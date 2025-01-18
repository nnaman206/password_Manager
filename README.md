# Password Manager

A full-stack password manager application built with **React.js**, **Express.js**, **Node.js**, **MongoDB**, and **Tailwind CSS**. The application allows users to securely store, edit, and delete website usernames and passwords, both locally and in a database.

## Features

- **Add Passwords**: Store usernames and passwords for different websites.
- **Edit Passwords**: Update stored credentials as needed.
- **Delete Passwords**: Remove credentials securely.
- **Responsive Design**: Optimized for all device sizes using Tailwind CSS.
- **Local and Database Storage**: Flexibility to store passwords locally or in a MongoDB database.

## Tech Stack

**Frontend**:
- React.js
- Tailwind CSS

**Backend**:
- Express.js
- Node.js

**Database**:
- MongoDB

## Installation and Setup

### Prerequisites
- Node.js installed on your machine
- MongoDB setup (local or cloud-based)

### Steps to Run the Application

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nnaman206/password_Manager.git
   cd password_Manager
   ```

2. **Install Dependencies**:
   Navigate to the root folder and the frontend folder to install dependencies.

   For the backend:
   ```bash
   cd backend
   npm install
   ```

   For the frontend:
   ```bash
   cd ../frontend
   npm install
   ```



3. **Start the Backend Server**:
   ```bash
   cd backend
   npm start
   ```
4. **Start the Frontend Development Server**:
   ```bash
   cd ../frontend
   npm start
   ```

5. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000`.



## Usage

1. Open the application in your browser.
2. Add new credentials by filling in the required fields.
3. View all saved credentials on the homepage.
4. Edit or delete credentials using the respective buttons.

## Security
- **UUIDs** are used for unique identification of each password entry.
- Data is stored securely in MongoDB, ensuring confidentiality and integrity.

