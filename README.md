# Book-Heaven

DEMO LINK - https://stunning-marzipan-9c35d2.netlify.app

Book-Heaven is a full-stack e-commerce platform for book enthusiasts. It provides a user-friendly interface for customers to browse, purchase, and manage their book orders, while also offering an admin dashboard for inventory and order management.

## Features

### User Dashboard
- User Authentication:
  - Sign up for a new account
  - Log in to existing account
- Book Management:
  - Browse for books
  - Add books to favorites
  - Add books to cart
- Order Processing:
  - Place orders
  - View order status
  - Access order history
- User Profile:
  - Update personal details

### Admin Dashboard
- Inventory Management:
  - Add new books to the inventory
  - Update existing book details
  - Delete books from the inventory
- Order Management:
  - View all placed orders
  - Update order status

## Technologies Used

- Frontend:
  - React.js
  - Tailwind CSS
- Backend:
  - Node.js
  - Express.js
- Database:
  - MongoDB
- Authentication:
  - JSON Web Tokens (JWT)

## Future Enhancements

- Payment Integration:
- Implement Stripe payment gateway for secure transactions
- User Experience:
- Develop a recommendation system based on user preferences and purchase history
- Add a review and rating system for books

## Setup Instructions

1. Clone the repository
```
git clone https://github.com/Shivang-Rajouria/book-heaven.git
cd book-heaven

```

2. Install dependencies
- For backend:
  ```
  cd backend
  npm install
  ```
- For frontend:
  ```
  cd ../frontend
  npm install
  ```

3. Set up environment variables
- Create a `.env` file in the backend directory
- Add the following variables:
  ```
  MONGODB_URI=your_mongodb_connection_string
  ```

4. Run the application
- Start the backend server:
  ```
  cd backend
  npm start
  ```
- In a new terminal, start the frontend:
  ```
  cd frontend
  npm start
  ```

5. Open your browser and navigate to `http://localhost:5173`


## Contributing

We welcome contributions to Book-Heaven! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for details on how to get started.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
