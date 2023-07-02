# mult-vendor-Ecommerce-Project

# Steps

1. Install Tools
   a. VS Code editor
   b. VS Code extension: prettier formatter, enSlint, ES7/React/React Native Code Snippets, Setting up default terminal and code formatter
   c. Chrome brownser
   d. Node js
   e. Git
2. create-react-app
3. create git repository
4. List Products
   1. create products array
   2. add product images
   3. render products
   4. style products
5. add routing
   1. npm i react-router-dom
   2. create route for home screen (page)
   3. create router for product screen (page)
6. Create Node.js Server

   1. Run npm init in root folder
   2. update package.json set type: module
   3. add .js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server.js
   7. require express
   8. create route for / return backend is ready
   9. move products.js from frontend to backend
   10. create route for /api/products
   11. return products
   12. npm start

7. Fetch Products From Backend

   1. Set proxy in package.json
   2. npm install axios
   3. Use state hook
   4. use effect hook
   5. use reducer hook

8. Manage state by Reducer hooks

   1. Define reducer
   2. update fetch data
   3. get state from useReducer
   4. npm install use-reducer-logger --force help debug state and fix issues

9. Add bootstrap UI Framework

   1. npm install react-bootstrap bootstrap
   2. npm i react-router-bootstrap
   3. update App.js

10. Create Product and Rating Components

    1. Create Rating Component
    2. Create Product component
    3. Use Rating component in Product component
    4. import font awasome to index.html above the title

11. Create Product Details Screen

    1. fetch product from backend
    2. create 3 columns for image, info and action

12. Create Loading and Message Components

    1. create loading component
    2. use the spinner component
    3. create message component
    4. create utils file to define getError function

13. Add to Cart
    1. Create React Context
    2. define reducer
    3. create store provider
    4. implement add to cart button click handler
