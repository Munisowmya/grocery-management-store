# grocery-management-store
A full-stack web application for managing grocery store inventory, orders, and user accounts — powered by a **Flask** backend and a **Bootstrap** frontend.

## ✨ Features

- 🔐 **User Authentication**  
  - Secure user registration and login  
  - Session management  

- 📦 **Inventory Management**  
  - View all products with details  
  - Add new products to inventory  
  - Remove products from system  

- 📋 **Order Processing**  
  - Create new orders  
  - View all order history  

- ⚖️ **Unit of Measure Management**  
  - Manage different measurement units for products  

- 📱 **Responsive Design**  
  - Fully responsive and mobile-friendly  

- 🔄 **REST API Support**  
  - Complete CRUD operations via REST endpoints  

---

## 🛠️ Technologies Used

### 🔧 Backend
- 🐍 Python Flask  
- 🐬 MySQL  
- 🔄 Flask-CORS  
- 🔐 python-dotenv  

### 🎨 Frontend
- 🌐 HTML5  
- 🎨 CSS3  
- 💠 Bootstrap 5  
- ⚙️ JavaScript  
- 💡 jQuery  

### 🗄️ Database
- 🐬 MySQL  

## API Endpoints

| Method | Endpoint               | Description                          |
|--------|------------------------|--------------------------------------|
| POST   | /register              | Register new user                    |
| POST   | /login                 | User login                           |
| GET    | /getUOM                | Get all units of measure             |
| GET    | /getProducts           | Get all products                     |
| POST   | /insertProduct         | Add new product                      |
| POST   | /deleteProduct         | Remove product                       |
| GET    | /getAllOrders          | Get all orders                       |
| POST   | /insertOrder           | Create new order                     |
