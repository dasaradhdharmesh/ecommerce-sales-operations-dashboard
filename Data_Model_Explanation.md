🔗 Data Model & Relationships
# Data Modeling Approach

This dashboard follows a Star Schema design for optimized performance and scalability.

## Fact Tables:

• FactOrders
• FactOrderItems
• OrderPayments
• OrderReviews

## Dimension Tables:

• DimDate
• Customers
• Sellers
• Products

## Relationships

• FactOrders → Customers (Many-to-One)
• FactOrders → DimDate (Many-to-One)
• FactOrderItems → Products (Many-to-One)
• FactOrderItems → Sellers (Many-to-One)
• OrderReviews → FactOrders (One-to-Many)
• OrderPayments → FactOrders (One-to-Many)

** All relationships are single-directional filtering from dimension to fact. **
