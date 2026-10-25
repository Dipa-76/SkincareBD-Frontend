# Glow & Care — Skincare Storefront

A responsive, multi-page skincare e-commerce frontend demo built with HTML5, CSS3, and Vanilla JavaScript. The project demonstrates the core frontend functionality of a skincare shopping website, including product browsing, search and filtering, shopping cart management, and form validation.

This project was developed as a frontend practice project inspired by skincare e-commerce websites.

## Project Overview

Glow & Care provides a clean and user-friendly shopping interface where users can browse skincare products, explore product details, manage their shopping cart, and interact with checkout and contact forms.

The project focuses on frontend development fundamentals, responsive web design, JavaScript-based interactions, and browser-based state management. Its structure also provides a foundation for future integration with a backend REST API and database.

## My Frontend Development Work

The frontend implementation includes:

- Developed a multi-page skincare storefront using HTML, CSS, and Vanilla JavaScript.
- Created page layouts for the home page, shop, product details, shopping cart, checkout, about, and contact sections.
- Implemented product rendering using structured JavaScript product data.
- Added product search, category filtering, and sorting functionality.
- Implemented shopping cart interactions, including adding products, updating quantities, removing items, and calculating the subtotal.
- Used browser `localStorage` to preserve shopping cart data across page refreshes.
- Added client-side form validation for checkout and contact forms.
- Organized the project into separate HTML, CSS, and JavaScript files for easier maintenance and future development.
- Applied responsive styling to support different screen sizes.

## Pages and Functionality

### 1. Home Page
- Main storefront layout with promotional content.
- Skincare category sections.
- New arrivals and best-selling product sections.
- Navigation to other pages of the website.

### 2. Shop Page
- Product listing with product names, categories, and prices.
- Search products by text.
- Filter products by category.
- Sort products using available sorting options.

### 3. Product Details Page
- Displays information about an individual product.
- Provides an option to add the selected product to the shopping cart.

### 4. Shopping Cart
- Displays products added to the cart.
- Supports quantity updates and item removal.
- Calculates the cart subtotal.
- Displays the cart item count through the shared frontend functionality.

### 5. Checkout Page
- Provides a checkout form interface.
- Performs client-side input validation.
- Demonstrates the frontend flow for collecting order details.

### 6. About Page
- Provides an introduction to the storefront and its purpose.

### 7. Contact Page
- Provides a contact form interface.
- Validates user input on the client side.

## Key Features

- Responsive multi-page frontend layout.
- Product display using structured JavaScript data.
- Product search, category filtering, and sorting.
- Add-to-cart functionality.
- Shopping cart quantity management and item removal.
- Automatic subtotal calculation.
- Cart persistence using browser `localStorage`.
- Client-side checkout and contact form validation.
- Reusable JavaScript functionality shared across pages.
- No frontend framework or package installation required.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure, content, and forms |
| CSS3 | Styling, layouts, and responsive design |
| Vanilla JavaScript | Product rendering, search, filtering, sorting, and cart interactions |
| Browser localStorage | Persisting shopping cart data locally |
| Git and GitHub | Version control and project hosting |

## Project Structure

```text
SkincareBD-Frontend/
├── index.html
├── shop.html
├── product.html
├── cart.html
├── checkout.html
├── about.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   ├── data.js
│   ├── main.js
│   ├── shop.js
│   ├── product.js
│   ├── cart.js
│   └── checkout.js
└── README.md
```

### Main Files

- `index.html` — Home page and main storefront layout.
- `shop.html` — Product listing, search, filtering, and sorting interface.
- `product.html` — Individual product details.
- `cart.html` — Shopping cart interface.
- `checkout.html` — Checkout form.
- `about.html` — About section.
- `contact.html` — Contact form.
- `css/style.css` — Shared styling and responsive layout.
- `js/data.js` — Sample product data.
- `js/main.js` — Shared frontend interactions and cart helpers.
- `js/shop.js` — Shop page search, filtering, and sorting.
- `js/product.js` — Product details functionality.
- `js/cart.js` — Cart rendering and quantity management.
- `js/checkout.js` — Checkout form validation.

## How to Run Locally

### Prerequisites

- A web browser such as Google Chrome.
- Visual Studio Code or another code editor.
- Python installed if using the local server method below.

### Run Using the Terminal

1. Clone the repository or download the project files.
2. Open the project folder in Visual Studio Code.
3. Open **Terminal → New Terminal**.
4. Navigate to the project directory:

   ```powershell
   cd C:\skincarebd-project
   ```

5. Start a local HTTP server:

   ```powershell
   python -m http.server 8000
   ```

6. Open the following address in your browser:

   `http://localhost:8000`

7. Stop the local server by pressing `Ctrl + C` in the terminal.

If the `python` command is not recognized, try:

```powershell
py -m http.server 8000
```

Python is used only to serve the static frontend files locally. The website itself is built with HTML, CSS, and JavaScript.

## Current Limitations

- This is a frontend-only demonstration project; no backend API or database is connected.
- Product names, prices, product information, and contact details are sample content and are not verified live inventory.
- Product images use remote Unsplash URLs and require an internet connection.
- Shopping cart data is stored in the current browser using `localStorage`.
- The checkout form does not create a real order or process payments.
- The contact form does not send messages to a server.
- User authentication, account management, and order history are not implemented.

## Future Enhancements

- Connect the frontend to a backend REST API using JavaScript `fetch()`.
- Store products, inventory, users, and orders in a database.
- Implement secure user registration and authentication.
- Add server-side checkout processing and order management.
- Integrate a payment gateway when supported by a backend.
- Improve accessibility, automated testing, and deployment workflows.

## Learning Outcomes

This project provides practical experience with:

- Structuring multi-page websites using HTML.
- Building responsive layouts with CSS.
- Manipulating page content using JavaScript.
- Working with arrays and objects to manage product data.
- Implementing search, filtering, sorting, and cart logic.
- Using browser `localStorage` for client-side persistence.
- Organizing frontend code into maintainable files.
- Using Git and GitHub to manage and publish a project.

## Author

**Dipa-76**

GitHub: [https://github.com/Dipa-76](https://github.com/Dipa-76)

Project Repository: [SkincareBD-Frontend](https://github.com/Dipa-76/SkincareBD-Frontend)

## Disclaimer

Glow & Care is an independent frontend learning and practice project inspired by skincare shopping websites. It is not the official SKIN CARE BD website and is not affiliated with or endorsed by SKIN CARE BD. Product names, prices, images, and other sample content are provided for demonstration purposes only.
