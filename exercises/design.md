**Exercise: Secure Design Principles for Backend API**

**Objective:** Apply secure design principles for a backend API.

**Scenario:** You are a developer working on a new e-commerce platform that allows customers to place orders online. The platform uses a RESTful API to manage user accounts, products, and orders.

Test the threat model that you've developed in the threat modeling exercise.

**Sensitive API Endpoints:**

1. **User Account Management**
        * `POST /users` (create a new user account)
        * `GET /users/{id}` (view a specific user account)
        * `PUT /users/{id}` (update a specific user account)
        * `DELETE /users/{id}` (delete a specific user account)
2. **Product Management**
        * `POST /products` (create a new product)
        * `GET /products/{id}` (view a specific product)
        * `PUT /products/{id}` (update a specific product)
        * `DELETE /products/{id}` (delete a specific product)
3. **Order Management**
        * `POST /orders` (place a new order)
        * `GET /orders/{id}` (view a specific order)
        * `PUT /orders/{id}` (update a specific order)
        * `DELETE /orders/{id}` (cancel a specific order)

Make sure the design follows the secure design principles for all the operations:

• Defense-in-Depth
• Fail Safe
• Least Privilege
• Separation of Duties
• Economy of Mechanism
• Complete Mediation
• Open Design
• Least Common Mechanism
• Psychological acceptability
• Weakest Link
• Leveraging Existing Components

** Bonus **

Design a protection system for secure storage of encryption keys. 

