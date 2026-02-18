# React Product Catalog
A fully-featured React Product Catalog with shopping cart and favorites functionality. This project demonstrates a modern interface with dynamic product listings, sorting, pagination, search, and theme switching.

# Demo Preview
  - [**Phone-shop Demo Link**](https://tvoypervy.github.io/phone-shop/)

# Design
  **The project is implemented according to the following designs:**
  - [Original Design](https://www.figma.com/design/xMK2Dy0mfBbJJSNctmOuLW/Phone-catalog--V2--Rounded-Style-1?node-id=0-1&p=f&t=tPHUyxIcmhvQUN6b-0)
  - Project have also dark theme

# Technologies Used
  - React (with TypeScript)
  - React Router DOM for routing
  - React Context for state management
  - CSS Modules & SCSS for styling
  - ESLint & Prettier for code formatting
  - LocalStorage for persisting cart and favorite
  - Skeleton Loader
  - Theme switching (light/dark)
  - Responsive design for mobile and desktop screens

# Features
## Home Page
  - Image slider with automatic and manual navigation
  - "Brand new" block showing newest products by year
  - "Shop by category" block: Phones, Tablets, Accessoires
  - "Hot Prices" block with the biggest discount
## Product Pages
  - Separate pages for /phones, /tablets, /accessoires
  - Sorting: New-est, Alphabetic-al, Cheap-est
  - Pagination and items-per-page selector
  - Product search with debounce and URL sync
  - Loader during data fetch, error handling, and empty states
## Product Details Page
  - Product information: images, available colors and capacities
  - Technical specifications and description
  - "You may also like" block
  - Breadcrumbs navigation
  - Browser-like Back button
## Shopping Cart
  - Add and emove products, manage quantity
  - Automatic calculation of total amount and quantity
  - Persist cart in LocalStorage
  - Modal confirmation for checkout
$$ Favorites Page
  - Add and remove products to favorites
  - Display favorites count in the header
  - Persist favorites in LocalStorage
## Themes & Other Features
  - Light/dark theme switching
  - Sticky header with:
      - logo
      - navigation
      - cart
      - favorites
  - Footer with GitHub link and "Back to Top" button
  - Smooth hover effects and image scaling NotFoundPage for unknown URLs
# Getting Started
  1. Clone the repository
     ```
     git clone https://github.com/tvoypervy/phone-shop
     ```
  2. Install dependencies
     ```
     npm install
     ```
  3. Run the project
     ```
     npm start
     ```
