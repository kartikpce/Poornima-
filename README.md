# Poornima-
Introduction
The Food Delivery System is a project designed to simulate a food delivery service using Object-Oriented Programming (OOP) principles in C++. This system allows users to order food from various restaurants, and manage orders, customers, and deliveries efficiently.

##Features
User Registration and Login: Allows new users to register and existing users to log in.
Restaurant Management: Manage restaurant information including menu items and prices.
Order Management: Place new orders, view order history, and track the status of current orders.
Delivery Management: Assign and track delivery personnel and their deliveries.
Payment System: Handle payments and generate invoices for completed orders.
Class Structure
The project utilizes the following classes to manage its functionality:

1. User
Attributes: userID, username, password, email, address
Methods: registerUser(), login(), updateProfile()
2. Restaurant
Attributes: restaurantID, name, address, menu
Methods: addMenuItem(), removeMenuItem(), updateMenuItem()
3. MenuItem
Attributes: itemID, name, description, price
Methods: displayItemDetails()
4. Order
Attributes: orderID, userID, restaurantID, items, status, totalAmount
Methods: placeOrder(), cancelOrder(), updateOrderStatus()
5. Delivery
Attributes: deliveryID, orderID, deliveryPersonID, status, deliveryTime
Methods: assignDelivery(), updateDeliveryStatus(), trackDelivery()
6. Payment
Attributes: paymentID, orderID, amount, paymentMethod, paymentStatus
Methods: processPayment(), generateInvoice()

##Usage
Register a new user or log in with existing credentials.
Browse available restaurants and their menus.
Place an order by selecting menu items from a restaurant.
Track the status of your order and view delivery details.
Make a payment for your order and receive an invoice.
