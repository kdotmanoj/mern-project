# eCommerce Platform - MERN Stack

Welcome to the eCommerce Platform, a comprehensive online shopping solution developed using the MERN Stack (MongoDB, Express.js, React, Node.js). This platform is designed to offer a smooth and feature-rich shopping experience with a robust admin panel for managing products, users, and orders.

## Key Features

* **User-Friendly Shopping Cart**: Add, remove, and manage products effortlessly
* **Product Reviews & Ratings**: Users can leave reviews and rate products to help others make informed decisions
* **Product Carousel**: Highlight top-rated or featured products with a smooth carousel
* **Pagination**: Efficient navigation through product listings with pagination support
* **Search Functionality**: Quickly find products by searching with keywords
* **User Profiles**: Registered users can manage their profiles and view order histories
* **Admin Dashboard**: Manage all aspects of the platform with an easy-to-use admin dashboard
* **Order Tracking**: Admins can mark orders as delivered and view detailed order information
* **Secure Checkout**: Customers can complete their purchase using secure payment options with Razorpay integration
* **Database Seeder**: Populate the platform with sample data for easy testing and demo purposes

## Getting Started

### Prerequisites

To set up this project on your local environment, ensure you have the following:

1. MongoDB: Create an account on MongoDB Atlas
2. Razorpay: Sign up for a Razorpay account and retrieve your API credentials
3. SMTP Email: Create an account on Brevo for email functionality

### Steps to Setup

1. Fork and clone the repository:
```bash
git clone https://github.com/your-username/MERN-eCommerce.git
cd MERN-eCommerce
```

2. Create a `.env` file based on the `.env.example` and add the following environment variables:
```env
NODE_ENV=development
PORT=5000
JWT_SECRET=your_jwt_secret
MONGO_URI=your_mongodb_uri
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
EMAIL_HOST=smtp-relay.brevo.com
EMAIL_PORT=587
EMAIL_USER=your_brevo_email
EMAIL_PASS=your_brevo_password
EMAIL_FROM=your_brevo_email
```

3. Install project dependencies:
```bash
npm install
cd frontend
npm install
```

4. Run the app (backend and frontend):
```bash
npm run dev
```

## Database Seeding

Seed the database with test data:
```bash
# Populate the database
npm run data:import

# Delete all data
npm run data:destroy
```

## Sample User Logins

You can use the following credentials to explore the platform:

### Admin Dashboard
- **Email**: `admin@admin.com`
- **Password**: `admin123`

### Customer Account
- **Email**: `john@email.com`
- **Password**: `john123`

Feel free to customize the platform as per your needs!

## Contributing to the Project

We appreciate contributions from developers, designers, and testers. Here's how you can contribute:

### 1. Fork and Clone the Repository
```bash
git clone https://github.com/your-username/MERN-eCommerce.git
cd MERN-eCommerce
```

### 2. Create a New Branch
```bash
git checkout -b feature/your-feature-name
```

### 3. Implement and Test Changes
Make sure your changes are well-tested and aligned with the project's coding conventions.

### 4. Commit Your Changes
```bash
git add .
git commit -m "Describe your changes"
git push origin feature/your-feature-name
```

### 5. Open a Pull Request
After pushing your changes, go to your GitHub repository and open a pull request with a clear description of the modifications.

## Code Review Process

Project maintainers will review your pull request and may provide feedback for improvements. Please address any comments or suggestions to ensure a smooth integration of your contributions.

Thank you for your support and happy coding! 😊
