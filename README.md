<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1 style="color: red; font-weight: bold;">E-Commerce Application (MERN Stack)</h1>
    <p>This is a comprehensive e-commerce application built with the MERN stack (MongoDB, Express, React, Node.js). It consists of a frontend developed with React and a backend built with Node.js and Express.</p>
   <h2>Demo</h2>
    <p>Check out the live demo: <a href="https://cleverxpress.web.app/" target="_blank">https://cleverxpress.web.app/</a></p>
        <h2>Features</h2>
         <h3>Frontend</h3>
         <ul>
        <li><strong>Authentication & Authorization:</strong> Secure user login and registration with JWT.</li>
        <li><strong>Product Management:</strong> View, search, filter, and sort products.</li>
        <li><strong>Shopping Cart:</strong> Add, remove, and manage products in the shopping cart.</li>
        <li><strong>Order Management:</strong> Place orders, choose payment methods, and manage order history.</li>
        <li><strong>Admin Dashboard:</strong> Manage products, categories, brands, and orders.</li>
        <li><strong>User Profile:</strong> Manage user profile, addresses, and order history.</li>
        <li><strong>Responsive Design:</strong> Optimized for both desktop and mobile devices.</li>
        <li><strong>Multilingual Support:</strong> Integration with Google Translator for multiple languages.</li>
    </ul>
     <h3>Backend</h3>
      <ul>
        <li><strong>Authentication & Authorization:</strong> Secure user authentication using JWT.</li>
        <li><strong>Product Management:</strong> CRUD operations for products.</li>
        <li><strong>Category & Brand Management:</strong> CRUD operations for categories and brands.</li>
        <li><strong>Order Management:</strong> Manage customer orders and payment processing.</li>
        <li><strong>User Management:</strong> User profile management and address book.</li>
        <li><strong>Cart Management:</strong> Add, remove, and manage items in the cart.</li>
        <li><strong>Wishlist Management:</strong> Add, remove, and manage wishlist items.</li>
        <li><strong>Review Management:</strong> Add, edit, and delete product reviews.</li>
        <li><strong>Coupon Management:</strong> Create and apply discount coupons.</li>
    </ul>
    <h2>Technologies Used</h2>
    <h3>Frontend</h3>
    <ul>
        <li><strong>React:</strong> Library for building user interfaces.</li>
        <li><strong>Redux Toolkit:</strong> State management.</li>
        <li><strong>React Router:</strong> Client-side routing.</li>
        <li><strong>Bootstrap:</strong> Responsive design framework.</li>
        <li><strong>Axios:</strong> Promise-based HTTP client.</li>
        <li><strong>React Toastify:</strong> Notification system.</li>
        <li><strong>React Paginate:</strong> Pagination component.</li>
        <li><strong>Firebase:</strong> For various backend services and tools.</li>
    </ul>
    <h3>Backend</h3>
    <ul>
        <li><strong>Node.js:</strong> JavaScript runtime for server-side development.</li>
        <li><strong>Express:</strong> Web framework for Node.js.</li>
        <li><strong>MongoDB:</strong> NoSQL database for data storage.</li>
        <li><strong>Mongoose:</strong> ODM library for MongoDB.</li>
        <li><strong>JWT:</strong> JSON Web Tokens for secure authentication.</li>
        <li><strong>Bcrypt:</strong> Library for hashing passwords.</li>
        <li><strong>Nodemailer:</strong> Library for sending emails.</li>
    </ul>
     <h2>Project Structure</h2>
    <h3>Frontend</h3>
    <ul>
        <li><strong>src/App.js:</strong> Main application file where routes are defined.</li>
        <li><strong>src/RTK/store.js:</strong> Redux store configuration.</li>
        <li><strong>src/index.js:</strong> Main entry point of the React application.</li>
    </ul>
    <h3>Backend</h3>
    <ul>
        <li><strong>config:</strong> Configuration files for the application.</li>
        <li><strong>controllers:</strong> Contains the logic for handling various routes.</li>
        <li><strong>middlewares:</strong> Custom middleware functions.</li>
        <li><strong>models:</strong> Mongoose models for MongoDB.</li>
        <li><strong>routes:</strong> Express routes for different API endpoints.</li>
        <li><strong>utils:</strong> Utility functions and helpers.</li>
    </ul>
        <h2>Installation</h2>
    <h3>Frontend</h3>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/FadyFathey/frontend-repo.git</code></pre>
        </li>
        <li>Navigate to the project directory:
            <pre><code>cd frontend-repo/e-commerce-app</code></pre>
        </li>
        <li>Install dependencies:
            <pre><code>npm install</code></pre>
        </li>
        <li>Start the development server:
            <pre><code>npm start</code></pre>
        </li>
    </ol>
    <p>The application will start on <a href="http://localhost:3000">http://localhost:3000</a>.</p>
     <h3>Backend</h3>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/FadyFathey/FULL-MEARN-STACK-REACT-PROJECT.git</code></pre>
        </li>
        <li>Navigate to the project directory:
            <pre><code>cd FULL-MEARN-STACK-REACT-PROJECT</code></pre>
        </li>
        <li>Install dependencies:
            <pre><code>npm install</code></pre>
        </li>
        <li>Create a <code>.env</code> file and add your environment variables:
            <pre><code>
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
            </code></pre>
        </li>
        <li>Start the server:
            <pre><code>npm run dev</code></pre>
        </li>
    </ol>
    <p>The server will start on <a href="http://localhost:5000">http://localhost:5000</a>.</p>
     <h2>Available Scripts</h2>
    <h3>Frontend</h3>
    <ul>
        <li><code>npm start:</code> Runs the app in development mode.</li>
        <li><code>npm test:</code> Launches the test runner.</li>
        <li><code>npm run build:</code> Builds the app for production.</li>
        <li><code>npm run eject:</code> Ejects the app configuration.</li>
    </ul>
     <h3>Backend</h3>
    <ul>
        <li><code>npm start:</code> Runs the server in production mode.</li>
        <li><code>npm run dev:</code> Runs the server in development mode with nodemon.</li>
        <li><code>npm test:</code> Runs the test suite.</li>
    </ul>
    <h2>API Endpoints (Backend)</h2>
    <h3>Authentication</h3>
    <ul>
        <li><code>POST /api/v1/auth/register:</code> Register a new user.</li>
        <li><code>POST /api/v1/auth/login:</code> Login a user.</li>
        <li><code>POST /api/v1/auth/forgotpassword:</code> Send password reset link.</li>
        <li><code>PUT /api/v1/auth/resetpassword/:resettoken:</code> Reset password.</li>
    </ul>
     <h3>Users</h3>
    <ul>
        <li><code>GET /api/v1/users:</code> Get all users.</li>
        <li><code>GET /api/v1/users/:id:</code> Get user by ID.</li>
        <li><code>PUT /api/v1/users/:id:</code> Update user.</li>
        <li><code>DELETE /api/v1/users/:id:</code> Delete user.</li>
    </ul>
      <h3>Products</h3>
    <ul>
        <li><code>GET /api/v1/products:</code> Get all products.</li>
        <li><code>GET /api/v1/products/:id:</code> Get product by ID.</li>
        <li><code>POST /api/v1/products:</code> Create a new product.</li>
        <li><code>PUT /api/v1/products/:id:</code> Update product.</li>
        <li><code>DELETE /api/v1/products/:id:</code> Delete product.</li>
    </ul>
     <h3>Orders</h3>
    <ul>
        <li><code>GET /api/v1/orders:</code> Get all orders.</li>
        <li><code>GET /api/v1/orders/:id:</code> Get order by ID.</li>
        <li><code>POST /api/v1/orders:</code> Create a new order.</li>
        <li><code>PUT /api/v1/orders/:id:</code> Update order.</li>
        <li><code>DELETE /api/v1/orders/:id:</code> Delete order.</li>
    </ul>
        <h2>Contributing</h2>
    <p>Contributions are welcome! Please open an issue or submit a pull request if you would like to contribute to the project.</p>
  <h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
</body>
</html>
