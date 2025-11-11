# 🚗 AutoMart — Online Car Selling Platform

A **Django-based full-stack web application** for selling cars online.  
Users can browse, view, and purchase cars.  

⚠️ **Note:** The payment system is *not functional yet* — clicking the payment button only refreshes the page instead of completing the process.

![AutoMart Preview](https://raw.githubusercontent.com/AdamyoussefEg/Online-Car-Selling-Platform/main/src/project/app_images/sc1.png)

---
https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc1.png
![AutoMart Preview](https://github.com/AdamyoussefEg/Online-Car-Selling-Platform/blob/main/src/project/app_images/sc1.png)

## 🏁 Overview

**AutoMart** simulates an online car marketplace where users can:
- View available cars  
- Explore detailed specifications  
- Add cars to the cart and proceed to checkout  

Most site features are functional, but the **payment integration** will be added in future updates.

---

## 🛠️ Features

- 🏎️ Browse and search cars by brand, model, and price  
- 📄 View detailed car descriptions and specifications  
- 🛒 Add cars to the cart and go to checkout  
- 🔐 User registration and login  
- ⚠️ Payment page exists but is not functional yet
- 
![AutoMart Preview](https://raw.githubusercontent.com/AdamyoussefEg/Online-Car-Selling-Platform/main/src/project/app_images/sc2.png)
![AutoMart Preview](https://raw.githubusercontent.com/AdamyoussefEg/Online-Car-Selling-Platform/main/src/project/app_images/sc3.png)
![AutoMart Preview](https://raw.githubusercontent.com/AdamyoussefEg/Online-Car-Selling-Platform/main/src/project/app_images/sc4.png)
![AutoMart Preview](https://raw.githubusercontent.com/AdamyoussefEg/Online-Car-Selling-Platform/main/src/project/app_images/sc5.png)
![AutoMart Preview](https://raw.githubusercontent.com/AdamyoussefEg/Online-Car-Selling-Platform/main/src/project/app_images/sc6.png)
![AutoMart Preview](https://raw.githubusercontent.com/AdamyoussefEg/Online-Car-Selling-Platform/main/src/project/app_images/sc7.png)
![AutoMart Preview](https://raw.githubusercontent.com/AdamyoussefEg/Online-Car-Selling-Platform/main/src/project/app_images/sc8.png)
![AutoMart Preview](https://raw.githubusercontent.com/AdamyoussefEg/Online-Car-Selling-Platform/main/src/project/app_images/sc9.png)
![AutoMart Preview](https://raw.githubusercontent.com/AdamyoussefEg/Online-Car-Selling-Platform/main/src/project/app_images/sc10.png)

---

## ⚙️ Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend** | Django, Django REST Framework |
| **Frontend** | HTML, CSS, JavaScript |
| **Database** | SQLite |
| **Authentication** | Django Built-in Auth System |

---

## 💻 Installation Guide

Follow these steps to set up and run the project locally:

### 1️⃣ Clone the repository
```bash
git clone https://github.com/AdamyoussefEg/Online-Car-Selling-Platform.git
cd Online-Car-Selling-Platform

### 2️⃣ Create a virtual environment
python -m venv venv
# On macOS/Linux
source venv/bin/activate
# On Windows
venv\Scripts\activate

### 3️⃣ Install dependencies
pip install -r requirements.txt

### 4️⃣ Apply database migrations
python manage.py makemigrations
python manage.py migrate

### 5️⃣ Run the development server
python manage.py runserver


###Then open your browser and visit:

http://127.0.0.1:8000/

---

###🚧 Known Issues

### ❌ Payment system not functional yet:
### Clicking the payment button only refreshes the page instead of proceeding to a payment method or confirmation page.
### 🕒 This issue will be fixed in future updates.

