# Food Order App

## Features
- User authentication (login, register, profile management)
- Restaurant and menu browsing
- Cart functionality
- Order management (view orders, order details)
- Responsive design

## Technologies Used
- **Frontend**: React, Redux, React Router
- **Styling**: CSS
- **State Management**: Redux, Redux Thunk
- **Alert Notifications**: react-alert
- **Dev Tools**: Redux DevTools

## Installation
1. Clone the repository
2. Navigate to the project directory
3. Install dependencies:
```bash
npm install
```
4. Start the development server:
```bash
npm start
```

## Usage
Open your browser and navigate to http://localhost:3000.
You can create an account or log in if you already have one.
Browse through restaurants, add items to your cart, and place orders.

## API Endpoints
#### User Authentication
- POST /users/login - Log in a user
- POST /users/signup - Register a new user
- GET /users/me - Get user profile
- PUT /users/me/update - Update user profile
#### Menu and Orders
- GET /eats/stores/:id/menus - Get menus for a restaurant
- POST /cart - Add items to cart
- GET /eats/orders/me/myOrders - Get user orders


Feel free to customize any part of it to better suit your project!
