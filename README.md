# 🚀 Laravel + Vue.js E-Commerce Platform

A complete full-stack E-Commerce web application built with **Laravel**, **Vue.js**, and **MySQL**.  
This project includes a fully functional **Frontend Storefront**, **Admin Panel**, **Product Management**, **Cart**, **Checkout Flow**, and **Authentication**.

This repository is a **custom improved version** of the open-source project by TheCodeholic, with modifications, cleanup, enhanced documentation, and UI improvements.
 

---

## ✨ Features

### 🛒 User Features
- User authentication (Login/Register)
- Product listings with pagination
- Product details with dynamic images
- Add to cart
- Cart item update/delete
- Checkout page
- Order summary + confirmation page
- Responsive frontend built with Vue.js & TailwindCSS

### 🛠 Admin Features
- Admin login
- Add/Edit/Delete Products
- Add/Edit/Delete Categories
- Image upload for products
- Product inventory & stock control
- Simple dashboard

### 🔧 Technical Features
- Laravel 10 API Backend
- Vue.js 3 SPA frontend
- TailwindCSS styling
- REST API communication
- MySQL database
- Authentication via Laravel Sanctum
- Clean folder architecture
- Reusable API services (Axios)

---

## 🧰 Tech Stack

**Backend:**  
- PHP 8+  
- Laravel 10  
- MySQL  
- Laravel Sanctum  
- Laravel Eloquent ORM  

**Frontend:**  
- Vue.js 3  
- Vue Router  
- TailwindCSS  
- Axios  
- Composition API  

**Tools:**  
- Vite  
- NPM  
- Composer  

---

## 🛠 Installation & Setup

BACKEND SETUP (Laravel)

1️⃣ Clone the repository

2️⃣ Install dependencies
composer install

3️⃣ Create environment file
cp .env.example .env

4️⃣ Generate application key
php artisan key:generate

5️⃣ Configure database
Update .env with your MySQL credentials:
DB_DATABASE=laravel_vue_ecommerce
DB_USERNAME=root
DB_PASSWORD=

6️⃣ Run migrations & seeders
php artisan migrate --seed

7️⃣ Start backend server
php artisan serve

Backend runs at:
http://localhost:8000


FRONTEND SETUP (Vue.js)

8️⃣ Go to frontend folder
cd frontend

9️⃣ Install dependencies
npm install

🔟 Start frontend dev server
npm run dev

Frontend runs at:
👉 http://localhost:5173


🔑 Default Login Credentials (Seeded)

🧑 User
email: user@example.com
password: password

👨‍💼 Admin
email: admin@example.com
password: password


📁 Project Folder Structure

/backend
    /app
    /routes
    /database
    /resources
/frontend
    /src
    /components
    /views
    /store


🎯 Improvements I Made
-> Added better UI components
-> Added form validations
-> Added error handling
-> Updated categories UI
-> Cleaned unused code
-> Fixed minor bugs

📝 License
This project is open-source and distributed under the MIT License.





