# 🛍️ Amazon Clone

A full-stack e-commerce web application that replicates the core functionalities of Amazon. This project demonstrates proficiency in building scalable, user-friendly e-commerce platforms with modern web technologies.

## 📋 Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## ✨ Features

- **User Authentication**
  - User registration and login
  - Secure password management
  - User profile management

- **Product Catalog**
  - Browse products with detailed descriptions
  - Search and filter products by category
  - Product ratings and reviews

- **Shopping Cart**
  - Add/remove items from cart
  - Update product quantities
  - Persistent cart storage

- **Checkout & Payment**
  - Secure checkout process
  - Payment gateway integration
  - Order confirmation

- **Order Management**
  - View order history
  - Track order status
  - Download invoices

- **Admin Dashboard** (Optional)
  - Manage products
  - View sales analytics
  - Manage user accounts

## 🛠️ Tech Stack

### Frontend
- **React** - UI library
- **Redux** - State management
- **React Router** - Routing
- **Axios** - HTTP client
- **Tailwind CSS / Material-UI** - Styling

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - ODM for MongoDB
- **JWT** - Authentication

### Additional Tools
- **Stripe/PayPal** - Payment processing
- **Firebase** - Optional: Authentication & Storage
- **Docker** - Containerization (optional)

## 🚀 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local or cloud instance)
- Git

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/bhushanpatil876/Amazon-clone.git
   cd Amazon-clone
   ```

2. **Install backend dependencies:**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies:**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Create environment variables:**
   
   Create `.env` file in the `backend` directory:
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   STRIPE_API_KEY=your_stripe_api_key
   PORT=5000
   ```

   Create `.env.local` file in the `frontend` directory:
   ```
   REACT_APP_API_URL=http://localhost:5000
   REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key
   ```

5. **Start the backend server:**
   ```bash
   cd backend
   npm start
   ```

6. **Start the frontend development server:**
   ```bash
   cd frontend
   npm start
   ```

7. **Access the application:**
   Open your browser and navigate to `http://localhost:3000`

## 💻 Usage

1. **Sign Up:** Create a new account with email and password
2. **Browse Products:** Explore the product catalog and use filters
3. **Add to Cart:** Click "Add to Cart" on any product
4. **Checkout:** Proceed to checkout and enter shipping/payment details
5. **Complete Order:** Review and confirm your order
6. **Track Order:** View your order history and status

## 📁 Project Structure

```
Amazon-clone/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── styles/
│   │   └── App.js
│   └── package.json
├── backend/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   ├── middleware/
│   ├── server.js
│   └── package.json
└── README.md
```

## 📸 Screenshots

Add screenshots of your application here:

```
![Homepage](./screenshots/homepage.png)
![Product Page](./screenshots/product-page.png)
![Shopping Cart](./screenshots/cart.png)
![Checkout](./screenshots/checkout.png)
```

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

**Bhushan Patil**
- GitHub: [@bhushanpatil876](https://github.com/bhushanpatil876)
- Email: [your-email@example.com](mailto:your-email@example.com)
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)

---

## 🙏 Acknowledgments

- [React Documentation](https://reactjs.org/)
- [Node.js Documentation](https://nodejs.org/)
- [MongoDB Documentation](https://docs.mongodb.com/)
- [Express.js Guide](https://expressjs.com/)

---

**⭐ If you found this project helpful, please consider giving it a star!**
