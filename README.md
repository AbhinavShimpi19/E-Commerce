## E-Commerce Website (React & Node.js)

👉 This is a full-featured E-Commerce website built using the MERN stack (MongoDB, Express, React, Node.js). It includes essential functionalities like user authentication, product management, cart system, payment integration, and order management.

## Features
![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Fy9SdZLBTOo/0.jpg)

**👉 Frontend (React)**
- Modern UI: Built with React and styled using CSS3
- Responsive Design: Works seamlessly on all devices
- Product Display: Browse products with detailed descriptions and images
- Shopping Cart: Add, remove, and update products in the cart
- User Authentication: Register, login, and manage user profile
- Checkout Process: Shipping, payment selection, and order placement
- Admin Dashboard: Manage users, orders, and products

**👉 Backend (Node.js & Express)**

- RESTful API: Handles user authentication, product management, and orders
- JWT Authentication: Secure user login & authorization
- MongoDB Database: Stores users, products, orders, and reviews
- Mongoose ODM: Efficient database queries and schema validation
- Payment Integration: Supports PayPal for secure transactions
- File Uploads: Upload and manage product images using Multer
- Order Management: Track orders and update order status

**👉 Deployment & Development**

- Git & GitHub: Version control and repository management
- ESLint & Babel: Code quality and modern JavaScript support
- Deployment: Hosted on Heroku with MongoDB Atlas


## Run Locally

### 1. Clone repo

```
$ git clone git@github.com:AbhinavShimpi19/node-react-ecommerce.git
$ cd node-react-ecommerce
```

### 2. Install MongoDB

Download it from here: https://docs.mongodb.com/manual/administration/install-community/

### 3. Run Backend

```
$ npm install
$ npm start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Create Admin User

- Run this on chrome: http://localhost:5000/api/users/createadmin
- It returns admin email and password

### 6. Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin

### 7. Create Products

- Run http://localhost:3000/products
- Click create product and enter product info

## Technologies Used
- Frontend: React, Redux, React Router, Axios
- Backend: Node.js, Express, MongoDB, Mongoose
- Authentication: JWT, bcrypt.js
- Deployment: Heroku, MongoDB Atlas
