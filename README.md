# Acadewise_Backend

## File structure

```{bash}
- /src
  - /pages
    - /api
      - auth.js           // Authentication API route
      - payment.js        // Payment processing API route
      - file.js           // File upload and sharing API route
      - admin.js          // Admin panel API route
    - /_app.js            // Custom App component for global styles and layout
    - /_document.js       // Custom Document component for server-rendered pages
    - index.js            // Landing page
    - login.js            // Login page
    - signup.js           // Signup page
    - forgot-password.js  // Forgot password page
    - blogs
      - [slug].js         // Dynamic route for individual blog posts
    - services
      - [slug].js         // Dynamic route for individual services
    - jobs
      - [slug].js         // Dynamic route for individual job listings
  - /config
    - db.js               // Database connection configuration
    - firebase.js         // Firebase configuration
    - stripe.js           // Stripe configuration (if applicable)
    - paypal.js           // PayPal configuration (if applicable)
  - /controllers
    - authController.js   // User authentication controllers
    - paymentController.js // Payment processing controllers
    - fileController.js   // File upload and sharing controllers
    - adminController.js  // Admin panel controllers
  - /middlewares
    - authMiddleware.js   // Authentication middleware
    - validationMiddleware.js // Input validation middleware
  - /models
    - User.js             // User model
    - Blog.js             // Blog model
    - Service.js          // Service model
    - Payment.js          // Payment model
    - Link.js             // Link model
    - File.js             // File model
    - Policy.js           // Policy model
    - Job.js              // Job model
  - /services
    - authService.js      // Authentication service
    - paymentService.js   // Payment processing service
    - fileService.js      // File upload and sharing service
    - adminService.js     // Admin panel service
  - /utils
    - constants.js        // Constants and configuration values
    - errorHandler.js     // Error handling utility
    - validator.js        // Input validation utility
  - /public
    - /uploads            // Folder for uploaded files
    - /img                // Folder for images
    - /css                // Folder for stylesheets
    - // Other public files (e.g., favicon.ico)
  - server.js             // Main server file

```
I am in I have to Learn MongoDB and Node.js