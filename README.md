# Django Assignment

## Prerequisite
- have python 3.10.7 installed
- use virtualenv is preferred

## Project Description
- there should be a ADMIN and SHOPPER user.
- ALL users must be able to login in order to call their respectives API.
- ONLY an ADMIN can add, edit, or remove products.
- A SHOPPER can add and remove a product to their cart.
- A SHOPPER can complete their respective cart as an order.
- A SHOPPER can retreive their PENDING order.
- ONLY an ADMIN can retreive all PENDING order.
- ONLY an ADMIN can mark a PENDING order as DELIVERED.
- A product has a name, price, and description. 
- A cart has multiple products.
- An order has multiple products, "PENDING" or "DELIVERED" states.
- A user has a ADMIN or SHOPPER type.

## Tasks
- install requirements into python environment
- create auth_app
- create ecommerce_app
- create user, product, cart, and order models
- create user, product, cart, and order serializers

## Important Notes: 
You are allowed to Google resources such as Django and Django rest framework documentation. Please feel free to upgrade Django if necessary. 
Also keep in mind that you do not need to build any UI i.e. using django templates or any other frameworks. If possible, we would like to see DRF UI for different API interactions.
