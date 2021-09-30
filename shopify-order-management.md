# Order:
Api doc: https://shopify.dev/api/admin-rest/2021-07/resources/order#resource_object
```
{
  "app_id": 1966818,
  "billing_address": {
    "zip": "T0E 0M0",
    "city": "Drayton Valley",
    "name": "Christopher Gorski",
    "phone": "(555)555-5555",
    "company": null,
    "country": "Canada",
    "address1": "2259 Park Ct",
    "address2": "Apartment 5",
    "latitude": "45.41634",
    "province": "Alberta",
    "last_name": "Gorski",
    "longitude": "-75.6868",
    "first_name": "Christopher",
    "country_code": "CA",
    "province_code": "AB"
  },
  "browser_ip": "216.191.105.146",
  "buyer_accepts_marketing": false,
  "cancel_reason": "customer",
  "cancelled_at": null,
  "cart_token": "68778783ad298f1c80c3bafcddeea",
  "checkout_token": "bd5a8aa1ecd019dd3520ff791ee3a24c",
  "client_details": {
    "browser_ip": "216.191.105.146",
    "user_agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_13_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/62.0.3202.94 Safari/537.36",
    "session_hash": "9ad4d1f4e6a8977b9dd98eed1e477643",
    "browser_width": 1280,
    "browser_height": 1320,
    "accept_language": "en-US,en;q=0.9"
  },
  "closed_at": "2008-01-10T11:00:00-05:00",
  "created_at": "2008-01-10T11:00:00-05:00",
  "currency": "USD",
  "current_total_discounts": "10.00",
  "current_total_discounts_set": {
    "current_total_discounts_set": {
      "shop_money": {
        "amount": "10.00",
        "currency_code": "CAD"
      },
      "presentment_money": {
        "amount": "5.00",
        "currency_code": "EUR"
      }
    }
  },
  "current_total_duties_set": {
    "current_total_duties_set": {
      "shop_money": {
        "amount": "164.86",
        "currency_code": "CAD"
      },
      "presentment_money": {
        "amount": "105.31",
        "currency_code": "EUR"
      }
    }
  },
  "current_total_price": "10.00",
  "current_total_price_set": {
    "current_total_price_set": {
      "shop_money": {
        "amount": "30.00",
        "currency_code": "CAD"
      },
      "presentment_money": {
        "amount": "20.00",
        "currency_code": "EUR"
      }
    }
  },
  "current_subtotal_price": "10.00",
  "current_subtotal_price_set": {
    "current_subtotal_price_set": {
      "shop_money": {
        "amount": "30.00",
        "currency_code": "CAD"
      },
      "presentment_money": {
        "amount": "20.00",
        "currency_code": "EUR"
      }
    }
  },
  "current_total_tax": "10.00",
  "current_total_tax_set": {
    "current_total_tax_set": {
      "shop_money": {
        "amount": "30.00",
        "currency_code": "CAD"
      },
      "presentment_money": {
        "amount": "20.00",
        "currency_code": "EUR"
      }
    }
  },
  "customer": {
    "id": 207119551,
    "note": null,
    "tags": "loyal",
    "email": "bob.norman@hostmail.com",
    "phone": "+13125551212",
    "state": "disabled",
    "currency": "USD",
    "addresses": {
      
    },
    "last_name": "Norman",
    "created_at": "2012-03-13T16:09:55-04:00",
    "first_name": "Bob",
    "tax_exempt": false,
    "updated_at": "2012-03-13T16:09:55-04:00",
    "total_spent": "0.00",
    "orders_count": "1",
    "last_order_id": 450789469,
    "tax_exemptions": {
      
    },
    "verified_email": true,
    "default_address": {
      
    },
    "last_order_name": "#1001",
    "accepts_marketing": false,
    "admin_graphql_api_id": "gid://shopify/Customer/207119551",
    "multipass_identifier": null
  },
  "customer_locale": "en-CA",
  "discount_applications": {
    "discount_applications": [
      {
        "type": "manual",
        "title": "custom discount",
        "value": "2.0",
        "value_type": "fixed_amount",
        "description": "customer deserved it",
        "target_type": "line_item",
        "target_selection": "explicit",
        "allocation_method": "across"
      },
      {
        "type": "script",
        "value": "5.0",
        "value_type": "fixed_amount",
        "description": "my scripted discount",
        "target_type": "shipping_line",
        "target_selection": "explicit",
        "allocation_method": "across"
      },
      {
        "code": "SUMMERSALE",
        "type": "discount_code",
        "value": "10.0",
        "value_type": "fixed_amount",
        "target_type": "line_item",
        "target_selection": "all",
        "allocation_method": "across"
      }
    ]
  },
  "discount_codes": [
    {
      "code": "SPRING30",
      "type": "fixed_amount",
      "amount": "30.00"
    }
  ],
  "email": "bob.norman@hostmail.com",
  "estimated_taxes": false,
  "financial_status": "authorized",
  "fulfillments": [
    {
      "id": 255858046,
      "status": "failure",
      "order_id": 450789469,
      "created_at": "2012-03-13T16:09:54-04:00",
      "updated_at": "2012-05-01T14:22:25-04:00",
      "tracking_number": "1Z2345",
      "tracking_company": "USPS"
    }
  ],
  "fulfillment_status": "partial",
  "gateway": "shopify_payments",
  "id": 450789469,
  "landing_site": "http://www.example.com?source=abc",
  "line_items": [
    {
      "id": 669751112,
      "sku": "IPOD-342-N",
      "name": "IPod Nano - Pink",
      "grams": 500,
      "price": "199.99",
      "title": "IPod Nano",
      "duties": [
        {
          "id": "2",
          "tax_lines": [
            {
              "rate": 0.1,
              "price": "16.486",
              "title": "VAT",
              "price_set": {
                "shop_money": {
                  "amount": "16.486",
                  "currency_code": "CAD"
                },
                "presentment_money": {
                  "amount": "10.531",
                  "currency_code": "EUR"
                }
              },
              "channel_liable": true
            }
          ],
          "shop_money": {
            "amount": "164.86",
            "currency_code": "CAD"
          },
          "presentment_money": {
            "amount": "105.31",
            "currency_code": "EUR"
          },
          "admin_graphql_api_id": "gid://shopify/Duty/2",
          "country_code_of_origin": "CA",
          "harmonized_system_code": "520300"
        }
      ],
      "vendor": "Apple",
      "taxable": true,
      "quantity": 1,
      "gift_card": false,
      "price_set": {
        "shop_money": {
          "amount": "199.99",
          "currency_code": "USD"
        },
        "presentment_money": {
          "amount": "173.30",
          "currency_code": "EUR"
        }
      },
      "tax_lines": [
        {
          "rate": 0.13,
          "price": "25.81",
          "title": "HST",
          "price_set": {
            "shop_money": {
              "amount": "25.81",
              "currency_code": "USD"
            },
            "presentment_money": {
              "amount": "20.15",
              "currency_code": "EUR"
            }
          },
          "channel_liable": true
        }
      ],
      "product_id": 7513594,
      "properties": [
        {
          "name": "custom engraving",
          "value": "Happy Birthday Mom!"
        }
      ],
      "variant_id": 4264112,
      "variant_title": "Pink",
      "total_discount": "5.00",
      "origin_location": {
        "id": 1390592786454,
        "zip": "V7Y 1G5",
        "city": "Toronto",
        "name": "Apple",
        "address1": "700 West Georgia Street",
        "address2": "1500",
        "country_code": "CA",
        "province_code": "ON"
      },
      "requires_shipping": true,
      "fulfillment_status": "fulfilled",
      "total_discount_set": {
        "shop_money": {
          "amount": "5.00",
          "currency_code": "USD"
        },
        "presentment_money": {
          "amount": "4.30",
          "currency_code": "EUR"
        }
      },
      "fulfillment_service": "amazon",
      "discount_allocations": [
        {
          "amount": "5.00",
          "amount_set": {
            "shop_money": {
              "amount": "5.00",
              "currency_code": "USD"
            },
            "presentment_money": {
              "amount": "3.96",
              "currency_code": "EUR"
            }
          },
          "discount_application_index": 2
        }
      ],
      "fulfillable_quantity": 1
    }
  ],
  "location_id": 49202758,
  "name": "#1001",
  "note": "Customer changed their mind.",
  "note_attributes": [
    {
      "name": "custom name",
      "value": "custom value"
    }
  ],
  "number": 1,
  "order_number": 1001,
  "original_total_duties_set": {
    "original_total_duties_set": {
      "shop_money": {
        "amount": "164.86",
        "currency_code": "CAD"
      },
      "presentment_money": {
        "amount": "105.31",
        "currency_code": "EUR"
      }
    }
  },
  "payment_details": {
    "avs_result_code": "Y",
    "credit_card_bin": "453600",
    "cvv_result_code": "M",
    "credit_card_number": "•••• •••• •••• 4242",
    "credit_card_company": "Visa"
  },
  "payment_gateway_names": [
    "authorize_net",
    "Cash on Delivery (COD)"
  ],
  "phone": "+557734881234",
  "presentment_currency": "CAD",
  "processed_at": "2008-01-10T11:00:00-05:00",
  "processing_method": "direct",
  "referring_site": "http://www.anexample.com",
  "refunds": [
    {
      "id": 18423447608,
      "note": null,
      "user_id": null,
      "order_id": 394481795128,
      "created_at": "2018-03-06T09:35:37-05:00",
      "processed_at": "2018-03-06T09:35:37-05:00",
      "transactions": [
        
      ],
      "order_adjustments": [
        
      ],
      "refund_line_items": [
        
      ]
    }
  ],
  "shipping_address": {
    "zip": "K2P0V6",
    "city": "Ottawa",
    "name": "Bob Bobsen",
    "phone": "555-625-1199",
    "company": null,
    "country": "Canada",
    "address1": "123 Amoebobacterieae St",
    "address2": "",
    "latitude": "45.41634",
    "province": "Ontario",
    "last_name": "Bobsen",
    "longitude": "-75.6868",
    "first_name": "Bob",
    "country_code": "CA",
    "province_code": "ON"
  },
  "shipping_lines": [
    {
      "code": "INT.TP",
      "price": "4.00",
      "title": "Small Packet International Air",
      "source": "canada_post",
      "price_set": {
        "shop_money": {
          "amount": "4.00",
          "currency_code": "USD"
        },
        "presentment_money": {
          "amount": "3.17",
          "currency_code": "EUR"
        }
      },
      "tax_lines": [
        
      ],
      "discounted_price": "4.00",
      "carrier_identifier": "third_party_carrier_identifier",
      "discounted_price_set": {
        "shop_money": {
          "amount": "4.00",
          "currency_code": "USD"
        },
        "presentment_money": {
          "amount": "3.17",
          "currency_code": "EUR"
        }
      },
      "requested_fulfillment_service_id": "third_party_fulfillment_service_id"
    }
  ],
  "source_name": "web",
  "subtotal_price": 398,
  "subtotal_price_set": {
    "shop_money": {
      "amount": "141.99",
      "currency_code": "CAD"
    },
    "presentment_money": {
      "amount": "90.95",
      "currency_code": "EUR"
    }
  },
  "tags": "imported, vip",
  "tax_lines": [
    {
      "rate": 0.06,
      "price": 11.94,
      "title": "State Tax",
      "channel_liable": true
    }
  ],
  "taxes_included": false,
  "test": true,
  "token": "b1946ac92492d2347c6235b4d2611184",
  "total_discounts": "0.00",
  "total_discounts_set": {
    "shop_money": {
      "amount": "0.00",
      "currency_code": "CAD"
    },
    "presentment_money": {
      "amount": "0.00",
      "currency_code": "EUR"
    }
  },
  "total_line_items_price": "398.00",
  "total_line_items_price_set": {
    "shop_money": {
      "amount": "141.99",
      "currency_code": "CAD"
    },
    "presentment_money": {
      "amount": "90.95",
      "currency_code": "EUR"
    }
  },
  "total_outstanding": "5.00",
  "total_price": "409.94",
  "total_price_set": {
    "shop_money": {
      "amount": "164.86",
      "currency_code": "CAD"
    },
    "presentment_money": {
      "amount": "105.31",
      "currency_code": "EUR"
    }
  },
  "total_shipping_price_set": {
    "shop_money": {
      "amount": "30.00",
      "currency_code": "USD"
    },
    "presentment_money": {
      "amount": "0.00",
      "currency_code": "USD"
    }
  },
  "total_tax": "11.94",
  "total_tax_set": {
    "shop_money": {
      "amount": "18.87",
      "currency_code": "CAD"
    },
    "presentment_money": {
      "amount": "11.82",
      "currency_code": "EUR"
    }
  },
  "total_tip_received": "4.87",
  "total_weight": 300,
  "updated_at": "2012-08-24T14:02:15-04:00",
  "user_id": 31522279,
  "order_status_url": {
    "order_status_url": "https://checkout.shopify.com/112233/checkouts/4207896aad57dfb159/thank_you_token?key=753621327b9e8a64789651bf221dfe35"
  }
}
```
