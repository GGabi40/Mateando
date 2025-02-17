# Mateando

<img src="https://raw.githubusercontent.com/ggabi40/Mateando/main/src/static/assets/img/LOGO-footer.png" alt="Mateando Logo" width="200">

## Description

This project is an **Online Store** developed from design to database, using **Flask**, **Python**, **HTML**, **CSS**, and **JavaScript**. It was created as part of a university programming assignment. The application provides a complete shopping experience with functionalities such as form validation, email sending when necessary, and a shopping cart system for users.

## Features

- **Product Catalog**: Display products with their descriptions, prices, and images.
- **Shopping Cart**: Add, update, and remove items from the cart.
- **Form Validation**: Ensure that all forms (such as registration, login, checkout) are properly filled out before submission.
- **Email Notifications**: Sends emails to users when necessary (e.g., order confirmation).
- **Responsive Design**: Fully responsive layout for different screen sizes using **CSS**.
- **User Authentication**: Users can register and log in to their accounts.

## Technologies Used

- **Flask**: Backend framework to build the web application.
- **Python**: Programming language for the server-side logic.
- **HTML**: Markup language used for the structure of the web pages.
- **CSS**: Styling language used for layout and visual design.
- **JavaScript**: Used for interactivity on the frontend, including shopping cart updates.
- **SQLAlchemy**: ORM used to interact with the SQLite database (or other supported databases).
- **SQLite**: Database used to store user data, orders, and product information.


## How to run it locally

Follow these steps:

1. Clone the repository:

        git clone https://github.com/ggabi40/Mateando.git

2. Install the required dependencies:

        pip install -r requirements.txt

3. Run the Flask application:

        python app.py

## Usage

- Users can browse the product catalog, add items to the cart, and proceed to checkout.
- The forms will validate input and provide feedback to the user.
- **Admin Panel**: Administrators have access to a control panel where they can:
  - Add new products with details such as name, description, price, and image.
  - Edit or delete existing products from the catalog.
- **User Dashboard**: Each registered user has a personal control panel where they can:
  - Update their account details, such as email and password.
  - Delete their account if they want to.
