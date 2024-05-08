# Grocery-Store-Application

The Grocery Store App is a multi-user web application that allows users to browse and purchase grocery items from various sections. It provides an intuitive interface for users to explore products, add them to their shopping cart, and complete the checkout process. The app also includes an admin interface for managing sections and products.

## Features

### User Features
- User registration and login functionality
- Browse products by sections/categories
- Search for specific products based on name, price, or other attributes
- View product details, including name, price, manufacture date, and available quantity
- Add products to the shopping cart
- Update quantities or remove products from the shopping cart
- Proceed to checkout and complete the purchase
- View order history and status

### Admin Features
- Admin login functionality
- Manage sections/categories (create, edit, remove)
- Manage products within each section/category (create, edit, remove)
- View and manage user accounts
- Generate reports on product engagement and sales trends

## Technologies Used

- **Flask**: Python web framework for building the application backend
- **Jinja2**: Templating engine for generating dynamic HTML pages
- **Bootstrap**: CSS framework for creating responsive and visually appealing user interfaces
- **SQLite**: Lightweight database for storing sections, products, user information, and order data
- **HTML/CSS**: Markup and styling for the web pages
- **JavaScript**: Client-side scripting for enhanced interactivity and functionality

## Getting Started

### Prerequisites
- Python 3.x
- pip (Python package installer)

### Installation

1. Clone the repository:
2. Navigate to the project directory:
  `cd grocery-store-app` 
4. Create a virtual environment (optional but recommended):
  `python -m venv venv`
6. Activate the virtual environment:
- For Windows:
  ```
  venv\Scripts\activate
  ```
- For macOS and Linux:
  ```
  source venv/bin/activate
  ```

5. Install the required dependencies:
   `pip install -r requirements.txt`
6. Set up the database:
  `python setup_db.py`
7. Run the application:
  `python app.py`

8. Access the application in your web browser at `http://localhost:5000`.

## Project Structure

- `app.py`: Main Flask application file
- `models.py`: Database models and SQLite configuration
- `routes.py`: Application routes and view functions
- `templates/`: Directory containing Jinja2 HTML templates
- `base.html`: Base template for consistent layout across pages
- `index.html`: Home page template
- `login.html`: User login template
- `register.html`: User registration template
- `admin/`: Directory for admin-related templates
 - `dashboard.html`: Admin dashboard template
 - `sections.html`: Section management template
 - `products.html`: Product management template
- `static/`: Directory for static assets
- `css/`: CSS stylesheets
- `js/`: JavaScript files
- `images/`: Image files
- `requirements.txt`: List of required Python packages
- `setup_db.py`: Script to set up the database and create necessary tables
- `README.md`: Project documentation and instructions

## Contributing

Contributions to the Grocery Store App are welcome! If you find any bugs, have suggestions for improvements, or would like to add new features, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Make your changes in the new branch.
4. Write tests to ensure the changes work as expected and maintain code quality.
5. Commit your changes and push them to your forked repository.
6. Submit a pull request to the main repository, describing your changes in detail.

Please ensure that your code follows the project's coding conventions and style guidelines.

## License

The Grocery Store App is open-source software licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as per the terms of the license.

## Contact

If you have any questions, suggestions, or feedback, please feel free to contact the project maintainer:

- Name: [Your Name]
- Email: [your-email@example.com]
- GitHub: 

We appreciate your interest in the Grocery Store App and look forward to your contributions!
