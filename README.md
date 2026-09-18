# 🍔 Chillin-Bites

A full-stack **food delivery web application** built using the **MERN stack** — MongoDB, Express.js, React.js, and Node.js.

Chillin-Bites allows users to browse local restaurants, explore food items, place orders, and track deliveries. The application also provides functionality for restaurant management and delivery coordination.

---

## 🚀 Features

* 👤 User-friendly food ordering experience
* 🍽️ Browse local restaurants and food items
* 🛒 Add food items and place orders
* 📦 Order and delivery tracking
* 🏪 Restaurant management
* 🚴 Delivery personnel coordination
* ⚡ Responsive React-based frontend
* 🔗 REST API-based backend
* 🗄️ MongoDB database integration

---

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Vite

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB

### Tools

* Git
* GitHub
* npm

---

## 🏗️ Architecture

```text
                    Chillin-Bites
                         │
          ┌──────────────┴──────────────┐
          │                             │
       Frontend                      Backend
          │                             │
       React.js                    Node.js
          │                             │
        Vite                       Express.js
          │                             │
          └──────────────┬──────────────┘
                         │
                    REST APIs
                         │
                         ▼
                      MongoDB
```

---

## 🔄 Application Flow

```text
User
 │
 ▼
React Frontend
 │
 │ HTTP Request
 ▼
Express / Node.js Backend
 │
 ▼
REST API
 │
 ▼
MongoDB
 │
 ▼
Response
 │
 ▼
React UI
```

For an order:

```text
User selects food
       │
       ▼
Add to cart
       │
       ▼
Place order
       │
       ▼
Backend API
       │
       ▼
MongoDB
       │
       ▼
Order created
       │
       ▼
Delivery tracking
```

---

## 📂 Project Structure

```text
Chillin-Bites/
│
├── App.jsx
├── main.jsx
├── App.css
├── index.css
├── index.html
│
├── server.js
├── package.json
├── package-lock.json
├── vite.config.js
├── eslint.config.js
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Anurag017pratap/Chillin-Bites.git
```

### 2. Navigate into the project

```bash
cd Chillin-Bites
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the project root and add the required environment variables.

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

> Add any additional environment variables required by your local configuration.

### 5. Start the application

```bash
npm run dev
```

The application should then be available at the local URL shown by Vite.

---

## 🧑‍💻 What I Learned

Building Chillin-Bites helped me strengthen my understanding of:

* Full-stack MERN application development
* Building and consuming REST APIs
* Connecting a Node.js/Express backend with MongoDB
* React component-based development
* Client-server communication
* Database-driven application design
* Git and GitHub workflow

---

## 🔮 Future Improvements

* 🔐 Authentication and role-based authorization
* 💳 Online payment integration
* 📍 Location-based restaurant discovery
* 🔔 Real-time order notifications
* 📊 Restaurant analytics dashboard
* 🚚 Improved delivery tracking
* 🧪 Automated testing
* ☁️ Cloud deployment and CI/CD

---

## 👨‍💻 Author

**Anurag Pratap**

* GitHub: [@Anurag017pratap](https://github.com/Anurag017pratap)

---

⭐ If you find this project useful, feel free to star the repository!
