
# 📚 Online Book Store

An **Online Book Store** built using **React** and **TypeScript**, featuring a robust Admin Dashboard and a user-friendly interface for customers. This project offers role-based access, where admins can manage the store's inventory and users can browse, purchase, and review books.

## 🖥️ Demo

Check out the live demo: [Online Book Store](https://online-book-store-sandy.vercel.app/)

## 📋 Table of Contents

- [📚 Online Book Store](#-online-book-store)
  - [🖥️ Demo](#️-demo)
  - [📋 Table of Contents](#-table-of-contents)
  - [✨ Features](#-features)
  - [🛠️ Tech Stack](#️-tech-stack)
  - [🗂️ Project Structure](#️-project-structure)
  - [🛠️ Installation](#️-installation)
    - [Steps](#steps)
  - [🔑 Environment Variables](#-environment-variables)
  - [🚀 Usage](#-usage)
  - [🛂 Roles \& Permissions](#-roles--permissions)
  - [📊 Admin Dashboard](#-admin-dashboard)
  - [📦 Deployment](#-deployment)
    - [Deployment Commands](#deployment-commands)
  - [🤝 Contributing](#-contributing)
  - [📬 Contact](#-contact)

## ✨ Features

- **User Authentication & Authorization**: Secure login and registration for both Admin and Customer roles.
- **Role-Based Access Control**:
  - **Admin Role**: Manage books, orders, users, and view analytics.
  - **Customer Role**: Browse books, add to cart, make purchases, and leave reviews.
- **Admin Dashboard**: Intuitive dashboard for managing the online store, including book inventory, order tracking, and user management.
- **Book Management**: Create, update, and delete books with detailed information.
- **Shopping Cart**: Add, update, or remove books from the cart.
- **Order Management**: Customers can track their order status; Admins can manage order processing.
- **Search & Filtering**: Easily search and filter books by category, author, or rating.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## 🛠️ Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS, React Query, React Hook Form, React Router
- **State Management**: Context API and  Redux 
- **Authentication**: JSON Web Tokens (JWT)
- **Payment Integration**: Stripe API
- **Form Validation**: Yup with React Hook Form
- **Deployment**: Vercel (Frontend)

## 🗂️ Project Structure

```
├── public
├── src
│   ├── assets
│   ├── components
│   ├── contexts
│   ├── hooks
│   ├── pages
│   ├── services
│   ├── types
│   └── utils
├── .env
├── package.json
├── README.md
└── tsconfig.json
```

## 🛠️ Installation



### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/online-book-store.git
   cd online-book-store
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

## 🔑 Environment Variables

Create a `.env` file in the root directory with the following:

```
REACT_APP_API_URL=http://localhost:5000
REACT_APP_STRIPE_PUBLIC_KEY=your-stripe-public-key
JWT_SECRET=your-jwt-secret
MONGODB_URI=your-mongodb-uri
```

## 🚀 Usage

- **Admin**:
  - Login as Admin to access the dashboard.
  - Manage books, users, and orders.
- **Customer**:
  - Browse books, add to cart, and place orders.
  - Leave reviews for purchased books.

## 🛂 Roles & Permissions

| Role     | Permissions                                     |
| -------- | ----------------------------------------------- |
| Admin    | Full access to the dashboard, manage users, books, and orders |
| Customer | Browse books, add to cart, make purchases, and leave reviews |

## 📊 Admin Dashboard

The Admin Dashboard provides:

- **Book Management**: Add, update, or delete books.
- **User Management**: View and manage user information.
- **Order Tracking**: Track and update the status of orders.
## 📦 Deployment

- **Frontend**: Deployed on Vercel

### Deployment Commands

```bash
# Build the frontend for production
npm run build

# Deploy to Vercel
vercel deploy
```

## 🤝 Contributing

Contributions are welcome! Please fork the repository and create a pull request.

1. Fork the project
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request



## 📬 Contact

- **Your Name** - [Your Email](mahmoudabdoh2211@gmail.com)
- **GitHub**: [your-username](https://github.com/mahmoudabdos)
