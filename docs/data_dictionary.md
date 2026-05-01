## Data Dictionary

- Month: Time period (Jan–Dec)
- Category: Product category
- ProductName: Product identifier
- UnitsSold: Units sold in the month
- InventoryOnHand: Available inventory
- ReorderPoint: Threshold to trigger reorder
- UnitCost: Cost per unit
- Revenue: UnitsSold * UnitCost
- StockoutRisk: Flag when InventoryOnHand < ReorderPoint
- OverstockRisk: Flag when InventoryOnHand > threshold
- ReorderRecommendation: Action suggestion
