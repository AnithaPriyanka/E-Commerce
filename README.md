# 🛒 ShopKart - E-commerce Single Page Application

A modern, responsive e-commerce web application built with vanilla HTML, CSS, and JavaScript. Features a beautiful glassmorphism design with complete shopping functionality including user authentication, product catalog, shopping cart, and more.

## 🌟 Features

### 🔐 User Authentication
- **User Registration**: Create new accounts with name, email, and password
- **User Login**: Secure login system with validation
- **Session Management**: Persistent login state across page refreshes
- **Admin Account**: Pre-configured admin user for testing

### 🛍️ Product Catalog
- **28 Products** across 6 categories
- **Categories**: Electronics, Home Appliances, Fashion, Books, Sports & Fitness, Beauty
- **Product Details**: High-quality images, descriptions, and pricing
- **Indian Market Focus**: Products and pricing tailored for Indian consumers

### 🔍 Advanced Filtering
- **Category Filter**: Browse products by specific categories
- **Price Range Filter**: Set minimum and maximum price limits
- **Real-time Filtering**: Instant results as you adjust filters
- **Responsive Grid**: Adaptive layout for all screen sizes

### 🛒 Shopping Cart
- **Add to Cart**: One-click product addition
- **Quantity Management**: Increase/decrease item quantities
- **Remove Items**: Delete unwanted products
- **Cart Persistence**: Cart data saved in browser storage
- **Real-time Total**: Automatic price calculation
- **Cart Counter**: Live item count in navigation

### 💰 Indian Currency (INR)
- **Rupee Pricing**: All prices displayed in Indian Rupees (₹)
- **Number Formatting**: Indian number system formatting
- **Realistic Pricing**: Market-appropriate pricing for Indian consumers

### 🎨 Modern UI/UX
- **Glassmorphism Design**: Modern glass-like aesthetic with blur effects
- **Gradient Backgrounds**: Beautiful color gradients
- **Hover Effects**: Interactive animations and transitions
- **Responsive Design**: Mobile-first approach, works on all devices
- **Box Shadows**: Depth and elevation effects

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with modern features
  - Flexbox and CSS Grid for layouts
  - CSS Variables for consistent theming
  - Backdrop-filter for glassmorphism effects
  - Smooth animations and transitions
- **JavaScript ES6+**: Modern JavaScript features
  - Arrow functions and template literals
  - Local Storage API for data persistence
  - Event handling and DOM manipulation
  - Array methods for data processing


## 🎯 Usage

### For Users
1. **Sign Up**: Create a new account or use demo credentials
2. **Browse Products**: Explore 28+ products across 6 categories
3. **Filter Products**: Use category and price filters to find items
4. **Add to Cart**: Click "Add to Cart" on desired products
5. **Manage Cart**: Adjust quantities or remove items
6. **View Total**: See real-time cart total in Indian Rupees

### Demo Credentials
```
Email: admin@example.com
Password: admin123
```

## 🏗️ Project Structure

```
shopkart-ecommerce/
│
├── index.html          # Main application file
├── README.md          # Project documentation
└── assets/            # (Optional: for additional assets)
    ├── screenshots/
    └── icons/
```

## 🛍️ Product Categories

| Category | Products | Price Range |
|----------|----------|-------------|
| **Electronics** | MacBook, Samsung Galaxy, Sony Headphones, iPad Pro, Canon Camera, Dell Laptop | ₹29,990 - ₹1,29,999 |
| **Home Appliances** | Smart TV, Washing Machine, Coffee Maker, Air Fryer, Refrigerator | ₹5,999 - ₹32,990 |
| **Fashion** | Levi's Jeans, Nike Sneakers, T-Shirts, Denim Jacket, Running Shoes | ₹999 - ₹16,999 |
| **Books** | Self-help, Philosophy, Autobiography, Finance | ₹199 - ₹399 |
| **Sports & Fitness** | Yoga Mat, Cricket Bat, Football, Dumbbells | ₹899 - ₹3,999 |
| **Beauty** | Lipstick, Face Wash, Hair Dryer, Razor | ₹399 - ₹1,999 |

## 💾 Data Storage

- **User Accounts**: Stored in JavaScript array (in-memory)
- **Product Catalog**: Static array with 28+ products
- **Shopping Cart**: Persistent storage using Browser's Local Storage API
- **User Sessions**: Session-based authentication

> **Note**: This is a demo application. In production, you would use a proper database and backend authentication system.

