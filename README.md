# auth-api

This project is a basic Node.js authentication API built with Express.js and MongoDB (using Mongoose). It provides endpoints for user registration and login, utilizing JSON Web Tokens (JWT) for authentication and bcryptjs for password hashing. Swagger UI is integrated for API documentation.

## Prerequisites

*   Node.js (v14 or later recommended)
*   npm (usually comes with Node.js)
*   MongoDB (running locally or a connection URI)

## Setup

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd auth-api
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up environment variables:**
    *   Copy the example environment file:
        ```bash
        cp .env.example .env
        ```
    *   Edit the `.env` file and provide the necessary values:
        ```dotenv
        PORT=5000 # Or any port you prefer
        MONGO_URI=your_mongodb_connection_string
        JWT_SECRET=your_jwt_secret_key
        ```

## Running the Application

*   **Development mode (with automatic restarts):**
    ```bash
    npm run dev
    ```

*   **Production mode:**
    ```bash
    npm start
    ```

The server will start, typically on the port specified in your `.env` file (defaulting to 5000).

## API Documentation

API documentation is available via Swagger UI. Once the server is running, navigate to `/api-docs` in your browser.
