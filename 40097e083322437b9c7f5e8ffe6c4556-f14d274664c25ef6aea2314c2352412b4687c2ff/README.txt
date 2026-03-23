MONGOOSE CRUD PROJECT - SETUP INSTRUCTIONS
==========================================

1. Install Node.js from: https://nodejs.org/

2. Make sure MongoDB is installed and running locally.
   Download from: https://www.mongodb.com/try/download/community

3. Download/clone this Gist to a folder on your machine.

4. Open Terminal/Command Prompt in that folder.

5. Run: npm install
   (This installs express and mongoose)

6. Run: npm start

7. Server starts at http://localhost:3000

TEST THE API USING POSTMAN OR BROWSER:

  CREATE:   POST   http://localhost:3000/products
            Body (JSON): { "name": "Laptop", "price": 799.99, "description": "High-performance laptop", "category": "Electronics" }

  READ ALL: GET    http://localhost:3000/products

  READ ONE: GET    http://localhost:3000/products/PRODUCT_ID

  UPDATE:   PUT    http://localhost:3000/products/PRODUCT_ID
            Body (JSON): { "price": 899.99 }

  DELETE:   DELETE http://localhost:3000/products/PRODUCT_ID

FILES INCLUDED:
- server.js    : Main server with all CRUD routes
- package.json : Project dependencies (express, mongoose)
- README.txt   : This file