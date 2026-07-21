# 🛒 Buyora

A modern **MERN Stack E-commerce Application** that allows users to browse products, manage their shopping cart, place orders, and securely authenticate. Buyora is designed with scalability, performance, and a responsive user experience in mind.

---

## 🚀 Features

### 👤 User Features
- User Registration & Login
- JWT Authentication & Authorization
- Secure Password Hashing using Bcrypt
- Browse Products
- Product Search & Filtering
- Add to Cart
- Update Cart Quantity
- Remove Items from Cart
- Wishlist Management
- Place Orders
- View Order History
- User Profile Management

### 🛍️ Admin Features
- Admin Authentication
- Dashboard Overview
- Product Management (CRUD)
- Category Management
- Order Management
- User Management
- Image Upload for Products

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit
- React Router DOM
- Axios
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt.js
- Multer

### Database
- MongoDB Atlas

### Development Tools
- Git
- GitHub
- Postman
- VS Code

---

# 📁 Project Structure

```
Buyora/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── uploads/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── context/
│   │   ├── admin/
│   │   └── App.jsx
│   └── package.json
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/buyora.git
```

```
cd buyora
```

---

## Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLIENT_URL=http://localhost:5173
```

Start Backend

```bash
npm run dev
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

# 🔐 Authentication

Buyora uses **JWT (JSON Web Token)** authentication.

- Register User
- Login User
- Protected Routes
- Admin Authorization
- Password Encryption using Bcrypt

---

# 📦 API Modules

- Authentication API
- User API
- Product API
- Category API
- Cart API
- Wishlist API
- Order API
- Admin API

---

# 📸 Screens

- Home Page
- Product Listing
- Product Details
- Shopping Cart
- Wishlist
- Checkout
- Login
- Register
- Admin Dashboard

---

# 📈 Future Improvements

- Razorpay / Stripe Payment Integration
- Product Reviews & Ratings
- Email Verification
- Forgot Password
- Order Tracking
- Coupon System
- Dark Mode
- Notifications
- Sales Analytics Dashboard

---

# 🧠 Challenges Faced

During the development of Buyora, several real-world challenges were encountered:

- Implementing secure JWT authentication.
- Managing Redux state after page refresh.
- Connecting React frontend with Node.js backend.
- Designing MongoDB relationships between users, products, and orders.
- Handling image uploads efficiently.
- Implementing proper error handling and API validation.
- Optimizing product fetching using pagination and filtering.

---

# 📚 What I Learned

Through this project, I gained hands-on experience in:

- Building scalable REST APIs
- MERN Stack Architecture
- MongoDB Data Modeling
- JWT Authentication & Authorization
- Redux Toolkit State Management
- API Integration
- File Upload Handling
- Error Handling
- Git & GitHub Workflow
- Debugging Real-world Applications

---

# 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository and submit pull requests.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Developer

**Jenil Kachhadiya**

### MERN Stack Developer

- React.js
- Node.js
- Express.js
- MongoDB
- JavaScript
- TypeScript

---

⭐ If you like this project, don't forget to give it a Star on GitHub!