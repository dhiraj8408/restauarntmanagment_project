# Restuarant Database managment
A mini project built in c which manages the database system of restaurants and provides a user interface to perform a set of instructions
The problem Statement for the code which we made is as follows:

Problem Statement:
Online ordering of food now-a-days is common. Managing the system is a tedious task. The goal here is to design a
system which performs the task.<br />
Create a list of restaurants in a city. Each restaurant is with attributes:<br />
a. Listing of generic food items and their respective prices for given quantity. <br />
b. Special items available at the restaurant and their prices. <br />
c. Special Item of the day and its price. <br />
d. Service time required for a given quantity of every food item. <br />
The list of restaurant records has to be in sorted order based on the key (Name and Address) i.e. the list of restaurants is
primarily sorted on name-of-restaurant. If two or more restaurants are having same name, then they are sorted on their
address.
Also, users are placing orders with the restaurants. Maintain a live record of orders for each restaurant. For every order,
the order time, user-name, user-phone number, user-address, food-item ordered, quantity of food items ordered and
expected delivery time are to be maintained. The delivery time can be calculated by considering service time for all the
food items (make appropriate assumptions in this calculation). The list of active/live orders should be in the sorted order
of first the order time and then the delivery time.
The list of restaurant records has to be in sorted order based on the key (Name and Address).
Also, maintain a database of live records of orders for each restaurant. Every order comes with order-time, food-item
ordered, quantity of food items ordered and the expected delivery time. The live records should be sorted with respect to
order-time and for same order- times, based on delivery time.
The following operations are to be defined so as to make the system function properly.

a. getMinTime() – Given food item and quantity, outputs the name, address and delivery time of the restaurant
taking minimum time to deliver the food order.<br />
Input: food order and quantity<br />
Output: restaurant-name, restaurant-address, time required to deliver.<br /><br />

b. getItemAvailability() – For the given food item, outputs the list of restaurants having the food item and respective
prices.<br />
Input: food item<br />
Output: list of restaurants and item with price at every restaurant<br /><br />
c. placeOrder() – Places an order for the food item.<br />
Input: list of items, quantity, user-name, user-phone-number, user-address<br />
Output: orderID<br />
d. getItemListInSortedOrder() – For a given restaurant, outputs list of items in the sorted order of names.<br />
Input: restaurant name<br />
Output: list of items in restaurant in sorted order based on name<br /><br />
e. getItemListInAreaSortedOrder() – For a given area, prints list of food-items available in that area in the sorted
order of restaurants.<br />
Input: Area<br />
Output: list of items available items in sorted order based on name of restaurant for restaurants in the given area<br /><br />
f. getAllSpecialItemListinSortedOrder() - Gives list of special items in a list of restaurants<br />
Input: restaurant list<br />
Output: list of special items in the restaurants of input restaurant-list in sorted order based on item-name and
price, also print the corresponding restaurant-name and its address<br /><br />
g. getItemofDayListinSortedOrder() – Gives a list of “Items-of-day” in the restaurants in the given area<br />
Input: area<br />
Output: list of all “item of the day” in all restaurant in sorted order based on food-item-name and food-item-price<br /><br />
h. getCommonItem() – Finds common food-item in the restaurant list<br />
Input: restaurant list<br />
Output: Common items present in the restaurants of the input restaurant-list given in the sorted order based on
item-name. List prices of the items in different restaurants.<br /><br />
i. getAllUniqueItem()<br />
Input: restaurant list<br />
Output: unique items present in each restaurant of input restaurant-list in sorted order based on item-name and
price. Also print name of the restaurant and its address.<br /><br />

<br /><br /> 
Based on the problem statement we decide to make use of structures in c and defined the structures accordingly
we initialized the databases to null values to avoid garbage values
we used file handling in c to provide the input database of restaurnats
we have used array of strurctures to implement all the databases that were required
<br />
Images of the user interface created are attached to the repository
