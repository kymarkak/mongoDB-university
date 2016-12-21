MongoMart
===================

Final project for M101JS course.

### How to run MongoMart application

1. Clone the MongoMart repository.
2. Install the dependencies.
3. Make sure you have a mongod running version 3.2.x of MongoDB.
4. Import the "item" collection: mongoimport --drop -d mongomart -c item data/items.json
5. Import the "cart" collection: mongoimport --drop -d mongomart -c cart data/cart.json
6. Run the application by typing "node mongomart.js" in the mongomart directory.
7. In your browser, visit http://localhost:3000.