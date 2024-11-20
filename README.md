# project_react_catalog
Create a single-page application (SPA) using React.js that displays a list of products in a catalog format. 
Users should be able to: 
*** View a list of products with details. 
*** Filter products based on categories. 
*** Search for products by name. 
*** View detailed information about a selected product. 


Product Catalog Application 
A simple React-based product catalog application with functionalities like filtering, searching, sorting, and adding products to a cart.

Features
Product Filtering: By category and price range.
Search: Find products by name.
Sorting: Sort products by price (ascending or descending).
Add to Cart: Add products to the cart and view them.
Reusable Components: Built using modular, reusable components like ProductList, ProductItem, SearchBar, and CategoryFilter.
Installation and Setup
Prerequisites
Node.js (v14 or higher) installed.
npm or yarn installed.
Steps to Run Locally
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/product-catalog.git
Navigate to the project directory:
bash
Copy code
cd product-catalog
Install dependencies:
bash
Copy code
npm install
Start the development server:
bash
Copy code
npm start
Open the application in your browser:
arduino
Copy code
http://localhost:3000
Libraries and Tools Used
React: Frontend framework.
React Router: For navigation and routing.
CSS: For styling components.
React Hooks: For state management (useState, useEffect).
Challenges Faced
State Management for Cart:
Initially struggled to share the cart state across components. Resolved by passing state and handlers via props.
Price Filtering Logic:
Implemented dynamic filtering logic using filter and sort to handle both price ranges and ascending/descending order.
Optional Enhancements
Sorting by Price: Implemented ascending/descending sorting for a better user experience.
Dynamic Cart View: Users can view and manage their cart contents in real-time.
Screenshots
Home Page

Product Filtering

Cart

Future Enhancements
Add user authentication for managing personalized carts.
Introduce pagination for large product lists.
Integrate a backend API for product data.
