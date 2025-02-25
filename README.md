# bookstore-project
An online bookstore.

# 📚 Bookstore Project

## 🚀 Overview
This is a full-fledged **online bookstore** that also integrates with a **physical store**. Users can:
- **Browse & search for books**
- **Purchase physical books & e-books/audiobooks**
- **Leave reviews and ratings**
- **Add items to cart and checkout**
- **Make secure payments via Paystack**
- **Sync inventory with the physical store**

## 🏗️ Tech Stack
### **Frontend (Next.js) 📌**
- React.js (Next.js)
- TailwindCSS
- Axios (API requests)
- Paystack SDK (Payments)

### **Backend (Node.js + Express) 🔧**
- Express.js (API framework)
- MongoDB (Mongoose ORM)
- JWT (Authentication)
- Paystack API (Payment processing)
- Multer (File uploads)

### **Database 🛢️**
- MongoDB (Book & user data)
- Firebase Storage (E-books & audiobooks storage)

## 🔧 Setup Instructions
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-username/bookstore-project.git
cd bookstore-project
```

### **2️⃣ Backend Setup**
```sh
cd backend
npm install
cp .env.example .env  # Configure your environment variables
npm start
```

### **3️⃣ Frontend Setup**
```sh
cd ../frontend
npm install
cp .env.local.example .env.local  # Configure API URLs
npm run dev
```

## 🎯 Features
✅ **Book Search & Filtering**
✅ **User Authentication (JWT)**
✅ **Shopping Cart & Orders**
✅ **Digital Book Downloads (E-books, Audiobooks)**
✅ **Physical Store Integration with POS**
✅ **Payments via Paystack**

## 📦 Folder Structure
```
📦 bookstore-project
 ┣ 📂 backend
 ┃ ┣ 📂 controllers (Auth, Books, Orders)
 ┃ ┣ 📂 models (User.js, Book.js, Order.js)
 ┃ ┣ 📂 routes (authRoutes.js, bookRoutes.js, orderRoutes.js)
 ┃ ┣ 📂 config (db.js)
 ┃ ┣ 📂 middleware (authMiddleware.js)
 ┃ ┣ 📜 server.js
 ┃ ┣ 📜 .env
 ┃ ┗ 📜 package.json
 ┣ 📂 frontend
 ┃ ┣ 📂 components (Navbar, Footer, BookCard, PayButton)
 ┃ ┣ 📂 pages (index.js, book/[id].js, cart.js, checkout.js, login.js, register.js)
 ┃ ┣ 📜 .env.local
 ┃ ┣ 📜 tailwind.config.js
 ┃ ┗ 📜 package.json
 ┣ 📜 .gitignore
 ┣ 📜 README.md
 ┗ 📜 LICENSE
```

## 🚀 Deployment
### **Backend**
- Host on **AWS / DigitalOcean / Railway**

### **Frontend**
- Deploy on **Vercel / Netlify**

## 🎯 To-Do List
- [ ] Implement search functionality using Algolia
- [ ] Add order tracking system
- [ ] Improve UI with animations
- [ ] Add analytics dashboard

## 🎉 Contributing
Feel free to **fork this repo** and submit PRs! 🚀

## 📄 License
This project is licensed under the **MIT License**.

