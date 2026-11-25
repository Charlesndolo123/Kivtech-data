VERIFIED CUSTOMER NOTIFICATION FEED

The homepage will only display customer purchase notifications from recent-orders.json when each entry has verified=true and customer_consent=true. Keep the customer's permission and proof of the completed order before adding a record. Never invent a customer, phone number, location or purchase.

Example record (replace every value with a real, consented, verified order):
[
  {
    "verified": true,
    "customer_consent": true,
    "display_name": "Mary",
    "masked_phone": "0111*****23",
    "town": "Nakuru",
    "offer": "1.5 GB",
    "price": 105
  }
]

Use a masked phone number only. Do not add M-PESA transaction codes, full phone numbers, account details or other sensitive data. This static JSON file must be updated and redeployed to publish new entries. For automatic real-time updates, KivTech will need a secure order database/backend and a verified payment/order workflow; this static website does not currently have that backend.
