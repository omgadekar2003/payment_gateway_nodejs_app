**Node.js + Razorpay Payment Gateway Demo** project:


# 💳 Razorpay Payment Gateway Integration (Node.js)

This project demonstrates how to integrate the Razorpay Payment Gateway with a Node.js backend. It allows users to make test payments using Razorpay's Test Mode.

---

## 🚀 Features

- Razorpay Checkout Integration
- Node.js + Express server
- Simple frontend for payment
- Handles success and failure events
- Supports UPI, card, wallet (test mode)

---

## 🧰 Tech Stack

- Backend: Node.js, Express
- Frontend: HTML + Razorpay Checkout Script
- Payment: Razorpay (Test Key)

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repo

bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


### 2️⃣ Install Dependencies

bash
npm install


### 3️⃣ Add Razorpay Keys

Create a `.env` file in the root folder:

env
RAZORPAY_KEY_ID=rzp_test_yourkeyid
RAZORPAY_KEY_SECRET=yourkeysecret


> 💡 Get your keys from [https://dashboard.razorpay.com](https://dashboard.razorpay.com)

### 4️⃣ Run the App

bash
node app.js


The server will run on:


http://localhost:3000


---

## 🧪 Testing Payments

Use the following test UPI IDs in Razorpay checkout:

| UPI ID              | Description       |
|---------------------|-------------------|
| `success@razorpay`  | Successful Payment |
| `failure@razorpay`  | Failed Payment     |
| `pending@razorpay`  | Pending Payment    |

---
## 📂 Project Structure


.
├── app.js
├── index.html
├── success.html    
├── public/
├── .env
└── README.md


---

## 📬 Contact

For questions or feedback, reach out at omgadekar25@gmail.com

---

## ⭐️ Show Some Love

If this helped you, give it a ⭐ on GitHub and share! 💙


---

