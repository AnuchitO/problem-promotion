# Promotions requirements 

### Promo-1
+ shop: "Bonchon"
+ tagline: "Special Deal"
+ kind: "LIMITED"
+ titile: "฿35 Discount"
+ discount_type: "Fixed Amount"
+ discount: 35
+ minimum_spend: 350
+ expiry_date: "2024-12-31 23:59:59"
+ descriptions: ["Spend at least ฿350, get ฿35 OFF.", "Applicable only joining promotin shop and branches Bonchon."]

### Promo-2
+ shop: "all"
+ tagline: "Cashback maximum ฿100 for next purchase"
+ kind: "LIMITED"
+ titile: "Cashback 5%"
+ discount_type: "Percentage"
+ discount: 0.05
+ maximum_discount: 100
+ minimum_spend: 220
+ expiry_date: "2024-12-31 23:59:59"
+ descriptions: ["Cashback coupon. Spend at least ฿220, get 5% OFF (max ฿100).", "When spend at least ฿250 for next purchase", "Only for participating shops.", "Limited quota per day.", "Cashback coupon will be given within 48 hours after the transaction is completed."]

## Promo-3
+ shop: "all"
+ tagline: "Discount for Gadgets"
+ kind: "SPECIAL"
+ titile: "10% OFF"
+ discount_type: "Percentage"
+ discount: 0.1
+ maximum_discount: 100
+ minimum_spend: 170
+ expiry_date: "2024-12-31 23:59:59"
+ descriptions: ["Spend at least ฿170, get 10% OFF (max ฿100).", "Only for gadgets category.", "Limited quota per day."]

## Promo-4
+ shop: "central T1"
+ tagline: "Central The 1"
+ kind: "ONLY EPAYMENT"
+ titile: "฿50 Discount"
+ discount_type: "Fixed Amount"
+ discount: 50
+ maximum_discount: 50
+ minimum_spend: 300
+ expiry_date: "2024-12-31 23:59:59"
+ descriptions: ["Spend at least ฿300, get ฿50 OFF.", "Only for e-Payment.", "Applicable only joining promotin shop and branches Central The 1."]

## Promo-5
+ shop: "Dairy Queen"
+ tagline: "Discount ฿50"
+ kind: "LIMITED"
+ titile: "฿50 Discount"
+ discount_type: "Fixed Amount"
+ discount: 50
+ maximum_discount: 50
+ minimum_spend: 250
+ expiry_date: "2024-12-31 23:59:59"
+ descriptions: ["Spend at least ฿250, get ฿50 OFF.", "Applicable only joining promotin shop and branches Dairy Queen."]

## Promo-6
+ shop: "Pizza"
+ tagline: "Buy 1 Get 1 Free"
+ kind: "LIMITED"
+ titile: "Buy 1 Get 1 Free"
+ discount_type: "Free Item"
+ maximum_discount: 1
+ minimum_spend: 300
+ expiry_date: "2024-12-31 23:59:59"
+ descriptions: ["Buy 1 Get 1 Free.", "Applicable only joining promotin shop and branches Pizza."]

## Complex Senario
### Scenario-1
A ฿1000 item is discounted 30%. Then, additional discounts of 40% and 50% are applied to the already discounted price of the item.
What is its sale price, in baht, after the three successive discounts?
Answer: ฿210
Solution: 
1. 30% discount on ฿1000 = ฿700
2. 40% discount on ฿700 = ฿420
3. 50% discount on ฿420 = ฿210
another solution: 1000 * 0.7 * 0.6 * 0.5 = 210
because discount is 1 - discount_rate that mean 
30% discount is 1 - 0.3 = 0.7
40% discount is 1 - 0.4 = 0.6
50% discount is 1 - 0.5 = 0.5


