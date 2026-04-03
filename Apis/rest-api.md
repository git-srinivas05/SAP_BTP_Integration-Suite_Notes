# REST API

## Definition
REST API is a way for systems to communicate over HTTP using standard methods.

##The 5 rules for REST api
-Use HTTP/HTTPS a internet protocall for communication
-Use URL as address 
-Stateless-servers forget client information after each call
-Use JSON/XLM as a data format 
-One resourcess and one URL

## Why it matters
All modern integrations (including SAP BTP) use REST APIs for communication.

## Real Example(METHODS)
GET /orders → fetch all orders  
POST /orders → create a new order
PUT /orders data → Update/replace data 
PATCH /orders data → Update the data partially or few records only 
DELETE /orders → Delete the orders

## Key Points
- Uses HTTP protocol
- Stateless
- Uses JSON or XML
- Resource-based (URL represents data)
