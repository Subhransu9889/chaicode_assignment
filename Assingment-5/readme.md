## Database Design and ER Diagram

# Core Idea of the Design

We separate Product (what is being sold) from Inventory (how many exist) because:

Thrift items → unique (1 piece)
Handmade items → multiple units

This avoids messy logic and keeps the system scalable.

## ER Diagram

![ER Diagram](/Assingment-5/ER-DAIGRAM.png)

## Database Implementation

