# TASK 1: Wireframing & Low-Fidelity Design Documentation
**Project:** QuickBite - Food Delivery App  
**Deliverable Type:** Low-Fidelity Wireframes, User Flow Specification & Interactive Prototype  
**Submission Format:** SVG Artboards (ready for Figma / Adobe XD import), Interactive Web Prototype (`index.html`), and Design System Specs.

---

## 1. Project Overview & Scope
- **App Concept:** QuickBite is a modern, fast, and intuitive food delivery mobile application designed for quick order turnaround, clear navigation, and real-time delivery transparency.
- **Target Device:** Mobile iOS & Android (Base Artboard: 390px × 844px — iPhone 13/14/15 standard viewport).
- **Core User Flow:** 
  `Splash / Location Discovery` ➔ `Home Feed & Categories` ➔ `Restaurant Details & Menu Filter` ➔ `Cart & Smart Checkout` ➔ `Live Order Tracker (Real-Time Status)`

---

## 2. Low-Fidelity Wireframe Screen Breakdown

### Screen 1: Home & Discovery Feed
- **Header:** Location selector dropdown (e.g. "Deliver to: Home, 12th St..."), Search bar ("Search burgers, sushi, tacos..."), Notification / Profile avatar.
- **Top Offer / Promotion Banner:** Low-fi dashed banner placeholder (e.g. 30% Off First Order).
- **Cuisine Categories (Horizontal scroll chips):** All, Pizza, Burger, Asian, Mexican, Healthy, Drinks.
- **Curated Sections:**
  - "Popular Near You" cards (Food thumbnail placeholder, Restaurant name, Rating badge, Delivery time & fee).
  - "Top Rated Restaurants" list view with tags (Free Delivery, Vegan options).
- **Navigation Bar:** Fixed bottom bar with 4 standard tabs: Home, Search/Explore, Orders, Profile.

### Screen 2: Restaurant Menu & Item Detail
- **Header:** Back button, Restaurant Banner image placeholder, Favorite (heart) button, Share button.
- **Restaurant Info Bar:** Restaurant Name ("Burger Craft & Co."), Rating (4.8 ★ 1.2k reviews), Delivery time (25-35 mins), Delivery tag ($1.99 Fee).
- **Menu Category Tabs:** Sticky sub-navigation (Burgers, Sides, Beverages, Desserts).
- **Menu Items List:**
  - Card with Dish Title, Brief Description placeholder (2 lines), Price ($11.49), Dish thumbnail placeholder, "ADD" / Counter CTA.
- **Floating Bottom Bar:** Sticky summary bar when items are added: "1 Item | $11.49" + "View Cart" CTA.

### Screen 3: Cart & Checkout
- **Header:** "My Cart", Back button, Clear cart button.
- **Delivery Address Summary:** Quick address selector pill with "Change" action.
- **Order Items List:**
  - Line items with customizable quantity stepper (`-` `1` `+`), item extras/notes, and item total.
- **Promo Code Box:** Input box + "Apply" button.
- **Bill Summary Breakdown:**
  - Subtotal
  - Delivery Fee
  - Taxes & Platform Service Fee
  - Total Amount (Bold)
- **Payment Method Selector:** Cards / Digital Wallet / Cash on Delivery.
- **Primary CTA:** "Place Order ($18.45)" button.

### Screen 4: Live Order Tracking
- **Header:** "Order Status", Back to Home button, Order ID (#QB-8942).
- **Live Status Map / Visual Area:** Placeholder illustration map with rider pin, restaurant pin, and route path.
- **Estimated Arrival Card:** "Estimated Delivery: 20-25 mins", progress bar with status steps:
  1. Order Placed (Done)
  2. Kitchen Preparing (In Progress)
  3. Rider on the way (Upcoming)
  4. Delivered (Upcoming)
- **Rider Info Card:** Driver thumbnail, Name ("Alex M."), Rating, "Call" and "Message" buttons.
- **Action Buttons:** "View Receipt" & "Need Help / Support".

---

## 3. Wireframe Visual Language & Standards
- **Monochrome & Greyscale Palette:** True to low-fidelity wireframing standards (no final brand colors; shades of grey #F3F4F6, #E5E7EB, #9CA3AF, #1F2937).
- **Typography Hierarchy:** Clean geometric sans-serif (Inter / System font).
- **Placeholders:** Box with diagonal cross or standard image icon for media assets.
- **Standardized Touch Targets:** Minimum 44px height for interactive buttons and tap areas.

---

## 4. How to Import into Figma / Adobe XD
1. All screen SVG files (`screen-1-home.svg`, `screen-2-restaurant.svg`, `screen-3-cart.svg`, `screen-4-tracking.svg`) can be dragged directly into a Figma canvas or Adobe XD workspace.
2. They are 100% vector-based, clean nested groups with editable text nodes and auto-alignable frames.
3. You can also view the interactive prototype by opening `index.html` in any browser.
