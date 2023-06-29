# Django-Vue E-commerce System Tutorial

This tutorial project demonstrates the implementation of a simple product-based e-commerce system using Django, Django REST Framework, and Vue.js. It is designed to help beginners learn the fundamentals of these frameworks and understand their integration.

## Technologies Used

### Backend

- Python: The programming language used for the backend development.
- Django: A powerful web framework for building web applications with Python.
- Django REST Framework: A toolkit for building APIs using Django.
- Djoser: A Django package providing authentication and user management.

### Frontend

- Vue.js: A JavaScript framework for building user interfaces.
- Vuex: A state management pattern and library for Vue.js applications.
- Bulma: A lightweight CSS framework for styling the frontend.

### Database

- SQLite: A lightweight and file-based relational database used for data storage.

## Features

- Product Management: Allows the creation, retrieval, update, and deletion of products.
- Category Management: Enables the organization of products into categories.
- Add to Cart: Allows users to add products to their cart for later purchase.
- Checkout System: Provides a simple checkout process for users to finalize their orders.

## Getting Started

To set up the project locally, follow these steps:

1. Clone the repository
2. Navigate to the project directory: `cd django-vue-ecommerce-tutorial`
3. Set up the backend:

   - Create a virtual environment named `venv`:

     ```
     python -m venv venv
     ```

   - Activate the virtual environment:

     - On Windows:
       ```
       venv\Scripts\activate
       ```
     - On macOS and Linux:
       ```
       source venv/bin/activate
       ```

   - Install the required Python packages:

     ```
     pip install -r requirements.txt
     ```

   - Apply database migrations:

     ```
     python manage.py migrate
     ```

   - Start the Django development server:
     ```
     python manage.py runserver
     ```

4. Set up the Frontend:

   - Navigate to the frontend directory:

     ```
     cd store_vue
     ```

   - Install the frontend dependencies:

     ```
     npm install
     ```

   - Start the Vue development server:

     ```
     npm run serve
     ```

5. Access the application by visiting `http://localhost:8080` in your web browser.

## Special Shout-Out

Special Shout-out to : https://github.com/SteinOveHelset/ for guiding me through this tutorial and giving proper insights
