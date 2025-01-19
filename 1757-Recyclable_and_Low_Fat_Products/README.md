# 1757. Recyclable and Low Fat Products

This repository contains the solution for the LeetCode SQL problem **1757. Recyclable and Low Fat Products**.

---

## Problem Description

Write an SQL query to find the IDs of products that are both recyclable and low fat.

The `Products` table contains the following columns:
- `product_id` (int): The ID of the product.
- `low_fats` (enum): Indicates whether the product is low fat ('Y' or 'N').
- `recyclable` (enum): Indicates whether the product is recyclable ('Y' or 'N').

### Example Input

| product_id | low_fats | recyclable |
|------------|----------|------------|
| 1          | Y        | N          |
| 2          | Y        | Y          |
| 3          | N        | Y          |
| 4          | Y        | Y          |

### Example Output

| product_id |
|------------|
| 2          |
| 4          |

---

