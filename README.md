# Data-Manipulation-language-DML-Checkpoint

1. Inserting into the Customer Table:
INSERT INTO Customer (Customer_id, customer_Name, customer_Tel)
VALUES 
(1, 'Tarek', '0600000001'),
(2, 'Lina', '0600000002'),
(3, 'Ali', '0600000003');


2. Inserting into the Product Table:
INSERT INTO Product (Product_id, product_name, category, Price)
VALUES 
(1, 'Laptop', 'Electronics', 1200),
(2, 'Smartphone', 'Electronics', 800),
(3, 'Table', 'Furniture', 150);


3. Inserting into the Orders Table:
INSERT INTO Orders (Customer_id, Product_id, OrderDate, quantity, total_amount)
VALUES 
(1, 1, '2024-09-25', 1, 1200),   -- Tarek buys 1 Laptop
(2, 2, '2024-09-26', 2, 1600),   -- Lina buys 2 Smartphones
(3, 3, '2024-09-27', 1, 150);    -- Ali buys 1 Table
