# Database Queries

## find all customers that live in London. Returns 6 records.

Customers 4, 11, 16, 19, 53, 72

## find all customers with postal code 1010. Returns 3 customers.

Customers 12, 54, 64

## find the phone number for the supplier with the id 11. Should be (010) 9984510.

Supplier Heli Süßwaren GmbH & Co. KG

## list orders descending by the order date. The order with date 1997-02-12 should be at the top.

Top 10 in order: 66, 20, 71, 55, 51, 79, 7, 87, 16, 60

## find all suppliers who have names longer than 20 characters. You can use `length(SupplierName)` to get the length of the name. Returns 11 records.

SupplierIDs 2, 3, 5, 8, 10, 11, 12, 13, 14, 18, 19

## find all customers that include the word "market" in the name. Should return 4 records.

CustomerIDs 10, 32, 71, 89

## add a customer record for _"The Shire"_, the contact name is _"Bilbo Baggins"_ the address is _"1 Hobbit-Hole"_ in _"Bag End"_, postal code _"111"_ and the country is _"Middle Earth"_.

Record number 92 created.

## update _Bilbo Baggins_ record so that the postal code changes to _"11122"_.

Output: You have made changes to the database. Rows affected: 1
New Record: 92 The Shire Bilbo Baggins 1 Hobbit-Hole Bag End 11122 Middle Earth

## list orders grouped by customer showing the number of orders per customer. _Rattlesnake Canyon Grocery_ should have 7 orders.

Rattlesnake Canyon Grocery 65 10262 1996-07-22
Rattlesnake Canyon Grocery 65 10272 1996-08-02
Rattlesnake Canyon Grocery 65 10294 1996-08-30
Rattlesnake Canyon Grocery 65 10314 1996-09-25
Rattlesnake Canyon Grocery 65 10316 1996-09-27
Rattlesnake Canyon Grocery 65 10346 1996-11-05
Rattlesnake Canyon Grocery 65 10401 1997-01-01

## list customers names and the number of orders per customer. Sort the list by number of orders in descending order. _Ernst Handel_ should be at the top with 10 orders followed by _QUICK-Stop_, _Rattlesnake Canyon Grocery_ and _Wartian Herkku_ with 7 orders each.

## list orders grouped by customer's city showing number of orders per city. Returns 58 Records with _Aachen_ showing 2 orders and _Albuquerque_ showing 7 orders.

## delete all users that have no orders. Should delete 17 records.
