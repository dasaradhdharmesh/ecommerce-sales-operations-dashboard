## 📊 Key DAX Measures Used

## Total Revenue
Total Revenue =
SUM(olist_order_payments_dataset[payment_value])

## Total Orders
Total Orders =
DISTINCTCOUNT(FactOrders[order_id])

## Average Order Value (AOV)
Average Order Value =
DIVIDE([Total Revenue], [Total Orders])

## On-Time Orders
On-Time Orders =
CALCULATE(
    COUNT(FactOrders[order_id]),
    FactOrders[delivery_status] = "On-Time"
)

## Late Delivery %
Late Delivery % =
DIVIDE([Late Orders], [Total Orders])

## Average Review Score
Average Review Score =
AVERAGE(olist_order_reviews_dataset[review_score])

## Units Sold
Units Sold =
SUM(FactOrderItems[order_item_id])


## All measures were created using star schema modeling principles to ensure optimized performance and accurate aggregations.
