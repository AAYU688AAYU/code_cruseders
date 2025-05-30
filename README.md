# Django Social Media Platform

A social media platform built with Django that allows users to create posts, like, comment, and interact with other users.

## Features

- User Registration and Authentication
- User Profile Management
- Create, View Posts
- Like and Comment System
- Responsive Design

## Technologies Used

- Python 3.x
- Django 5.2
- SQLite Database
- HTML/CSS
- JavaScript (for like functionality)

## Setup Instructions

1. Clone the repository:
```bash
git clone <your-repository-url>
cd <repository-name>
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install django
```

4. Apply migrations:
```bash
python manage.py migrate
```

5. Create a superuser (admin):
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

7. Visit http://127.0.0.1:8000/ in your browser

## Project Structure

- `main/` - Main application directory
  - `views.py` - Contains view functions
  - `models.py` - Database models
  - `forms.py` - Form definitions
  - `templates/` - HTML templates
- `website/` - Project settings directory
- `media/` - User uploaded files
- `static/` - Static files (CSS, JS, images)

## Contributing

Feel free to fork the project and submit pull requests.

## License

This project is open source and available under the [MIT License](LICENSE). 