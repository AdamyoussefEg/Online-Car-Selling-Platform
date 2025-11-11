# 🚗 AutoMart — Online Car Selling Platform

A Django-based full-stack web application for selling cars online.  
Users can browse, view, and purchase cars.  
⚠️ Note: The payment system is **not functional yet** — clicking the payment button only refreshes the page instead of completing the process.

---

## 🏁 Overview

AutoMart is designed to simulate an online car marketplace.  
It allows users to view available cars, explore details, and proceed to a simulated checkout page.  
While most site features are functional, the **payment method** is not yet connected and will be completed in future updates.

---

## 🛠️ Features

- 🏎️ Browse and search cars by brand, model, and price  
- 📄 View detailed car descriptions and specifications  
- 🛒 Add items to the cart and go to checkout  
- 🔐 User registration and login  
- ⚠️ **Payment page exists but not functional yet** (refreshes instead of proceeding)  

---

## ⚙️ Tech Stack

- **Backend:** Django, Django REST Framework  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** SQLite
- **Authentication:** Django built-in auth system  

---

## 💻 Installation Guide

Follow these steps to set up and run the project on your local machine:

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YourUsername/AutoMart.git
cd AutoMart

### 2️⃣ Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt

### 4️⃣ Apply database migrations
```bash
python manage.py makemigrations
python manage.py migrate

### 5️⃣ Run the development server
```bash
python manage.py runserver


### 🚧 Known Issues

### ❌ Payment system not working:
Clicking the payment button only refreshes the page instead of proceeding to a payment method or confirmation page.

🕒 This issue will be fixed in future updates.

ْhttps://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc1.png
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5971e999-5046-463e-8a04-7779e704028e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6c6f3b28-3254-4b50-9427-cb47653d509e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/09c132e2-255d-439a-9b32-77bf6f56a9cc" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b1024a9d-fbcb-40f3-9112-90d8b4370474" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fc7a4148-5f74-43cd-9b6e-b2569cde5818" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/66e7419f-928a-4559-9f46-2dca88104d8d" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/06f24e60-aa1d-4e42-a4f7-95dec43a102a" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ef1fe98e-d2e7-4bc0-8967-d032e10a9629" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/314aeaf9-e878-4187-9eb9-4c80677731bc" />
