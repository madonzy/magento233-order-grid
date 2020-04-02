# Module OrderGrid (technical task)

This module add columns: Coupon Code and Discount Amount, into the Order Grid in the admin panel of Magento.

*Requirements*:
- Magento 2.3.3

*Steps to install*:
1. Fetch the changes by composer (with git repository) or add it manually into app/code/Yeremenko/OrderGrid
2. bin/magento mod:en Yeremenko_OrderGrid
3. bin/magento set:upg

_Please note: Those colums would not be populated for old orders, with their values. But if that is required I can implement this by adding patch which is merging sales_order into sales_order_grid table with values for new columns._
