# Crafty Corner

## Project Overview
Crafty Corner is an e-commerce platform designed to sell custom-designed clothing and handmade crafts. The main goals of the project are:

- *Empower local creators*: Provide a platform for independent artisans to showcase and sell their handmade works.
- *Sell in-house clothing*: Offer a curated selection of custom-designed clothing produced by Crafty Corner.
- *Customer engagement*: Enable users to discover unique, handmade products and shop online with an intuitive user experience.
- *Facilitate secure transactions*: Ensure a seamless and secure checkout process with multiple payment options.
- *Community growth*: Build a creative community where sellers and customers can interact through product reviews and feedback.

## Functional Requirements
### 1. Product Search and Browsing
- Customers can search for products by category (e.g., clothing, handmade items), price range, or keywords.
- Sellers can filter and manage their submitted items through the Seller Portal.

### 2. Shopping Cart and Checkout
- Customers can add products to their shopping cart, review items, and proceed through a secure checkout.
- The system will calculate total costs, including taxes and shipping.
- Integration with a payment gateway (e.g., Credit Card, Cash on Delivery) to process payments securely.

### 3. Seller Portal
- Sellers can create accounts, upload handmade products with descriptions and images, and set prices.
- Product Management: Sellers can update their products, manage stock levels, and track sales.

### 4. Admin Functionality
- Admins have the ability to approve or reject products submitted by sellers.
- Admins can manage both customer and seller accounts and perform site-wide updates (e.g., promotions, content changes).

### 5. User Management
- Registration/Login: Customers and sellers can register for an account and log in to access their respective dashboards.
- Account Management: Users can update their profiles, manage shipping addresses, and view order history.

### 6. Order Tracking and Notifications
- After making a purchase, customers can track the status of their orders.
- Email notifications will be sent to both customers and sellers regarding order updates, product submissions, and payment confirmations.

### 7. Reviews and Ratings
- Customers can leave reviews and rate products they’ve purchased, contributing to the quality control of items on the platform.

## Non-Functional Requirements
### 1. Performance
- The system should respond to user actions (such as loading a product or completing a checkout) within 2 seconds under normal conditions.
- It must support 250 concurrent users without significant performance degradation.

### 2. Security
- All sensitive data (user credentials, payment details) must be encrypted in transit and at rest using industry-standard encryption methods (e.g., SSL).
- Only authorized users should be able to access and modify their respective data (e.g., sellers managing their products, customers managing their orders).
- The platform must comply with GDPR regulations to ensure proper handling of personal data.

### 3. Usability
- The platform will have a user-friendly interface with easy navigation, ensuring users can browse and shop without unnecessary complexity.
- It will be accessible to users with disabilities and follow WCAG 2.1 accessibility standards.

### 4. Reliability and Availability
- The platform will have a 99.9% uptime guarantee, ensuring that users can access the site without major interruptions.
- In case of server failure, the system should recover and be fully operational within 5 minutes.

### 5. Scalability
- The system will be able to scale to handle 800 registered users and 350 product listings. It should be flexible enough to accommodate future growth as the platform and community expand.

### 6. Compatibility
- The platform will be compatible with all modern web browsers (e.g., Chrome, Firefox, Safari, Edge) and support mobile-friendly browsing for users accessing the site via smartphones or tablets.

## Implementation Processes
### 1. Development Methodology: Agile
The Agile methodology will be used for the development of Crafty Corner. Agile is best suited for this project because it encourages frequent iterations, client feedback, and collaboration, ensuring that the project stays on track and meets both business and user requirements.
