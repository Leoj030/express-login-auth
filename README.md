# Login Auth

Thank you for checking out this repository! This project demonstrates a simple **login authentication system** built with **Express.js**.

## Getting Started

### 1. Install Dependencies

Before running the application, make sure to install the required dependencies by running:

```bash
cd server && npm install
```

This will change the current directory to the server, and will install the neccessary dependencies there.

---

### 2. Create your own Environment Config

You'll need to create your own environment configuration and fill it with your own values. There is a file named .env.example in the repository with the following variables:

```js
MONGODB_URI = your_mongodb_uri
JWT_SECRET = your_jwt_secret
NODE_ENV = development
SMPT_USER = your_smpt_user
SMPT_PASS = your_smpt_pass
SENDER_EMAIL = your_sender_email
```

---

### 3. Running The Server

You have two options for running the server:

**Development Mode:**
    Start the server with nodemon so it automatically refreshes when you make changes:

```bash
npm run devStart
```

**Production Mode:**
    Run the server once without automatic refreshing (suitable for deployment):

```bash
npm start
```

### 4. Testing the System

You can test the API endpoints using Postman or any similar tool (including VS Code extensions for API testing). Configure your requests and verify that the login authentication works as expected.
