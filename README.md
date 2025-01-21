EcomEase - Your Modern E-Commerce Solution

EcomEase is a fully functional e-commerce website built using the MERN (MongoDB, Express.js, React, Node.js) stack. It is designed to provide a seamless shopping experience for users and a robust management platform for administrators.

Features

User Features

User Authentication: Secure login and registration using JWT.

Product Browsing: View detailed product descriptions, pricing, and availability.

Search and Filter: Search for products by name and filter by category or price range.

Shopping Cart: Add, update, and remove items from the cart.

Checkout: Place orders with real-time order confirmation.

Admin Features

Dashboard: Overview of sales, users, and product inventory.

Product Management: Add, edit, and delete products.

Order Management: View and update order statuses.

User Management: Manage registered users and their access levels.

Tech Stack

Frontend: React.js with Redux for state management, Axios for API calls, and Tailwind CSS for responsive UI design.

Backend: Node.js and Express.js for server-side logic and APIs.

Database: MongoDB for storing product, user, and order data.

Authentication: JWT (JSON Web Tokens) for secure user sessions.

Installation and Setup

Prerequisites

Node.js (v16 or later)

MongoDB (local or cloud instance)

Steps

Clone the repository:

git clone https://github.com/yourusername/EcomEase.git
cd EcomEase

Install dependencies:

For the backend:

cd backend
npm install

For the frontend:

cd ../frontend
npm install

Set up environment variables:

Create a .env file in the backend directory and configure the following:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000

Run the application:

Start the backend server:

cd backend
npm start

Start the frontend:

cd ../frontend
npm start

Open your browser and navigate to http://localhost:3000 to view the application.

Folder Structure

EcomEase/
|-- backend/
|   |-- controllers/
|   |-- models/
|   |-- routes/
|   |-- server.js
|-- frontend/
|   |-- src/
|       |-- components/
|       |-- pages/
|       |-- App.js
|-- README.md

Contributions

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

Thanks to the MERN stack community for their tutorials and resources.

Inspiration for EcomEase came from popular e-commerce platforms like Amazon and Flipkart.


 
