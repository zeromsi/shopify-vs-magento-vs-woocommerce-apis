Shopify

# Product:
Api doc: https://shopify.dev/api/admin-rest/2021-07/resources/product#top

product json:

```xml
{
  "body_html": "It's the small iPod with a big idea: Video.",
  "created_at": "2012-02-15T15:12:21-05:00",
  "handle": "ipod-nano",
  "id": 632910392,
  "images": [
    {
      "id": 850703190,
      "src": "http://example.com/burton.jpg",
      "width": 110,
      "height": 140,
      "position": 1,
      "created_at": "2018-01-08T12:34:47-05:00",
      "product_id": 632910392,
      "updated_at": "2018-01-08T12:34:47-05:00",
      "variant_ids": [
        {
          
        }
      ]
    }
  ],
  "options": {
    "id": 594680422,
    "name": "Color",
    "values": [
      "Pink",
      "Red",
      "Green",
      "Black"
    ],
    "position": 1,
    "product_id": 632910392
  },
  "product_type": "Cult Products",
  "published_at": "2007-12-31T19:00:00-05:00",
  "published_scope": "global",
  "status": "active",
  "tags": "Emotive, Flash Memory, MP3, Music",
  "template_suffix": "special",
  "title": "IPod Nano - 8GB",
  "updated_at": "2012-08-24T14:01:47-04:00",
  "variants": [
    {
      "id": 808950810,
      "sku": "IPOD2008PINK",
      "grams": 567,
      "price": 199.99,
      "title": "Pink",
      "weight": 0.2,
      "barcode": "1234_pink",
      "option1": "Pink",
      "taxable": true,
      "position": 1,
      "created_at": "2012-08-24T14:01:47-04:00",
      "product_id": 632910392,
      "updated_at": "2012-08-24T14:01:47-04:00",
      "weight_unit": "kg",
      "compare_at_price": null,
      "inventory_policy": "continue",
      "inventory_item_id": 341629,
      "requires_shipping": true,
      "inventory_quantity": 10,
      "fulfillment_service": "manual",
      "inventory_management": "shopify"
    }
  ],
  "vendor": "Apple"
}
```
# options
The custom product properties. For example, Size, Color, and Material. Each product can have up to 3 options and each option value can be up to 255 characters. Product variants are made of up combinations of option values. Options cannot be created without values. To create new options, a variant with an associated option value also needs to be created.

# status
The status of the product. Valid values:
- active: The product is ready to sell and is available to customers on the online store, sales channels, and apps. By default, existing products are set to active.
- archived: The product is no longer being sold and isn't available to customers on sales channels and apps.
- draft: The product isn't ready to sell and is unavailable to customers on sales channels and apps. By default, duplicated and unarchived products are set to draft.

# variants
An array of product variants, each representing a different version of the product.
The position property is read-only. The position of variants is indicated by the order in which they are listed.

To manage variants: 
Api doc: https://shopify.dev/api/admin-rest/2021-07/resources/product-variant#resource_object

variant object:

```
{
  "barcode": "1234_pink",
  "compare_at_price": "299.00",
  "created_at": "2012-08-24T14:01:47-04:00",
  "fulfillment_service": "manual",
  "grams": 567,
  "id": 808950810,
  "image_id": 434522,
  "inventory_item_id": 342916,
  "inventory_management": "shopify",
  "inventory_policy": "continue",
  "inventory_quantity": 10,
  "old_inventory_quantity": 5,
  "inventory_quantity_adjustment": 5,
  "option": {
    "option1": "Pink"
  },
  "presentment_prices": {
    "presentment_prices": [
      {
        "price": {
          "amount": "199.99",
          "currency_code": "USD"
        },
        "compare_at_price": {
          "amount": "249.99",
          "currency_code": "USD"
        }
      },
      {
        "price": {
          "amount": "158.95",
          "currency_code": "EUR"
        },
        "compare_at_price": {
          "amount": "198.95",
          "currency_code": "EUR"
        }
      },
      {
        "price": {
          "amount": "143.00",
          "currency_code": "GBP"
        },
        "compare_at_price": {
          "amount": "179.00",
          "currency_code": "GBP"
        }
      },
      {
        "price": {
          "amount": "22400",
          "currency_code": "JPY"
        },
        "compare_at_price": {
          "amount": "28000",
          "currency_code": "JPY"
        }
      }
    ]
  },
  "position": 1,
  "price": "199.00",
  "product_id": 632910392,
  "requires_shipping": true,
  "sku": "IPOD2008PINK",
  "taxable": true,
  "tax_code": "DA040000",
  "title": "Pink",
  "updated_at": "2012-08-24T14:01:47-04:00",
  "weight": 100,
  "weight_unit": "oz"
}
```

# fulfillment_service
The fulfillment service associated with the product variant. Valid values: manual or the handle of a fulfillment service.A Fulfillment Service is a third party warehouse that prepares and ships orders on behalf of the store owner. Fulfillment services charge a fee to package and ship items and update product inventory levels. Some well known fulfillment services with Shopify integrations include: Amazon, Shipwire, and Rakuten. When an app registers a new FulfillmentService on a store, Shopify automatically creates a Location that's associated to that fulfillment service.

To manage fullfillment service:
api doc: https://shopify.dev/api/admin-rest/2021-07/resources/fulfillmentservice#top
