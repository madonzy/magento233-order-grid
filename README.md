# Module OrderGrid (technical task)

Requirements:
- Magento 2.3.3

This module add columns: Coupon Code and Discount Amount, into the Order Grid in the admin panel of Magento.

_Please note: this solution assumes that your shop don't have any old orders, that mean old orders would not be updated with this value. But if that is required I can implement it by adding patch which is updating sales_order_grid table with values for new columns._
