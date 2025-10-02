# Flowcharts & Process Diagrams

## Customer Order Flow
```
+-------------------+
|  Customer Places  |
|     Vehicle Order |
+--------+----------+
         |
         v
+--------+----------+
|  Order Validation |
+--------+----------+
         |
         v
+--------+----------+
| Dealer Assignment |
+--------+----------+
         |
         v
+--------+----------+
|  Stock Check      |
+--------+----------+
         |
         v
+--------+----------+
|  Order Processed  |
+-------------------+
```

## Stock Validation Flow
```
+-------------------+
|  New Order        |
+--------+----------+
         |
         v
+--------+----------+
|  Check Inventory  |
+--------+----------+
         |
   +-----+-----+
   |           |
   v           v
In Stock   Out of Stock
   |           |
   v           v
Reserve   Notify/Backorder
   |           |
   v           v
Complete   Await Stock
```
