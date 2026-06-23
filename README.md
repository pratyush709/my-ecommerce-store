<div align="center">
  <h1>🛍️ MERN E-Commerce Platform</h1>
  <p>A full-stack, feature-rich e-commerce store built with the MERN stack, TypeScript, and Tailwind CSS.</p>

  <p>
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
    <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node" />
    <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" alt="Express" />
    <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  </p>
</div>

---

## 📖 Table of Contents

- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [💻 Environment Variables](#-environment-variables)
- [📜 License](#-license)

---

## ✨ Features

### Customer Storefront
- **Browse & Filter:** Advanced product filtering by category, brand, size, and color.
- **Authentication:** Secure user login and registration powered by Clerk.
- **Cart & Wishlist:** Seamless cart management and wishlist saving.
- **Checkout System:** Secure payments integrated with Razorpay.
- **Rewards Program:** Unique "Pay with Points" feature where returned orders translate to store credit.
- **Order Tracking & Returns:** Customers can view their order history and initiate returns within a valid time window.

### Admin Dashboard
- **Analytics Overview:** High-level metrics for total sales, products, and returned orders.
- **Product Management:** Full CRUD capabilities for products, including Cloudinary integration for multiple image uploads.
- **Category & Coupon Management:** Create and manage product categories and live promo codes (with minimum order thresholds).
- **Order Fulfillment:** Update order statuses (Placed, Shipped, Delivered) and process returns.
- **Store Settings:** Dynamic homepage banner management.

---

## 🛠️ Tech Stack

**Frontend:**
- React (via Vite)
- TypeScript
- Tailwind CSS
- Shadcn UI (Radix UI)
- Zustand (State Management)
- React Router DOM

**Backend:**
- Node.js & Express.js
- MongoDB & Mongoose
- TypeScript
- Multer & Streamifier (File Handling)

**Third-Party Services:**
- **Clerk:** Authentication & Identity Management
- **Razorpay:** Payment Gateway
- **Cloudinary:** Cloud Image Storage

---

## 🚀 Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites
- [Node.js](https://nodejs.org/) installed
- A [MongoDB](https://www.mongodb.com/) database URL
- Accounts with Clerk, Razorpay, and Cloudinary for API keys

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name