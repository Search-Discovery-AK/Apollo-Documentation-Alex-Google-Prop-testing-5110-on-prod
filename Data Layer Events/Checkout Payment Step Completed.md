# Checkout Payment Step Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "add_payment_info",
  "detailed_event": "Checkout Payment Step Completed",
    "ecommerce": {
        "count_checkout_payment_step_completions": "<count_checkout_payment_step_completions>",
        "coupon": "<coupon>",
        "currency": "<currency>",
        "items": [
            {
                "item_id": "<item_id>",
                "item_name": "<item_name>"
            }
        ],
        "payment_method": "<payment_method>",
        "value": <value>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|ecommerce.count_checkout_payment_step_completions|number|Captures the specific chat service line used. \(i.e., the agent\)||||||||
|ecommerce.coupon|string|Order-level coupon code used for a purchase.|summer\_fun|||||||
|ecommerce.currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|ecommerce.items[n].item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|ecommerce.items[n].item_name|string|Item Name \(context-specific\).|jeggings|||||||
|ecommerce.payment_method|string|The chosen method of payment.|credit card, gift card, paypal, apple pay|||||||
|ecommerce.value|number|The monetary value of the event.|7.77, 239.55, 659|||||||




