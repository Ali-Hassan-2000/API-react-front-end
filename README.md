# React Pets Frontend

A React frontend application for managing pets, connected to a MongoDB-backed Express API.

## 🚀 Overview

This React application provides a user interface for managing pets (create, read, update, delete operations). It connects to a separate backend API built with Express.js and MongoDB.

## 🔗 Backend Repository

This frontend is designed to work with the backend API from:  
**[API-routes-with-postman](https://github.com/Ali-Hassan-2000/API-routes-with-postman.git)**  

*Backend Features:*
- Express.js server
- MongoDB database
- RESTful API routes
- CRUD operations for pets
- Postman-tested endpoints

## 🎯 Usage

Once both servers are running:

1. **Access the application:** Open `http://localhost:5173` in your browser
2. **View pets:** See all pets from the database
3. **Add new pets:** Use the form to create new pet entries
4. **Update pets:** Click on a pet to view details and edit
5. **Delete pets:** Remove pets from the database

## 🔧 API Endpoints Used

This frontend communicates with the backend using these endpoints:

- `GET /pets` - Fetch all pets
- `POST /pets` - Create a new pet
- `PUT /pets/:id` - Update a specific pet
- `DELETE /pets/:id` - Delete a specific pet