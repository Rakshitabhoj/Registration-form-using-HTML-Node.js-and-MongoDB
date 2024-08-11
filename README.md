# Registration Form Using HTML, Node.js, and MongoDB

## Overview
This project is a simple registration form that demonstrates how to create a user registration system using HTML for the front-end, Node.js for backend processing, and MongoDB for data storage. It captures user input via a form, validates the data, and stores it securely in a MongoDB database.

## Features
- **User-Friendly Interface:** A responsive and clean HTML form that gathers user details.
- **Server-Side Processing:** Utilizes Node.js to handle form submissions and interact with the MongoDB database.
- **Data Storage:** Stores user information in a MongoDB database for persistent data management.
- **Validation:** Basic validation on both client and server sides to ensure data accuracy.

## Technologies Used
- **HTML**: For creating the registration form interface.
- **Node.js**: For backend server operations and processing user data.
- **MongoDB**: For storing user data in a NoSQL database.

## Installation

### Prerequisites
- **Node.js**: Ensure you have Node.js installed. You can download it [here](https://nodejs.org/).
- **MongoDB**: Make sure MongoDB is installed and running. You can download it [here](https://www.mongodb.com/).

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rakshitabhoj/Registration-form-using-HTML-Node.js-and-MongoDB.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd registration process
   ```
3. **Install the required dependencies:**
   ```bash
   npm init
   npm install express body-parser mongoose nodemon
   ```
4. **Set up environment variables:**
   - Add your MongoDB connection string:
     ```
     MONGODB_URI=mongodb://localhost:27017
     ```

5. **Start the server:**
   ```bash
   node index.js
   ```
6. **Access the application:**
   Open your browser and go to `http://localhost:3000` to view the registration form.

## Usage
1. Open the registration form in your browser.
2. Enter the required details such as name, email, and password.
3. Submit the form. The data will be stored in the MongoDB database.
4. You can view and manage the stored data using MongoDB's management tools.

## Future Enhancements
- Implement user authentication and session management.
- Integrate password hashing to enhance security.
- Add a front-end framework like React for a more dynamic user interface.
- Implement email verification for new registrations.

