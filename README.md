# User Authentication App

This project is a user authentication application built using Node.js, Express.js, and Mongoose. It allows users to log in, register, and view their email along with a logout option. If a user does not exist during login, they are redirected to the registration page. 

## Features

- User Registration
- User Login
- Protected Routes
- Display User Email
- User Logout

## Technologies Used

- Node.js
- Express.js
- Mongoose
- MongoDB
- EJS (Embedded JavaScript templates)
- bcrypt (for password hashing)
- cookie-parser (for parsing cookies)
- dotenv (for environment variables)
- jsonwebtoken (for JWT authentication)

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/shashankaz/backend-signup-login.git
cd backend-signup-login
```

2. **Install dependencies:**

```bash
npm install
```

3. **Set up environment variables:**

Create a `.env` file in the root directory and add the following:

```
PORT=3000
MONGO_URI=your_mongodb_connection_string
```

Replace `your_mongodb_connection_string` with your actual MongoDB connection string.

1. **Start the application:**

```bash
npm start
```

The application will be running on `http://localhost:3000`.

## Usage

### Register a New User

- Navigate to `http://localhost:3000/register`
- Fill out the registration form and submit.

### Login

- Navigate to `http://localhost:3000/login`
- Fill out the login form and submit.
- If the user does not exist, you will be redirected to the registration page.

### Profile

- After logging in, you will be redirected to the profile where you can see your email and a logout button.

### Logout

- Click the logout button to log out of the application.

## Acknowledgments

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [bcrypt](https://www.npmjs.com/package/bcrypt)
- [cookie-parser](https://www.npmjs.com/package/cookie-parser)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
- [EJS](https://ejs.co/)