# SQLAlchemy - Stores 

An API that allows you to create stores and post items with prices. You can get specific items/store, update prices of items, delete stores/items, and view all stores/items.

Build with Flask-SQLAlchemy, Flask-RESTful, Flask-JWT using Python. Deployed on Heroku with Postgres database.

To test this API and database, please download Postman and use this collection to make requests:

https://www.getpostman.com/collections/13bfcc5b895ed8464f6b

Begin by creating a user using /register (edit the body to create your name and password) and then /auth to authenticate it.   

After that, you can now create a store using POST /store/<name> and add items to it using POST /item/<name> (edit the body to include price and store_id)  
  
GET /items to see all items.  
GET /item/<name> to get a specific item.  
GET /stores to see all stores.  
GET /store/<name> to get a specific store.  
PUT /item/<name> to create a new item or edit an exist item.  
DEL /item/<name> to delete an item.  
DEL /store/<name> to delete a store.  
