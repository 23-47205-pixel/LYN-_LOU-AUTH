A modern, responsive web application that combines user authentication with an interactive clothing e-commerce interface.

📋 Overview
This project features a sleek login system with both traditional and Google OAuth authentication, transitioning to a beautifully designed clothing collection showcase after successful login. The application includes interactive shopping features like wishlists and shopping carts with a stunning glassmorphism design.

✨ Features
🔐 Authentication System
Traditional username/password login with validation

Google OAuth integration

Password visibility toggle

Secure logout with confirmation modal

Form validation with error messages

👗 Clothing Collection (4 Products)
Harpa - Women's printed clothing

H&N - Blue Printed A-Line Dress

MANGO - Black Solid Bodycon Dress

ONLY - Red Floral Dress

Each product features:

High-quality images from Unsplash

Original and discounted prices

Discount percentages displayed

Add to Bag and Wishlist buttons

🛍️ Shopping Features
Add to Wishlist: Save items for later viewing

Add to Cart: Add items to shopping cart

Interactive Counters: Real-time updates for wishlist and cart items

Modal Popups: View wishlist and cart contents

User Info Bar: Display welcome message and avatar (for Google login)

🎨 Design Elements
Glassmorphism Design: Frosted glass effect on all containers

Gradient Backgrounds: Purple-blue gradient background

Hover Animations: Smooth transitions and scale effects

Responsive Layout: Mobile-first design

Color Scheme: Purple/pink gradients with complementary accents

Custom Typography: Montserrat font for modern appearance

🛠️ Technologies Used
HTML5 - Structure and content

CSS3 - Advanced styling with animations

JavaScript - Interactive functionality

Bootstrap 5.3.2 - Responsive grid system and components

Font Awesome 6.4.0 - Icons

Google Fonts - Montserrat typography

Google Identity Services - OAuth authentication

Unsplash - High-quality product images

📁 File Structure
Single HTML file containing:

HTML structure

Embedded CSS styles

JavaScript functionality

All external CDN links

🚀 Quick Start
Clone or download the HTML file

Open index.html in any modern web browser

Use the following login options:

Traditional Login: Any username, password (minimum 4 characters)

Google Login: Click "Sign In Using Google" button

💻 Usage Instructions
Login Process
Traditional Login:

Enter any username

Enter password (minimum 4 characters)

Click "LOGIN" button

Google Login:

Click the Google Sign In button

Select Google account

Grant permission

Shopping Features
Add to Bag: Adds item to shopping cart (counter updates)

Wishlist: Saves item to wishlist (counter updates)

View Counters: See number of items in wishlist/cart

View Details: Click wishlist/cart buttons to see contents in modal

User Interface
User Avatar: Displayed for Google login users

Welcome Message: Personalized greeting

Navigation:

Wishlist Button: View saved items

Cart Button: View cart items

Log Out Button: Secure logout with confirmation

🎯 Key JavaScript Functions
Authentication
loginUser(): Validates and processes traditional login

handleGoogleResponse(): Processes Google OAuth response

logoutUser(): Handles user logout and resets state

confirmLogout(): Shows logout confirmation modal

UI Interactions
togglePassword(): Toggles password visibility

showClothingSection(): Transitions to main shopping interface

addToWishlist(): Adds item to wishlist array

addToCart(): Adds item to cart array

showWishlist(): Displays wishlist modal

showCart(): Displays cart modal

State Management
currentUser: Object storing {name, avatar}

wishlist: Array of wishlisted items

cart: Array of cart items

updateWishlistCount(): Updates wishlist counter

updateCartCount(): Updates cart counter

🎨 Design Features
Glassmorphism Effects
background: rgba(255,255,255,0.18)

backdrop-filter: blur(12px)

border: 1px solid rgba(255,255,255,0.3)

Animations
fadeIn keyframes for smooth transitions

Hover effects with transform: translateY() and scale()

Gradient transitions on buttons

Responsive Breakpoints
Mobile (<768px): Adjusted padding, column layout

Tablet: Responsive grid columns

Desktop: Full-width container with max-width

📱 Responsive Design
The application is fully responsive with:

Mobile: Stacked layout, adjusted spacing

Tablet: 2-column grid for product cards

Desktop: 4-column grid for product cards

User Info Bar: Adapts to column layout on mobile

🔧 Customization Options
Products
Add/remove product cards in the HTML

Update product images (Unsplash URLs)

Modify product details (names, descriptions, prices)

Styling
Colors: Modify CSS variables in the <style> section

Gradients: Change linear-gradient() values

Animations: Adjust @keyframes and transition durations

Functionality
Google OAuth: Replace client ID with your own

Form Validation: Modify validation rules in loginUser()

Shopping Features: Extend wishlist/cart functionality

⚠️ Important Notes
Google OAuth
The current Google OAuth client ID (855865687175-fhhra5hajbihsgpgmaiq92toq3oh9gd7.apps.googleusercontent.com) is for demonstration. For production:

Register your app in Google Cloud Console

Replace the client ID

Configure authorized domains

Data Persistence
Current implementation uses client-side JavaScript arrays

Data is lost on page refresh/logout

For persistent storage, consider adding:

LocalStorage/SessionStorage

Backend API integration

Database connection

Security Considerations
Password validation is minimal (demo purposes)

For production, implement:

Strong password policies

Backend authentication

HTTPS encryption

CSRF protection

🎯 Learning Outcomes
This project demonstrates:

Modern CSS techniques (glassmorphism, gradients)

Form handling and validation

OAuth integration

Responsive design principles

JavaScript state management

Bootstrap grid system

Modal implementation

User interface transitions

🤝 Potential Enhancements
Immediate Improvements
Form Validation: More robust validation rules

Product Details: Individual product pages

Search/Filters: Product filtering functionality

Quantity Selection: Adjust item quantities in cart

Advanced Features
Backend Integration: Node.js/Express or PHP backend

Database: User accounts and order history

Payment Gateway: Stripe/PayPal integration

Admin Panel: Product management

User Reviews: Rating and review system

Social Sharing: Share products on social media

📝 License
This project is for educational and demonstration purposes. Feel free to modify and use as needed for learning or personal projects.

🚀 Deployment
To deploy this application:

Upload the HTML file to any web server

Ensure all CDN links are accessible

For Google OAuth, update authorized domains in Google Cloud Console
