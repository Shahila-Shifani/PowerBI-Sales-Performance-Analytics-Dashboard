# Power Query cleaning guide

1. Import the Orders table.
2. Check `Order Date` and `Ship Date` are Date type.
3. Check `Sales`, `Profit`, `Quantity` and `Discount` are numeric.
4. Remove rows where Order ID is blank.
5. Trim text columns such as Region, Category and Product Name.
6. Check for unexpected null values before replacing or removing them.
7. Select Close & Apply.

Do not remove negative profit values: they represent loss-making orders and are useful for analysis.
