# ORM-E-commerce-Back-End

This application allows a user to manage categories, products, and tags for your e-commerce store. Simplify your online store management and enhance customer experience with easy-to-use endpoints for CRUD operations on essential e-commerce entities.

[Video on how to use this app](https://drive.google.com/file/d/18De30Unm-GifOcm0HCh0gQDyjCao-Jf0/view?usp=sharing)

## Features

- **Categories**: Create, Read, Update, and Delete categories.
- **Products**: Create, Read, Update, and Delete products, with support for associating products with categories and tags.
- **Tags**: Create, Read, Update, and Delete tags, with support for associating tags with products.

## Technologies Used

1. Node.js
2. Express.js
3. Sequelize 

## Getting Started

1. **Clone the repository:**

   git clone git@github.com:chappzach24/ORM-E-commerce-Back-End.git

2. **Install dependencies:**

   cd ORM-E-commerce-Back-End
   npm install

3. **Start MySQL:**

   mysql -u root -p

4. **Source schema.sql:**

   source schema.sql

5. **Quit MySQL:**

   quit

6. .env

    Make sure to add username and password in .env

7. **Seed the database:**

   npm run seed

8. **Start the server:**

   npm start

## API Endpoints:

- Categories: /api/categories
- Products: /api/products
- Tags: /api/tags

## License

This project is licensed under the [MIT License](LICENSE).
