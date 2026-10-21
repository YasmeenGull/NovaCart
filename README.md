# E-Commerce Website - Web Technology Project
## HTML5 & CSS3 Frontend Implementation

### Project Overview
This is a complete **frontend-only** e-commerce website built with **pure HTML5 and CSS3** for a Web Technology semester project. The website is designed with professional architecture to allow seamless integration of JavaScript, backend, and database functionality in future phases.

**Current Status:** HTML5 + CSS3 Complete (No JavaScript, No Backend, No Database)

---

## 📁 Project Folder Structure

```
ecommerce-project/
│
├── index.html                 # Home page
├── products.html              # All products listing page
├── product-details.html       # Individual product detail page
├── categories.html            # Product categories page
├── cart.html                  # Shopping cart page
├── checkout.html              # Checkout form page
├── login.html                 # Login page
├── register.html              # Registration page
├── about.html                 # About us page
├── contact.html               # Contact us page
│
├── css/
│   └── style.css              # Main stylesheet (single external CSS file)
│
├── images/
│   ├── products/              # Product images folder
│   ├── categories/            # Category images folder
│   └── banners/               # Banner/hero images folder
│
└── README.md                  # This file
```

---

## 📄 HTML Pages - Complete Description

### 1. **index.html** - Home Page
- **Sticky navigation bar** with logo, search bar, cart icon, and login/register links
- **Hero/Banner section** with promotional text and "Shop Now" call-to-action
- **Featured products section** (6-8 products with hover effects)
- **Product categories** grid (6 main categories)
- **New arrivals section** (Latest products)
- **Benefits section** (Fast Delivery, Secure Payment, Quality Products, Customer Support)
- **Newsletter subscription** form
- **Professional footer** with links, social media icons, and company info
- **Responsive design** that adapts to all screen sizes

### 2. **products.html** - Products Listing
- **Sidebar filters** UI (Price range, Categories, Ratings, etc.)
- **Sort dropdown** (Price: Low to High, High to Low, Newest, etc.)
- **Product grid** displaying 12+ products with:
  - Product image
  - Product name
  - Rating display (⭐)
  - Price & old price with discount percentage
  - "View Details" button
  - "Add to Cart" button
- **Pagination controls** (Previous, Next, page numbers)
- **Data attributes** on product cards for JavaScript integration

### 3. **product-details.html** - Product Details Page
- **Product image gallery** with multiple images layout
- **Product specifications table** (specifications, features, dimensions)
- **Price display** with old price and discount calculation
- **Rating & reviews count**
- **Product description** (detailed information)
- **Options selector** (Color, Size, etc.) with input fields
- **Quantity selector** UI
- **"Add to Cart" button**
- **"Buy Now" button**
- **Customer reviews section** (sample reviews display)
- **Related products** carousel/grid

### 4. **categories.html** - Categories Page
- **Category cards** for:
  - Electronics
  - Fashion
  - Beauty & Personal Care
  - Home & Living
  - Accessories
  - Sports & Outdoors
- Each category card contains:
  - Category image
  - Category name
  - Short description
  - "View Products" button
- **Featured products** from selected categories below

### 5. **cart.html** - Shopping Cart Page
- **Cart items table** with:
  - Product image
  - Product name
  - Unit price
  - Quantity controls (-, +, input field)
  - Subtotal per item
  - Remove button (trash icon)
- **Empty cart message** (displayed when no items)
- **Order summary** showing:
  - Subtotal
  - Shipping cost
  - Discount amount (if applicable)
  - **Total amount** (bold and prominent)
- **Promo/Discount code** input
- **Apply coupon button**
- **"Continue Shopping" button**
- **"Proceed to Checkout" button**

### 6. **checkout.html** - Checkout Page
- **Progress indicator** (Step 1 of 3 styling ready)
- **Shipping information form** with fields:
  - Full Name
  - Email
  - Phone Number
  - Address
  - City
  - Province/State
  - Postal Code
  - Country
- **Payment method selection**:
  - Credit/Debit Card (selected by default)
  - PayPal
  - Bank Transfer
  - COD (Cash on Delivery)
- **Card details form** (when card is selected):
  - Cardholder Name
  - Card Number
  - Expiry Date
  - CVV
- **Order summary** (recap of items and total)
- **Place Order button**
- **Terms & Conditions checkbox**

### 7. **login.html** - Login Page
- **Login form** with:
  - Email input
  - Password input
  - "Remember me" checkbox
  - "Login" button
  - "Forgot password?" link
- **Social login options** (Google, Facebook buttons - visual only)
- **Registration link** ("Don't have an account? Register here")
- **Promotional content** on the side

### 8. **register.html** - Registration Page
- **Registration form** with:
  - Full Name
  - Email
  - Phone Number
  - Password
  - Confirm Password
  - Terms & Conditions checkbox (required)
  - Newsletter subscription checkbox (optional)
  - "Register" button
- **Login link** ("Already have an account? Login here")
- **Form validation hints** (password strength indicator styling)

### 9. **about.html** - About Us Page
- **Company introduction** section
- **Mission & Vision** statements
- **Why choose us** section (key benefits)
- **Team member profiles** (with images and roles)
- **Company statistics** (Number of customers, orders, etc.)
- **Awards & recognition** section
- **Customer testimonials** section

### 10. **contact.html** - Contact Us Page
- **Contact form** with:
  - Name
  - Email
  - Subject
  - Message
  - Submit button
- **Contact information cards**:
  - Email address (clickable link)
  - Phone number (clickable link)
  - Physical address
  - Business hours
- **Social media links** (Facebook, Twitter, Instagram, LinkedIn icons)
- **Google Map placeholder** (iframe-ready location)
- **FAQ section** (Frequently asked questions with answers)

---

## 🎨 CSS Features & Structure

### CSS File: `css/style.css`

The stylesheet includes:

#### 1. **CSS Variables (Custom Properties)**
```css
--primary-color: #007bff (Blue)
--secondary-color: #6c757d (Gray)
--success-color: #28a745 (Green)
--danger-color: #dc3545 (Red)
--warning-color: #ffc107 (Yellow)
--light-bg: #f8f9fa
--dark-text: #212529
--border-color: #dee2e6
--white: #ffffff
--shadow: (box shadow)
--transition: (smooth transitions)
```

#### 2. **Layout Systems**
- **Flexbox** - Used for navigation, headers, and component alignment
- **CSS Grid** - Used for product grids, category grids, and footer
- **Responsive** - Mobile-first design with media queries (768px, 480px breakpoints)

#### 3. **Component Styles**
- **Navigation bar** (sticky, responsive hamburger-ready)
- **Product cards** (with hover effects and badges)
- **Category cards** (with images and descriptions)
- **Forms** (styled inputs, focus states, validation styling)
- **Buttons** (primary, secondary, success, danger, outline variants)
- **Tables** (cart table with proper spacing)
- **Footer** (multi-column, social links)

#### 4. **Effects & Interactions**
- **Hover effects** on cards (lift animation with shadow)
- **Smooth transitions** (0.3s ease on all interactive elements)
- **Focus states** on form inputs (blue border, light shadow)
- **Button animations** (transform on hover)

#### 5. **Responsive Breakpoints**
- **Desktop** (1200px and up)
- **Tablet** (768px to 1199px)
- **Mobile** (below 768px)
- **Small Mobile** (below 480px)

---

## 🔗 Navigation & Page Links

All pages are **interconnected** using relative paths:

- **Home** → `index.html`
- **Products** → `products.html`
- **Categories** → `categories.html`
- **Cart** → `cart.html`
- **Checkout** → `checkout.html`
- **Login** → `login.html`
- **Register** → `register.html`
- **About** → `about.html`
- **Contact** → `contact.html`

Navigation is **consistent** across all pages with:
- Top header with search and cart
- Sticky navigation bar with all main links
- Footer with additional links
- "Active" class on current page link (ready for JavaScript updates)

---

## 📊 Data Attributes & HTML Structure for Future Integration

### Product Cards
All product cards include data attributes for JavaScript integration:

```html
<article class="product-card" data-product-id="P001">
  <div class="product-image">
    <img src="images/products/product-1.jpg" alt="Product Name">
    <span class="product-badge">-20%</span>
  </div>
  <div class="product-info">
    <h3 class="product-name">Product Name</h3>
    <div class="product-rating">⭐ 4.5 (125 reviews)</div>
    <div class="product-price">
      <span>$49.99</span>
      <span class="product-old-price">$62.99</span>
    </div>
    <button class="btn" data-product-id="P001">Add to Cart</button>
  </div>
</article>
```

### Form Fields
All form inputs have meaningful `name` attributes for backend processing:

```html
<input type="email" name="email" required>
<input type="password" name="password" required>
<input type="text" name="full_name" required>
<input type="number" name="quantity" min="1" value="1">
<select name="product_color">...</select>
<input type="text" name="shipping_address">
```

### Cart Containers
Cart page has separate containers for conditional display:

```html
<div id="cart-items-container">...</div>
<div id="empty-cart-message">Your cart is empty</div>
<div id="order-summary">...</div>
```

### Category IDs
Categories have anchor IDs for navigation:

```html
<section id="electronics">...</section>
<section id="fashion">...</section>
<section id="beauty">...</section>
```

---

## 🚀 Future Integration Guide

### Phase 2: JavaScript Integration
The HTML structure is ready for JavaScript to:

1. **Event Listeners:**
   - Add click handlers to "Add to Cart" buttons using `data-product-id`
   - Handle quantity increment/decrement on cart page
   - Toggle "Add to Favorites" functionality

2. **Dynamic Updates:**
   - Update cart count badge dynamically
   - Switch active navigation link based on current page
   - Show/hide "empty cart" message based on items
   - Implement product filtering and sorting

3. **Form Handling:**
   - Validate form inputs before submission
   - Show loading state on submit buttons
   - Handle form data collection using `name` attributes

### Phase 3: Backend Integration
The structure supports backend implementation:

1. **Server-Side Form Processing:**
   - Login form (validate credentials, set session)
   - Registration form (store user in database)
   - Checkout form (create orders)
   - Contact form (save inquiries)

2. **Database Queries:**
   - Fetch product data to populate grid
   - Fetch category data with images
   - Fetch product details on product-details page
   - Fetch cart items for current user
   - Fetch user information on profile page

3. **API Endpoints:**
   - `GET /api/products` - Fetch all products
   - `GET /api/products/:id` - Fetch single product
   - `GET /api/categories` - Fetch categories
   - `POST /api/cart/add` - Add item to cart
   - `POST /api/checkout/place-order` - Create order
   - `POST /api/auth/login` - User login
   - `POST /api/auth/register` - User registration

### Phase 4: Database Schema (Ready to Implement)

The current structure supports these tables:
- **Users** (id, name, email, password, phone, address, city, postal_code)
- **Products** (id, name, description, price, old_price, image, category_id, rating)
- **Categories** (id, name, description, image)
- **Orders** (id, user_id, total_amount, status, shipping_address, payment_method)
- **OrderItems** (id, order_id, product_id, quantity, price)
- **Cart** (id, user_id, product_id, quantity)
- **Reviews** (id, product_id, user_id, rating, comment)

---

## ✅ What's Implemented

### HTML5
- ✅ All 10 pages with semantic HTML elements
- ✅ Proper use of `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- ✅ Form elements with proper labels and attributes
- ✅ Responsive meta viewport tag
- ✅ Data attributes on interactive elements
- ✅ Meaningful class names and IDs
- ✅ Proper image alt attributes

### CSS3
- ✅ CSS Variables for consistent theming
- ✅ Flexbox layouts
- ✅ CSS Grid layouts
- ✅ Responsive design with media queries
- ✅ Hover effects and transitions
- ✅ Form styling with focus states
- ✅ Professional color scheme
- ✅ Consistent typography
- ✅ Card-based component design
- ✅ Shadow effects for depth

### Design
- ✅ Professional & clean layout
- ✅ Responsive on all devices
- ✅ Consistent branding across pages
- ✅ User-friendly navigation
- ✅ Accessible color contrast
- ✅ Proper spacing and padding

---

## ❌ What's NOT Implemented (For Future Phases)

- ❌ JavaScript functionality
- ❌ Backend/Server-side logic
- ❌ Database
- ❌ User authentication (real)
- ❌ Cart calculations
- ❌ Payment processing
- ❌ Form submission
- ❌ Product search/filtering (interactive)
- ❌ API integration

---

## 🖥️ How to Use This Project

### 1. **Open in Browser**
Simply double-click any HTML file or open it with your preferred browser:
```
index.html → Home Page
products.html → Products Listing
```

### 2. **Navigate Between Pages**
Use the navigation menu and links to move between pages.

### 3. **Image Assets**
The project includes locally stored product and category photography plus a
homepage banner photo. Product images use a square (1:1) crop; category cards
use a 3:2 crop to keep the grids aligned. The images are in `images/products/`,
`images/categories/`, and `images/banners/`, so the pages work without a network
connection. Replace them with your own images by updating the relative paths in
the HTML and CSS.

Sample photos are downloaded from Unsplash and saved in the project, so the
website does not depend on a live image URL.

### 4. **Customize Colors**
Edit CSS variables in `css/style.css`:
```css
:root {
  --primary-color: #007bff;  /* Change this */
  --secondary-color: #6c757d; /* And this */
}
```

### 5. **Add Content**
Replace sample products, categories, and text with real content.

---

## 📚 Design Guidelines

### Colors Used
- **Primary Blue** (#007bff) - Main buttons, links, highlights
- **Dark Gray** (#212529) - Text, navigation background
- **Light Gray** (#f8f9fa) - Backgrounds, alternating rows
- **Red** (#dc3545) - Danger buttons, discount badges
- **Green** (#28a745) - Success state
- **Yellow** (#ffc107) - Ratings, warnings

### Typography
- **Font Family:** Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Main headings:** Bold, 32px
- **Product names:** Bold, 18px
- **Body text:** Regular, 14-16px
- **Buttons:** Bold, 16px

### Spacing
- **Section padding:** 40px horizontal, 30px vertical
- **Component gaps:** 20-30px
- **Border radius:** 4-8px (for consistency)
- **Shadow:** Subtle, 0 2px 8px rgba(0,0,0,0.1)

---

## 🔐 Browser Compatibility

This project uses standard HTML5 and CSS3 that works on:
- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📝 Project Submission

### For Web Technology Course Submission:
1. Ensure all 10 HTML pages are present
2. Verify `css/style.css` is linked correctly
3. Check all navigation links work
4. Test responsive design on different screen sizes
5. Ensure no broken image links
6. Review semantic HTML structure
7. Include this README.md file

### Grading Criteria Met:
- ✅ Complete HTML5 structure
- ✅ Professional CSS3 design
- ✅ Responsive layout
- ✅ Semantic HTML elements
- ✅ Consistent navigation
- ✅ Professional appearance
- ✅ All 10 required pages
- ✅ Proper folder organization
- ✅ Ready for JavaScript integration
- ✅ Ready for backend integration

---

## 📞 Support & Notes

- This is a **frontend-only** submission for the current phase
- JavaScript functionality will be added in Phase 2
- Backend and database will be added in Phase 3
- All naming conventions (classes, IDs, data attributes) are chosen to support future integration

---

## 👨‍💻 Code Quality

- **Clean HTML:** No unnecessary divs, semantic elements used properly
- **Organized CSS:** Logical grouping, clear comments, CSS variables for maintainability
- **Readable:** Proper indentation, meaningful names
- **Maintainable:** External CSS, modular component structure
- **Scalable:** Easy to add new pages or components
- **Professional:** Appropriate for a university-level course project

---

**Project Status:** ✅ HTML5 & CSS3 Complete | Ready for JavaScript Phase
**Last Updated:** 2024
**Web Technology Semester Project**
