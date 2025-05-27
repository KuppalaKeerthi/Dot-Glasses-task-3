# Dot-Glasses-task-3
Project Overview
This is a simple RESTful API built with Node.js and Express for managing articles. It allows users to create,
read, update, and delete articles stored in a MySQL database.
Environment Setup
1. Install Node.js and MySQL
2. Clone the repository
3. Run `npm install`
4. Start MySQL server and create the database
5. Run the server with `node index.js`
API Endpoints
POST /articles - Create a new article
GET /articles - Retrieve all articles
GET /articles/:id - Retrieve a single article by ID
PUT /articles/:id - Update article (rating/status)
DELETE /articles/:id - Delete article
