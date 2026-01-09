## 🚀 Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/ecommerce-backend.git
cd ecommerce-backend
Create Virtual Environment
python -m venv venv


Activate the virtual environment:

Linux / Mac

source venv/bin/activate


Windows

venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Apply Migrations
python manage.py makemigrations
python manage.py migrate

5️⃣ Create Superuser
python manage.py createsuperuser

6️⃣ Run the Development Server
python manage.py runserver
# 🛒 E-Commerce Backend Project (Django)

This repository contains the backend implementation of an **E-commerce application** built using **Django** and **Django REST Framework (DRF)**.  
The project is designed for learning, practice, and real-world backend development use cases.

Anyone is **free to clone, copy, and use** this project.

---

## 📌 Project Objective

The goal of this project is to build a **scalable and secure backend** for an e-commerce platform that supports:
- User management
- Product handling
- Orders and cart functionality
- RESTful APIs for frontend/mobile integration

---

## 🚀 Features

- User Registration & Login
- Authentication & Authorization
- Product CRUD Operations
- Category Management
- Cart Management
- Order Placement
- Django Admin Panel
- REST APIs using DRF
- Secure and modular project structure

---

## 🛠️ Tech Stack

- **Backend Framework:** Django
- **API Framework:** Django REST Framework (DRF)
- **Language:** Python
- **Database:** SQLite (default)
- **Tools:** Git, GitHub, Postman
- **Authentication:** Django Auth / JWT (optional)

---

## 📂 Project Structure

```bash
ecommerce-backend/
│
├── ecommerce/        # Project settings
├── users/            # User authentication & profiles
├── products/         # Products & categories
├── orders/           # Orders & cart
├── manage.py
├── requirements.txt
└── README.md



MIT License

Copyright (c) 2026 Bablu Kumar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

