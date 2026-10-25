# Day 01 — Practical Exercise & Reflection

## Scenario A: Supermarket ERP Workflow
A customer purchases 5 kg rice, 2 L milk, and one packet of biscuits.

### Q1. Inventory Management
**Initial answer:** Check whether the store has 5 kg of rice.

**Improved understanding:** Check stock availability and, when the sale is posted, reduce the recorded rice stock by 5 kg. For example, 100 kg becomes 95 kg.

### Q2. Sales Transaction
**Initial answer:** Subtract 5 kg of rice from stock.

**Improved understanding:** Record product identifiers/names, quantities, unit prices, transaction date/time, taxes, discounts (if applicable), and total amount. The stock reduction belongs to the inventory process.

### Q3. Finance
**Initial answer:** Calculate the purchase amount.

**Improved understanding:** Account for the sale and payment, relevant taxes, and any outstanding customer balance; use the data in financial reporting.

### Q4. Low Stock
**Answer:** Alert the responsible person when stock becomes low.

**Extension:** A purchasing workflow may then be initiated to replenish stock.

### Q5. ABAP Developer
**Answer:** Build logic to retrieve products whose current stock is below the minimum required level.

**Conceptual pseudocode:**
```text
IF current_stock < minimum_stock
    DISPLAY product_name, current_stock, minimum_stock
ENDIF
```

In ABAP Cloud, use supported data models and released APIs where required.

## Scenario B: Correction Exercise
A supermarket starts with 50 biscuit packets. A customer buys 8 packets at ₹20 each and pays in cash.

1. **Inventory:** 50 − 8 = **42 packets remaining**.
2. **Sales:** Record product, quantity (8), unit price (₹20), transaction date/time, applicable taxes or discounts, and total (**₹160 before any taxes or discounts**).
3. **Finance:** Record cash payment, amount received, any applicable tax, and payment status. If ₹160 is the final amount and fully paid, the outstanding balance is ₹0.

## Scores & Reflection
| Assessment | Result |
| --- | --- |
| Theory quiz | 10/10 |
| Initial practical | 13/20 |
| Correction exercise | 5/5 |

**Reflection:** My initial answers mixed up inventory and sales responsibilities. After correction, I can distinguish sales transaction details, inventory stock changes, and finance payment records.

**Next step:** Learn SAP's presentation, application, and database layers.
