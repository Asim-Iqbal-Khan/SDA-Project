# 🛒 Nex Commerce - Supermarket Management System

A JavaFX-based supermarket management system developed using **FXML (Scene Builder)** for the frontend and **Java** for the backend. The application integrates with a **MySQL database** to handle real-world operations like inventory, orders, deliveries, and more. Developed as a part of a university project at FAST NUCES.

---

## 📌 Features

### 👤 User Features
- User registration and login
- Product browsing by category
- Add to cart, remove from cart
- Order checkout and tracking
- Rate delivery experience

### 🔐 Admin Features
- Manage categories, products, users, and employees
- Process and assign orders to delivery personnel
- View sales reports with filters
- Add/remove/edit product and category data

### 🚚 Delivery Boy Features
- View assigned deliveries
- Mark orders as delivered
- Get rated by customers

---

## 🧰 Tech Stack

| Layer         | Tech Used                         |
|---------------|-----------------------------------|
| **Frontend**  | JavaFX with FXML via Scene Builder |
| **Backend**   | Java                              |
| **Database**  | MySQL                             |
| **Architecture** | MVC pattern + modular components |

---


## 🗃️ Database Schema

- **Tables:**
  - `Users`
  - `Products`
  - `Categories`
  - `Orders`
  - `Cart`
  - `Wishlist`
  - `DeliveryBoy`
  - `Reviews`


---

## 🔧 Setup Instructions

### Prerequisites
- Java SE 11 or above
- MySQL Server
- Scene Builder (for editing FXML visually)
- IntelliJ IDEA / NetBeans / VS Code with JavaFX plugin

### Clone the Repo
```bash
git clone https://github.com/Asim-Iqbal-Khan/SDA-Project.git
cd SDA-Project
