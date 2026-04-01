# 📚 Mini e-Library Application  

A lightweight e-Library management system designed to simplify digital book management and user access in small to medium-scale applications.

Built with **Node.js**, **Express.js**, **MongoDB**, and **Vue.js**, the project provides secure user management, JWT-based authentication, and book CRUD operations. It follows a modular structure for scalability and easy integration with modern web applications.

## Features  
- **User Management**: Registration, login, and JWT-based authentication  
- **Authorization**: Public access for viewing books, restricted access for adding/updating/deleting  
- **Book Management**: Create, read, update, and delete books via RESTful API  
- **Database**: MongoDB with Mongoose models for users and books  
- **Frontend**: Vue.js interface for seamless user interaction  

## Tech Stack  
- **Backend:** Node.js, Express.js, MongoDB, Mongoose, JWT  
- **Frontend:** Vue.js  
- **Others:** dotenv, bcrypt, express-validator  


## 🔑 Workflow  
1. **User Registration & Login**  
   - Users register and are stored in the database  
   - On successful login, a **JWT token** is generated  
   - Token is used for authentication in subsequent requests  

2. **Authorization**  
   - Public: View all books (GET)  
   - Authenticated users: Add, update, or delete books  

3. **Book Operations**  
   - Add new book (**POST**)  
   - Get all books (**GET**)  
   - Update book details (**PUT**)  
   - Delete book (**DELETE**)  
