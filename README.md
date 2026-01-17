# 🚗 AutoMart — Online Car Selling Platform

A **Django-based full-stack web application** for selling cars online.  
Users can browse, view, and purchase cars.  

⚠️ **Note:** Add your payment code in settings and the checkout in Adnor_Marketing 

# To Test 
# U: Dimo
# P: Dimo123456

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
---


## 🏁 Overview

**AutoMart** simulates an online car marketplace where users can:
- Explore detailed specifications  
- Add cars to the cart and proceed to checkout  

Most site features are functional, but the **payment integration** will be added in future updates.

---

## 🛠️ Features

- 🏎️ Browse and search cars by brand
- 📄 View detailed car descriptions and specifications  
- 🛒 Add cars to the cart and go to checkout  
- 🔐 User registration and login  
- ⚠️ Payment page exists but is not functional yet

---

## ⚙️ Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend** | Django, Django REST Framework |
| **Frontend** | HTML, CSS, JavaScript |

---

## 💻 Installation Guide

Follow these steps to set up and run the project locally:

### 1️⃣ Clone the repository
```bash
git clone https://github.com/AdamyoussefEg/Online-Car-Selling-Platform.git
cd Online-Car-Selling-Platform

## 2️⃣ 𝗖𝗿𝗲𝗮𝘁𝗲 𝗮 𝘃𝗶𝗿𝘁𝘂𝗮𝗹 𝗲𝗻𝘃𝗶𝗿𝗼𝗻𝗺𝗲𝗻𝘁
```bash
python -m venv venv
# On macOS/Linux
source venv/bin/activate
# On Windows
venv\Scripts\activate

### 3️⃣  𝗜𝗻𝘀𝘁𝗮𝗹𝗹 𝗱𝗲𝗽𝗲𝗻𝗱𝗲𝗻𝗰𝗶𝗲𝘀
```bash
cd src\project
pip install -r requirements.txt

### 4️⃣ Apply database migrations
```bash
python manage.py makemigrations
python manage.py migrate

### 5️⃣ Run the development server
```bash
python manage.py runserver

###Then open your browser and visit:

http://127.0.0.1:8000/

---


