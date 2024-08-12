# Toy Shop Server

This is the backend server for the Toy Shop website, built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The server handles all the backend operations, including user authentication, product management, and order processing.

## Features

- **User Authentication:** Secure login and registration functionality using JWT tokens.
- **Product Management:** APIs for adding, updating, and deleting toy listings.
- **Order Management:** APIs for handling customer orders.
- **Database Integration:** Efficient data handling with MongoDB.
- **Error Handling:** Robust error handling for reliable operations.

## Technologies Used

- MongoDB
- Express.js
- Node.js
- JWT (JSON Web Tokens)

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/galibmia/toy-shop-server.git
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up environment variables:
    Create a `.env` file in the root directory and add the following:
    ```plaintext
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. Run the server:
    ```bash
    npm start
    ```

## API Endpoints

### Auth

- **POST /api/auth/register**: Register a new user
- **POST /api/auth/login**: Login a user

### Products

- **GET /api/products**: Get all products
- **POST /api/products**: Add a new product
- **PUT /api/products/:id**: Update a product
- **DELETE /api/products/:id**: Delete a product

### Orders

- **GET /api/orders**: Get all orders
- **POST /api/orders**: Place a new order

## Contributing

Feel free to explore the code and contribute to the project! Fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License.
