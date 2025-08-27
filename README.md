# Recipe Book API

A backend API for a recipe sharing application, allowing users to create, share, and discover new recipes. This project is built with Node.js, Express, and MongoDB.

## Features

  User Authentication: Secure user registration and login using JSON Web Tokens (JWT).
  
  CRUD Operations: Users can Create, Read, Update, and Delete their own recipes.
  
  Recipe Discovery: Search for recipes by title or ingredients.
  
  Social Interaction: Rate and comment on recipes.

## Technology Stack

  Backend: Node.js, Express.js
  
  Database: MongoDB with Mongoose
  
  Authentication: JWT, bcrypt.js

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have the following installed on your machine:

  * [Node.js](https://nodejs.org/en/)
  * [MongoDB](https://www.mongodb.com/try/download/community)
  * An API client like [Postman](https://www.postman.com/) or [Thunder Client](https://www.thunderclient.com/) for testing.

### Installation & Setup

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/MayureshRajesh/Backend-TestRecipe.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd Backend-TestRecipe
    ```

3.  **Install NPM packages:**

    ```bash
    npm install
    ```

4.  **Create a `.env` file** in the root of the project. This file will hold your secret environment variables. Add the following, replacing the placeholder values with your own:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_super_secret_key
    PORT=5000
    ```

5.  **Start the server:**

    ```bash
    npm start
    ```

ENDPOINTS: 

<img width="857" height="231" alt="Screenshot 2025-08-27 113200" src="https://github.com/user-attachments/assets/6192314e-8330-4223-a699-2dfa031eb2e1" />

