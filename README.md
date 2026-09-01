# Book API (Node.js + Express)

##  Overview
A simple REST API to manage a list of books using Node.js and Express.  
Supports CRUD operations (Create, Read, Update, Delete) with in-memory storage.

##  How to Run
1. Install dependencies:
  npm install
2. Start the server:
  node server.js
3. The server will run at:
  http://localhost:3000

## Endpoints
  -GET /books → Get all books

  -POST /books → Add a new book
  ** Example body:**
  {
    "title": "Clean Code",
    "author": "Robert C. Martin"
  }
  -PUT /books/:id → Update a book by ID

  -DELETE /books/:id → Delete a book by ID

## Tools Used
  -Node.js
  -Express
  -Postman (for testing)

## Notes
Data is stored in memory, so it resets each time the server restarts.
---
