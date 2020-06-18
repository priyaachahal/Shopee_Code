### Project 1 : Order Brushing
In this, we have to find out the shops who are suspected of conducting order brushing, if there concentrate rate >= 3.
And in the next part, we have to find out the highest proportion of orders (by userid) to a shop that might have conducted order brushing (include only shops with order brushing).
OrderID - distinct transaction on Shopee
ShopID : distinct seller on Shopee
userid: distinct buyer on Shopee
Time : exact order time an order was placed

Concentrate rate = 
**Number of Orders within 1 hour** / **Number of Unique Buyers within 1 hour**
