# Personal Blog with Flask

The Personal Blog with Flask is a web application that allows users to create, view, and manage blog posts. Built using Python with Flask and SQLite, this project serves as a simple yet functional personal blogging platform.

## Project Structure

- **app/__init__.py**: Initializes the Flask application.
- **app/models.py**: Defines the data models, including the User and Post classes.
- **app/routes.py**: Implements the routes and views for the application.
- **app/templates/**: Contains HTML templates for rendering pages.
- **venv/**: Virtual environment folder for Python dependencies.
- **.gitignore**: Specifies files and folders to be ignored by version control.
- **config.py**: Configuration file for the Flask application.
- **run.py**: Script to run the Flask application.

## Setup and Usage

1. **Create Virtual Environment**:
   - Create a virtual environment using `python -m venv venv`.
   - Activate the virtual environment.

2. **Install Dependencies**:
   - Install required Python packages using `pip install -r requirements.txt`.

3. **Database Setup**:
   - The SQLite database will be created automatically when the application runs.

4. **Run the Application**:
   - Execute `python run.py` to start the Flask development server.

5. **Access the Blog**:
   - Open your browser and go to `http://127.0.0.1:5000/` to access the blog.

## Features

- User registration and authentication.
- Create, edit, and delete blog posts.
- View all blog posts or filter by author.
- Simple and responsive user interface.

## Enhancements and Customization

Feel free to customize and enhance the project:
- Add features like comments and categories.
- Implement Markdown support for blog post content.
- Improve the user interface with additional styling.

## Dependencies

- **Flask**: Web framework for Python.
- **SQLite**: Lightweight relational database.
- **Flask-WTF**: Flask extension for handling web forms.

## Contributing

Contributions are welcome! If you find issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
