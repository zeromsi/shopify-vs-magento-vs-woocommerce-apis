Shopify

# Product:
Api doc: https://shopify.dev/api/admin-rest/2021-07/resources/product#top

json:

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
