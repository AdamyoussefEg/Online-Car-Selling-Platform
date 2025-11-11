# 🚗 AutoMart — Online Car Selling Platform

A Django-based full-stack web application for selling cars online.  
Users can browse, view, and purchase cars.  
⚠️ Note: The payment system is **not functional yet** — clicking the payment button only refreshes the page instead of completing the process.

![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc1.png)
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
https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc1.png
### ❌ Payment system not working:
Clicking the payment button only refreshes the page instead of proceeding to a payment method or confirmation page.

###🕒 This issue will be fixed in future updates.


![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc1.png)
![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc2.png)
![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc3.png)
![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc4.png)
![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc5.png)
![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc6.png)
![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc7.png)
![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc8.png)
![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc9.png)
![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc10.png)
