#Simply-Sell : Refurbished Goods Marketplace App - MERN Stack


Interface -
![Screenshot 2023-08-05 at 12 42 14 PM](https://github.com/krishanjit19/simply_sell/assets/84830284/d5ca59bc-be61-49bf-8691-202be4e1ad9c)

User Registation in the Backend
![Screenshot 2023-08-05 at 12 42 57 PM](https://github.com/krishanjit19/simply_sell/assets/84830284/55b39147-90ae-4e96-8d8e-7c263430e4e6)



Welcome to the Refurbished Goods Marketplace App! This is a full-stack web application built using the MERN (MongoDB, Express, React, Node.js) stack along with Redux Toolkit for state management. The app allows users to buy and sell refurbished goods, creating a platform for environmentally-conscious shopping for college student.

## Table of Contents


- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and registration
- Product listings with details and images
- User profiles and seller stores
- Search and filtering options
- Real-time notifications
- Admin panel for managing products and users
- Responsive design for various devices

## Installation

Follow these steps to set up and run the application locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/refurbished-marketplace.git
   cd refurbished-marketplace
   ```

2. Install the dependencies for both the server and client:

   ```bash
   cd server
   npm install

   cd ../client
   npm install
   ```

3. Configure environment variables:

   Rename `.env.example` in the `server` directory to `.env` and provide the necessary values, such as database connection URL, JWT secret, etc.

4. Seed the database (optional):

   If you want to populate the database with sample data, you can run the following command:

   ```bash
   cd server
   npm run seed
   ```

5. Start the development server:

   ```bash
   cd ../server
   npm start
   ```

   Open a new terminal window/tab:

   ```bash
   cd ../client
   npm start
   ```

6. Access the application in your web browser at `http://localhost:3000`.

## Usage

- Register a new account or log in if you already have an account.
- Browse through the product listings, view product details, and add items to your cart.
- Proceed to the checkout, where you can enter your payment details.
- Sellers can create their own stores, add products, and manage their inventory.
- Admin users can access the admin panel to manage users, products, and orders.

## Technologies

- Frontend: React, Redux Toolkit, HTML5, CSS3
- Backend: Node.js, Express.js, MongoDB
- Authentication: JSON Web Tokens (JWT)
- Payment Gateway: Stripe
- Real-time Updates: Socket.io
- Deployment: Heroku (backend), Vercel (frontend)

## Contributing

Contributions are welcome! If you find any bugs or want to add new features, please open an issue or submit a pull request. Make sure to follow the existing code style and guidelines.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-feature`.
3. Commit your changes: `git commit -m 'Add a new feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Open a pull request.
