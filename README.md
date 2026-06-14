# ShopEase - E-Commerce Website

## 📌 Project Overview

**ShopEase** is a modern, fully functional e-commerce web application built with HTML, CSS, and vanilla JavaScript. It provides a seamless shopping experience with product browsing, filtering, search functionality, shopping cart management, and checkout capabilities.

## ✨ Key Features

### Product Management
- **12 Pre-loaded Products** across 4 categories (Men, Women, Electronics, Accessories)
- **Product Grid Display** with emoji icons, names, prices, and categories
- **Responsive Product Cards** with hover animations

### Shopping Features
- **Category Filtering** - Browse products by category or view all
- **Search Functionality** - Real-time search across product names
- **Add to Cart** - Easily add items to shopping cart
- **Cart Management** - View, update quantities, and remove items
- **Cart Counter** - Badge showing total items in cart

### Checkout & Order
- **Shopping Cart Sidebar** - Slide-out cart overlay with all items
- **Checkout Modal** - Multi-step checkout form with:
  - Full name field
  - Email address
  - Shipping address
  - Payment method selection (Card, UPI, Cash on Delivery)
- **Toast Notifications** - Feedback messages for user actions
- **Order Confirmation** - Thank you message upon order placement

### User Interface
- **Sticky Header** - Navigation always visible while scrolling
- **Hero Banner** - Promotional messaging with "Big Summer Sale" campaign
- **Professional Footer** - Links and contact information
- **Responsive Design** - Mobile-friendly layout
- **Color Scheme** - Dark header with orange accents (#ff6f3c)

## 🏗️ Project Structure

```
ecommerce website/
├── home.html           # Main HTML page
├── script.js           # JavaScript functionality
├── css/
│   └── style.css       # All styling (CSS)
├── style1.css          # Original CSS (deprecated)
├── script1.css         # Original JavaScript (deprecated)
└── readme/
    └── README.md       # This file
```

## 📦 Products Catalog

### Men's Category
- Men's Casual Shirt - ₹999
- Men's Denim Jacket - ₹2,499
- Men's Running Shoes - ₹1,799

### Women's Category
- Women's Summer Dress - ₹1,499
- Women's Handbag - ₹1,999
- Women's Sneakers - ₹1,599

### Electronics Category
- Wireless Headphones - ₹2,999
- Smart Watch - ₹3,499
- Bluetooth Speaker - ₹1,299

### Accessories Category
- Sunglasses - ₹799
- Leather Wallet - ₹599
- Backpack - ₹1,899

## 🛠️ Technology Stack

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with flexbox and grid layouts
- **Vanilla JavaScript** - No frameworks or libraries
- **Responsive Design** - Mobile and desktop support

## 🚀 How to Use

1. **Open the Website** - Open `home.html` in any modern web browser
2. **Browse Products** - Scroll through the product grid or use category filters
3. **Search Products** - Type in the search bar to find specific items
4. **Add to Cart** - Click "Add to Cart" on any product
5. **View Cart** - Click the cart button (🛒) in the header
6. **Checkout** - Click "Checkout" button in the cart sidebar
7. **Complete Purchase** - Fill in your details and select payment method
8. **Confirmation** - Receive order confirmation message

## 💻 JavaScript Functionality

### Key Functions
- `renderProducts()` - Displays filtered products based on category and search
- `addToCart(id)` - Adds product to cart
- `updateCart()` - Updates cart display and totals
- `changeQty(id, delta)` - Adjusts product quantity
- `removeFromCart(id)` - Removes item from cart
- `showToast(message)` - Displays notification messages

### State Management
- Maintains product data array
- Tracks cart items and quantities
- Manages current category filter
- Stores search term state

## 🎨 Design Features

- **Color Palette**
  - Dark Background: #1f2937
  - Primary Accent: #ff6f3c
  - Light Background: #f5f5f5
  - Text: #333

- **Animations**
  - Card hover effects with lift animation
  - Smooth cart slide-in/out
  - Toast notification animations
  - Smooth color transitions

- **Typography**
  - Font Family: Segoe UI, Arial, sans-serif
  - Responsive font sizes
  - Bold product names and prices

## 📱 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## ✅ Features Implemented

- ✅ Product catalog with 12 items
- ✅ Category filtering
- ✅ Search functionality
- ✅ Shopping cart with add/remove
- ✅ Quantity management
- ✅ Cart total calculation
- ✅ Checkout form
- ✅ Payment method selection
- ✅ Toast notifications
- ✅ Responsive design
- ✅ Professional UI/UX

## 🔄 State Flow

```
User Action → Event Listener → Function Execution → DOM Update
    ↓                                                    ↓
Click Add to Cart → addToCart() → updateCart() → Refresh cart display
```
## 👨‍💻 Development

This project uses vanilla JavaScript without any frameworks, making it lightweight and easy to understand. 
**Last Updated:** June 14, 2026  
**Status:** Fully Functional
