This is a basic E-commerce backend application developed using Node.js, Express, and MongoDB.
It offers REST APIs for handling users, products, and shopping cart operations.

## Features
- User registration with password hashing
- Product management and user-based cart handling
- Automatic timestamping for users and products

 ## Tech Stack 
- Node.js
- Express.js
- MongoDB
- Mongoose
- bcrypt
- REST APIs

## Cart Logic
- Each user has a separate cart
- Cart maintains productId and quantity (with default quantity of 1)
- If the product is already in the cart, the quantity is incremented by 1
- If the product is not in the cart, it is added to the cart with quantity set to 1
- Product information is displayed in the cart 






