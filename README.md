# E-commerce Application

This is a comprehensive e-commerce application that provides a range of features for an online store. It includes essential functionalities such as product listings, product details, cart management, checkout process, secure card payments, cash payments, an admin panel for managing orders and products, sorting, filtering, and pagination queries, authentication using Passport JS strategies, order and password reset emails, and user profile management.

## Features

🔥 **Basic E-commerce Features**
- Product Lists: Browse through a wide range of products available in the store.
- Product Details: View detailed information about each product, including images, descriptions, prices, and customer reviews.
- Cart: Add products to the cart and manage quantities before proceeding to checkout.
- Checkout: Complete the purchase process by providing necessary shipping and payment information.

🔒 **Secure Card Payments / Cash Payments**
- Secure Card Payments: Safely process payments using secure payment gateways, ensuring the confidentiality of sensitive card information.
- Cash Payments: Provide an option for customers to choose cash on delivery or other offline payment methods.

🛠️ **Admin Panel**
- Add/Edit Orders: Admin users can manage orders by adding new orders, updating existing ones, and keeping track of the order status.
- Add/Edit Products: Admin users have the ability to add new products, update existing product details, and manage the product inventory.

🔍 **Sorting, Filtering, and Pagination**
- Mongoose queries enable sorting, filtering, and pagination options, allowing users to easily find the desired products based on their preferences.

🔐 **Authentication with Passport JS Strategies**
- Implement user authentication using Passport JS strategies, which support various authentication methods such as local authentication, social media logins, and more.

📧 **Order Emails, Reset Password Emails**
- Send order confirmation emails to customers upon successful completion of their purchases.
- Provide password reset functionality and send reset password emails to users who have requested a password reset.

👤 **User Profile and User Orders**
- Users can create and manage their profiles, update personal information, and view their order history.

## Technologies Used

- Node.js: A JavaScript runtime environment.
- Express.js: A web application framework for Node.js.
- MongoDB: A NoSQL database for storing product, order, and user information.
- Mongoose: A MongoDB object modeling tool for Node.js.
- Passport.js: An authentication middleware for Node.js.
- Tailwind: Styling for the user interface.
- JavaScript: Programming language for client-side interactions.
- Stripe: Integration with a secure payment gateway provider.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/aneeese/ecommerce-app.git
   ```
2. Change to the project directory:
   ```
   cd ecommerce-app
   ```
3. Install the dependencies:
   ```
   npm install
   ```
4. Set up the environment variables by creating a `.env` file in backend folder and filling in the required values:
   ```
   PORT = 8080
   MONGODB_URL = mongodb://127.0.0.1:27017/MERN_E-Commerce
   SECRET_KEY=your_secret_key
   PORT = 8080
   ENDPOINT_SECRET = 
   STRIPE_SERVER_KEY = 
   JWT_SECRET_KEY = Jwtsecret
   SESSION_KEY = SessionKey 
   ```
5. Start the application:
   ```
   npm start (in both frontend and backend directories)
   ```
6. Access the application at `http://localhost:3000` in your web browser.

**Note:** Make sure you have Node.js and MongoDB installed on your system before running the application.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.