[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# E-Commerce Back End API 
  
## Description
  
This project is the back end of an e-commerce store, providing a robust API for managing products, categories, and tags. Built with Node.js, Express.js, and Sequelize, it offers functionalities to create, read, update, and delete products, categories, and tags, including associations between them. Seamlessly integrate this back end into your e-commerce application to handle essential data management tasks

## Table of Contents

* [Project Information](#project-information)<br>
* [Installation](#installation)<br>
* [Usage](#usage)<br>
* [Endpoints](#endpoints)<br>
* [Contact Information](#contact-information)<br>
* [Credits](#credits)<br>
* [License](#license)

## Project Information

This project is developed as part of a school assignment for Rutgers University. While external contributions are not expected, this repository serves as a demonstration of my understanding of the concepts covered in the course.

## Installation

1. **Clone the Repository**:<br>
Clone the project's GitHub repository to your computer.
2. **Create a .env File**:<br>
Duplicate the .env.EXAMPLE file in the project's root folder.<br>
Rename the duplicated file to .env.
3. **Configure Database in .env**:<br>
Open the new .env file.<br>
Replace placeholders (example_name, example_username, example_password, example_url) with your actual database information.
4. **Install Dependencies**:<br>
Run npm install to install project dependencies.
5. **Set Up the Database**:<br>
Execute npm run db:migrate to create required database tables.<br>
Optionally, add initial data with npm run seed.
6. **Start the Server**:<br>
Launch the server with npm start.
7. **Access the API**:<br>
The server will be at http://localhost:3001.<br>
Use the API endpoints as described in the project's README.

## Usage

[Instruction Video](https://drive.google.com/file/d/1a3KtZXPKh4Gi679KsPR1310UxlcLi3ey/view)

## Endpoints

The E-Commerce Back End API provides a set of endpoints for managing products, categories, and tags. Below are the available endpoints and their functionalities:

### Products
* Get All Products
    * Endpoint: /api/products
    * Method: GET
    * Description: Fetches all products, including associated category and tags.
* Get a Single Product by ID
    * Endpoint: /api/products/:id
    * Method: GET
    * Description: Fetches a single product by ID, including associated category and tags.
* Create a New Product
    * Endpoint: /api/products
    * Method: POST
    * Description: Creates a new product.
* Update a Product by ID
    * Endpoint: /api/products/:id
    * Method: PUT
    * Description: Updates a product by ID.
* Delete a Product by ID
    * Endpoint: /api/products/:id
    * Method: DELETE
    * Description: Deletes a product by ID.

### Categories
* Get All Categories
    * Endpoint: /api/categories
    * Method: GET
    * Description: Fetches all categories, including associated products.
* Get a Single Category by ID
    * Endpoint: /api/categories/:id
    * Method: GET
    * Description: Fetches a single category by ID, including associated products.
* Create a New Category
    * Endpoint: /api/categories
    * Method: POST
    * Description: Creates a new category.
* Update a Category by ID
    * Endpoint: /api/categories/:id
    * Method: PUT
    * Description: Updates a category by ID.
* Delete a Category by ID
    * Endpoint: /api/categories/:id
    * Method: DELETE
    * Description: Deletes a category by ID.

### Tags
* Get All Tags
    * Endpoint: /api/tags
    * Method: GET
    * Description: Fetches all tags, including associated products.
* Get a Single Tag by ID
    * Endpoint: /api/tags/:id
    * Method: GET
    * Description: Fetches a single tag by ID, including associated products.
* Create a New Tag
    * Endpoint: /api/tags
    * Method: POST
    * Description: Creates a new tag.
* Update a Tag by ID
    * Endpoint: /api/tags/:id
    * Method: PUT
    * Description: Updates a tag by ID.
* Delete a Tag by ID
    * Endpoint: /api/tags/:id
    * Method: DELETE
    * Description: Deletes a tag by ID.

## Contact Information

For any further inquiries, please feel free to reach out to me through the following channels:
* GitHub: [My GitHub Profile](https://www.github.com/BenThere6)
* Email: benjaminbirdsall@icloud.com

I am here to assist you with any questions or feedback you may have. Thank you for your interest!

## Credits

The foundational codebase was sourced from the following repository: [fantastic-umbrella](https://github.com/coding-boot-camp/fantastic-umbrella). This repository served as a starting point for the project, providing valuable insights and inspiration that contributed to the development process. We express our gratitude for the resources made available by the authors of the original codebase.

## License 

[MIT License](https://opensource.org/licenses/MIT)

This code's MIT License allows you to freely use, modify, and share it for any purpose. Please include the original license and copyright notices when sharing.