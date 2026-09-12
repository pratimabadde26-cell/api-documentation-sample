# api-documentation-sample
**simple-grocery-api-documentation**

**Overview**

This project provides technical documentation for the Simple Grocery Store API, a sandbox API that allows users to place grocery orders for collection from a store.

The documentation is based on API testing and a Postman collection and is designed to provide developers with clear information about the available endpoints, parameters, request and response examples, and HTTP status codes.

**API Version**

Version: 1.0

**Base URL**

https://simple-grocery-store-api.glitch.me


**API Resources**

The API documentation covers the following resources:

**Status** — Check whether the API is running.

**Products**— Retrieve product information.

**Carts** — Create and manage shopping carts and cart items.

**Orders**— Create and manage grocery orders.

**API Authentication** — Register an API client and obtain an access token.

**Documentation**

**Section**	                        **Description**      

Overview	                        Introduction to the API                    

Authentication                  	API client registration and authentication

Status	                          Check the API status

Products	                        Retrieve product information       

Carts	                            Create and manage carts    

Orders	                          Create and manage orders    

Error Handling	                  HTTP status codes and error responses      


**Tools**

The API was tested using Postman.

The original Postman collection is included in this repository for reference.

**Project Purpose**

This project demonstrates my ability to:

 Analyse an API and its endpoints
 
 Create structured API reference documentation
 
 Document request parameters and responses
 
Explain HTTP status codes and errors

 Provide practical request and response examples
 
 Transform API testing information into developer-focused documentation

**API Availability**

The API provides a status endpoint that can be used to check whether the service is running.

https://simple-grocery-store-api.glitch.me/status

**Status**

**Get /Status**

{

  "status": "UP"
  
}

**Products**

The Products endpoints allow you to retrieve product information.

You can:

•	Retrieve products.

•	Retrieve a specific product by ID.

•	Filter products by category and availability.

**Carts**

The Carts endpoints allow you to create and manage shopping carts.

You can:

•	Create a new cart.

•	Retrieve a cart.

•	Add an item to a cart.

•	Modify an item.

•	Replace an item.

•	Delete an item.

**Orders**

The Orders endpoints allow you to create and manage grocery orders.

**API Authentication**

The API provides an endpoint for registering a new API client and obtaining an access token.

**API Documentation Structure**

This documentation is organised into the following sections:

•	Authentication

•	Status

•	Products

•	Carts

•	Orders

•	Error Handling



