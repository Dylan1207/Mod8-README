# Backend API (Mod6-A6)

## Overview
This is a backend API built using Node.js and Express. It connects to a PostgreSQL database hosted on Render and allows users to retrieve, add, and update data.

## Table of Contents
- Installation
- API Documentation
- Database Setup
- Deployment
- Contributing
- License

## Installation & Setup
### Prerequisites:
- Node.js
- PostgreSQL
- npm

### Steps:
- git clone https://github.com/Dylan1207/Mod6-A6.git
- cd Mod6-A6
- npm install
- npm start

## API Documentation
GET /api/v1/items - Returns all items
POST /api/v1/items - Creates a new item
PUT /api/v1/items/:id - Updates an existing item

### Example Response:
{
  "id": 1,
  "name": "Item 1",
  "price": 10
}

## Database Setup
CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  name TEXT,
  price NUMERIC
);

## Deployment
The API is deployed on Render.
https://mod6-a6.onrender.com/api/v1/items

## Contributing
- Fork the repository
- Create a new branch
- Make changes
- Submit a pull request

## License
This project is licensed under the MIT License.