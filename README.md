Welcome to the EasyShop E-Commerce Capstone Project repository! This project is a comprehensive e-commerce website featuring a Spring Boot API backend and a MySQL database for data storage. EasyShop empowers users to log in, explore products across diverse categories and prices, add items to a shopping cart, and seamlessly check out to place orders. Throughout the development phases, the focus is on addressing existing bugs in the API code and introducing new features, all while ensuring the backend operates seamlessly.



Built With

- Programming Languages:

  - Backend: Java, SQL

  - Frontend: HTML, CSS, JavaScript

- Tools:

  - IntelliJ (Maven)

  - Spring Boot Framework

  - MySQL Workbench

  - Postman



Getting Started:

1. Clone this repository to your local machine.

2. Open the project in your preferred Java IDE.

3. Set up the MySQL database using the provided script.

4. Run the Spring Boot API.

5. Access the front-end web application to test your changes.

6. Testing: Utilize Postman for API endpoint testing, and a frontend web application is available for testing API integration with the web.



Phase 1 - CategoriesController:

- Implement methods in CategoriesController class.

- Only administrators can insert, update, or delete a category.

- Implement code in MySqlCategoriesDao.

- Utilized appropriate annotations in the controller.



Phase 2 - Fix Bugs:

- Resolved bugs in the ProductsController:

  - Bug 1: Fixed incorrect search results.

  - Bug 2: Resolved product duplication issues.



Phase 3 - Shopping Cart - Feature:

- Implement shopping cart functionality, enabling logged-in users to add items to their shopping cart.

- Shopping cart data is stored in the database.

- Implement methods in ShoppingCartController for required REST actions:

  - GET: Returns the shopping cart for the current user.

  - POST: Adds a new product to the shopping cart.

  - DELETE: Clears the shopping cart.

  - PUT: Updates the quantity of a product in the cart.

- Implement code in ShoppingCartDao and MySqlShoppingCartDao.


