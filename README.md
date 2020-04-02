# Module OrderGrid (technical task)

This module add columns: Coupon Code and Discount Amount, into the Order Grid in the admin panel of Magento.

*Requirements*:
- Magento 2.3.3

*Steps to install*:
1. Fetch the changes by composer (with git repository) or add it manually into app/code/Yeremenko/OrderGrid
2. bin/magento mod:en Yeremenko_OrderGrid
3. bin/magento set:upg

_Please note: this solution assumes that your shop don't have any old orders, that mean those colums would not be updated with their value for old orders. But if that is required I can implement this by adding patch which is updating sales_order_grid table with values for new columns._
