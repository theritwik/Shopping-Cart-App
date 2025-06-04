# Shopping Cart Application

A modern e-commerce shopping cart built with React, Redux Toolkit, and Tailwind CSS.

![Shopping Cart Demo](public/logo.png)

## Features

- 📱 Responsive design that works on desktop and mobile
- 🛍️ Browse products fetched from Fake Store API
- 🛒 Add/Remove products to/from cart
- 💳 Cart management with Redux Toolkit
- 🎯 Real-time cart total calculation
- 🎨 Modern UI with Tailwind CSS
- 🔔 Toast notifications for cart actions

## Tech Stack

- React.js
- Redux Toolkit for state management
- React Router for navigation
- Tailwind CSS for styling
- React Hot Toast for notifications
- React Icons for UI icons
- Fake Store API for product data

## Getting Started

### Prerequisites

- Node.js (v12 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone [repository-url]
```

2. Navigate to the project directory
```bash
cd shopping-cart
```

3. Install dependencies
```bash
npm install
```

4. Start the development server
```bash
npm start
```

The application will start running at `http://localhost:3000`

## Project Structure

```
src/
├── components/         # Reusable UI components
│   ├── CartItem.jsx   # Cart item component
│   ├── Navbar.jsx     # Navigation bar
│   ├── Product.jsx    # Product card
│   └── Spinner.jsx    # Loading spinner
├── pages/             # Page components
│   ├── Cart.jsx       # Cart page
│   └── Home.jsx       # Home/Products page
├── redux/             # Redux state management
│   ├── Store.js       # Redux store configuration
│   └── Slices/        # Redux slices
│       └── CartSlice.js # Cart state management
├── App.jsx            # Main app component
└── index.js          # Entry point
```

## Features in Detail

### Home Page
- Displays a grid of products
- Each product shows:
  - Product image
  - Title
  - Brief description
  - Price
  - Add to Cart/Remove from Cart button

### Cart Page
- Lists all items added to cart
- Shows total items and total amount
- Option to remove items from cart
- Checkout button

### Navigation
- Persistent navbar with:
  - Home link
  - Cart icon with item count
  - Responsive design

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
