# Acadewise_Backend

## File structure

```{bash}
- /your-backend
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
    - ...                 // Other models
  - /routes
    - authRoutes.js       // Authentication routes
    - paymentRoutes.js    // Payment processing routes
    - fileRoutes.js       // File upload and sharing routes
    - adminRoutes.js      // Admin panel routes
    - index.js            // Combine and export all routes
  - /services
    - authService.js      // Authentication service
    - paymentService.js   // Payment processing service
    - fileService.js      // File upload and sharing service
    - adminService.js     // Admin panel service
  - /utils
    - constants.js        // Constants and configuration values
    - errorHandler.js     // Error handling utility
    - validator.js        // Input validation utility
  - /views
    - // Admin panel views (if using server-side rendering)
  - /public
    - // Public files (e.g., images, stylesheets)
  - server.js             // Main server file

```
