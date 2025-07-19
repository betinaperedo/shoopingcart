# shoopingcart
Keep Track of shooping carts

# shoopingcart
Keep Track of shooping carts
Problem : We have a hard time keeping track of all our shopping carts. We need
help designing a solution to this problem.
Assumptions
1) Each user has one shooping cart
2) One cart has a list of (Items,quantity)
3) Items can be removed
4) Items can be increased
5) User has a username , cart
6) We wont handle inventory
7) Do we support guest users?
8) items  will be stored in memory
9) Do carts expire after some time?
10) we will define the API endpoinds
11) We arent implementing logging
12) Auhtentitacion will be handled via SSO
13) No promo codes
14) Pyament will be out of scope


Cart
Long cartId;
Long userId;
List<CardItem> cardItems;
Date createdAt;
Date modifiedAt;

CartItem
Long itemId;
Integer quantity;

Item
Long itemId;
String description;
Double price;

Order
LOng orderId;
Long userId;
Long cartId;
String Status; (ENUM : CREATED, PENDING, COMPLETED)
Datetime creationTime;
DateTime modificationTime;

src/main/java/com/cart
   controller
   service
   model
   repository
   exception




