# GoMarketplace

**GoMarketplace** is an e-commerce application developed during the GoStack bootcamp by @rocketseat. Built with **React Native** and **TypeScript**, this project simulates an online clothing store, offering features such as product listings, shopping cart management, and local storage.

## Features

- **Product Listings**: Displays a list of available products for purchase.
- **Product Details**: Shows detailed information about each product.
- **Shopping Cart**: Allows users to add products to the cart and view selected items.
- **Async Storage**: Stores cart state locally for persistence between sessions.
- **Context API**: Manages global app state, including the shopping cart and user information.

## Screenshots

<div>
  <img src="dashboard.jpeg" width=200 height=400 />
  <img src="cart.jpeg" width=200 height=400 />
</div>

## Getting Started

To get started with the GoMarketplace project, follow these steps:

### Prerequisites

- **Node.js** (version 12 or higher)
- **npm** or **yarn**
- **React Native CLI** (if running the app on a physical device or emulator)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/renatosilveira99/go-marketplace-mobile
   ```

2. **Navigate to the project directory**:
   ```bash
   cd go-marketplace
   ```

3. **Install dependencies**:
   ```bash
   yarn install
   ```
   or
   ```bash
   npm install
   ```

4. **Run the application**:
   - For iOS:
     ```bash
     npx react-native run-ios
     ```
   - For Android:
     ```bash
     npx react-native run-android
     ```

## Usage

- **Browse Products**: Navigate through the product listings to view available items.
- **View Product Details**: Tap on a product to see more information.
- **Add to Cart**: Add products to your shopping cart for purchase.
- **View Cart**: Access the cart to review selected items and proceed to checkout.

## Technologies Used

- **React Native**: Framework for building mobile applications.
- **TypeScript**: Superset of JavaScript for type safety and better development experience.
- **Async Storage**: For persisting data locally on the device.
- **Context API**: For managing global state across the app.
