
# **Kisaan Mitra  🌾**  
**Revolutionizing Agri-Living with Technology**
<img src="https://yt3.googleusercontent.com/ytc/AIdro_mVURs1Yt7dHx6sXFvEO386tIsqgNt5N0_GHt4aEfSKNQ=s900-c-k-c0x00ffffff-no-rj" alt="Kisaan Mitra " width="600" height="300">

---

## **Overview**

Kisaan Mitra  is a comprehensive **Agricultural Management Web Application** developed as part of a university project. Built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**, this application aims to bridge the gap between farmers, sellers, and consumers by providing an intuitive and feature-rich platform.  

**Key Features:**
- **Interactive ChatBot** for user assistance
- Comprehensive **Seller & Farmer Profiles**
- **Product Management**: Add/Delete/Edit Products, Grains
- **Consumer Features**: Shopping Cart, Product Purchase, PayPal Integration
- **Address Management**: Add/Edit Personal & Company Addresses
- **Loan & Credit Card Services** for Farmers

---

## **Getting Started**

### **Prerequisites**

To get started with Kisaan Mitra , ensure you have Node.js version 14.6+ installed. If not, add the `--experimental-modules` flag to support ES Modules.

### **Environment Variables**

Create a `.env` file in the root directory and add the following:
```bash
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=abc123
PAYPAL_CLIENT_ID=your_paypal_client_id
```

For the frontend, create a `.env` file with:
```bash
REACT_APP_GOOGLE_KEY=your_google_map_api_key
```

---

## **Installation**

Follow these steps to install dependencies for both the frontend and backend:

```bash
# Install backend dependencies
npm install

# Navigate to the frontend directory
cd frontend

# Install frontend dependencies
npm install
```

---

## **Running the Application**

### **Development Mode**
To run both the frontend and backend servers simultaneously:
```bash
npm run dev
```
To run only the backend server:
```bash
npm run server
```

### **Production Build**
Create a production build for the frontend:
```bash
cd frontend
npm run build
```

---

## **Database Seeding**

You can seed the database with sample users and products using the following commands:

```bash
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

---

