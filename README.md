# 💎 SSJ – Ecommerce Jewellery Website

**Repository Name:** Ecommerce-Jewellery
**Project Name:** SSJ

SSJ is a full-stack **E-commerce Jewellery Web Application** built using **Django** and **SQL**, integrated with **Razorpay** for secure online payments. The platform allows users to browse jewellery products, request **custom-made jewellery using AI-generated images or reference images**, and interact with admins for feasibility and customization approval.

---

## 🚀 Features

### 👤 User Features

* User authentication (Register / Login / Logout)
* Browse jewellery products
* Secure online payments using **Razorpay**
* Upload reference images from the internet to request custom jewellery
* Generate jewellery images using **AI Image Generation**
* Provide **custom weight (in grams)** for jewellery requests
* Track custom jewellery requests
* Receive admin feedback on feasibility of custom designs

### 🧠 AI-Powered Custom Jewellery

* Users can generate jewellery designs using an **AI image generation model**
* Users can also upload external images as design references
* Users specify the **expected weight (grams)** of the jewellery
* Requests are sent to admin for validation and feasibility check

### 🛠️ Admin Features

* Admin dashboard to manage products and users
* View AI-generated and user-uploaded jewellery requests
* Check whether the requested jewellery is **technically makeable or not**
* Contact users regarding feasibility, pricing, or customization details
* Approve or reject custom jewellery requests

---

## 🧰 Tech Stack

| Layer          | Technology                |
| -------------- | ------------------------- |
| Backend        | Django (Python)           |
| Database       | SQL (SQLite / MySQL)      |
| Frontend       | HTML, CSS, JavaScript     |
| Payments       | Razorpay                  |
| AI Feature     | AI Image Generation Model |
| Authentication | Django Auth System        |

---

## 🏗️ Project Structure (High Level)

```
Ecommerce-Jewellery/
│── SSJ/
│   │── settings.py
│   │── urls.py
│   │── views.py
│   │── models.py
│   │── templates/
│   │── static/
│── manage.py
│── db.sqlite3
│── requirements.txt
│── README.md
```

---

## 💳 Razorpay Payment Integration

* Integrated **Razorpay Checkout** for secure payments
* Handles order creation and payment verification
* Ensures safe and reliable transaction flow

---

## 🔐 Security Highlights

* Django’s built-in authentication system
* Secure payment handling using Razorpay APIs
* Server-side validation for custom jewellery requests

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Ecommerce-Jewellery.git
cd Ecommerce-Jewellery
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Razorpay

* Create an account on **Razorpay**
* Add your `RAZORPAY_KEY_ID` and `RAZORPAY_KEY_SECRET` in Django settings

### 5️⃣ Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Start the Server

```bash
python manage.py runserver
```

---

## 🧪 Sample Use Case Flow

1. User logs in
2. Generates or uploads a jewellery image
3. Enters required weight in grams
4. Submits custom jewellery request
5. Admin reviews feasibility
6. Admin contacts user for confirmation
7. Payment is completed via Razorpay

---

## 📌 Future Enhancements

* Price estimation using AI based on weight & material
* Order tracking system
* Email & WhatsApp notifications
* Product reviews and ratings
* Deployment on cloud (AWS / Azure)

---

## 📜 License

This project is for educational and learning purposes.
