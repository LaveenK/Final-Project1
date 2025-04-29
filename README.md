
# 🍔 Foodeli – Food Order & Delivery App

**Foodeli** is a full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to explore restaurants, browse food menus, place online orders, and track them in real-time. This project replicates core features of popular food delivery apps like Swiggy and Zomato on a simplified scale, ideal for educational and demonstration purposes.

---

## 🚀 Live Demo

> 🔗 [https://foodeli-client.vercel.app](#)  
> 🔗 [https://foodeli-api.onrender.com](#)

---

## 📸 Screenshots

![Home Page](https://raw.githubusercontent.com/LaveenK/Final-Project1/main/website_screenshots/img1.jpg)
![Menu Page](https://raw.githubusercontent.com/LaveenK/Final-Project1/main/website_screenshots/img2.jpg)
![Cart](https://raw.githubusercontent.com/LaveenK/Final-Project1/main/website_screenshots/img3.jpg)
![Checkout](https://raw.githubusercontent.com/LaveenK/Final-Project1/main/website_screenshots/img4.jpg)
![Login Page](https://raw.githubusercontent.com/LaveenK/Final-Project1/main/website_screenshots/img5.jpg)
![Admin Dashboard](https://raw.githubusercontent.com/LaveenK/Final-Project1/main/website_screenshots/img6.jpg)
![Add Item](https://raw.githubusercontent.com/LaveenK/Final-Project1/main/website_screenshots/img7.jpg)
![Order Tracking](https://raw.githubusercontent.com/LaveenK/Final-Project1/main/website_screenshots/img8.jpg)
![Order History](https://raw.githubusercontent.com/LaveenK/Final-Project1/main/website_screenshots/img9.jpg)

---

## 🛠️ Tech Stack

**Frontend**:  
- React.js    

**Backend**:  
- Node.js  
- Express.js  
- MongoDB with Mongoose  
- JWT for authentication  

**Other Tools that can be used for deployment**:  
- Render (Backend Deployment)  
- Vercel / Netlify (Frontend Deployment)  
- MongoDB Atlas (Cloud Database)

---

## ✨ Features

### 👥 User
- User registration & login (JWT auth)
- Browse restaurants & their menus
- Add items to cart
- Place orders & view order history
- Track order status

### 🛒 Admin
- Add/Edit/Delete Restaurants & Menu Items
- View & manage user orders
- Track sales metrics

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/LaveenK/Final-Project1.git
cd Final-Project1
```

---

### 2. Backend Setup

```bash
cd server
npm install
```

Create a `.env` file in `/server` directory with the following:

```env
MONGO_URI=your_mongo_db_uri
JWT_SECRET=your_jwt_secret
PORT=5000
```

Start backend:
```bash
npm run start
```

---

### 3. Frontend Setup

```bash
cd ../client
npm install
npm start
```

---

## 🌍 Deployment

- **Frontend**: Deploy `/client` folder using [Vercel](https://vercel.com) or [Netlify](https://www.netlify.com)
- **Backend**: Deploy `/server` folder using [Render](https://render.com) or [Railway](https://railway.app)
- **Database**: Use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for cloud-hosted MongoDB

---

## 🧠 Future Improvements

- Payment integration (Razorpay / Stripe)
- Rating & reviews system
- Real-time delivery tracking with WebSockets
- Admin analytics dashboard

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.

---


## 💬 Contact

Built with ❤️ by [Laveen Kewlani](https://github.com/LaveenK)  
📧 Email: laveenkewlani2004@gmail.com  
