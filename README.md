# Seller Mobile App
Seller Mobile App is an app that has two different types of users: employees in various businesses and their customers. 

Customers use this app in order to see all available products/services and to create their order. Everytime they create a new order, employees that are logged in the app at that moment get a notification about it. In case a customer has some questions, he/she can call the employee by sending another notification.

Seller app gives employees access to all orders, list of all products/services offered by the business as well as their current availability in the store and existing tables/stores (depending on type of business). They can, as well, create and edit an order and send it to the cash register for processing.

This app is a part of the school project and communicates directly with [Cash Register Server](https://github.com/spusina1/CashRegisterServer) in order to get required information.
<p align="center">
<img src="https://github.com/kamberovicmubina/SellerMobileApp/blob/master/SellerApp/assets/LoginScreen.jpg" width="350" height="600">
</p>

## Get Started
Seller Mobile App is a React Native app which works both on Android and iOS devices. To build this app, you should have Node.js installed on your local machine.

After cloning the repository to your local machine, in the root directory:
* Install dependencies with `npm install` 

To run the app on your phone, first install Expo app on it. Optionally, you can run the app on a virtual device.

Start the app with 
* `npm start` or `expo start`
* Scan the QR code with your Expo app (Android) or the Camera app (iOS)
