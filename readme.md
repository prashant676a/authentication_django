# Django Authentication API with Simple JWT

This project is a Django REST API for user authentication using Simple JWT (JSON Web Token) for token-based authentication.

## Getting Started

### Prerequisites

- Python 3.x (https://www.python.org/downloads/)
- pip (https://pip.pypa.io/en/stable/installation/)


### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/prashant676a/authentication_django.git

2. Navigate to the project directory:

    ```bash
    cd authentication_django/djangoauthapi

3. Create a virtual Environment(recommended)
    ```bash
    python -m venv venv
    source venv/bin/activate (for mac and linux)
    venv\Scripts\activate (for windows)

4. Install the required packages
    ```bash
    pip install -r requirements.txt

5. Apply Database Migrations
    ```bash
    python manage.py migrate

6. Run the Development Server
    ```bash
    python manage.py runserver


### API endpoints
You can find the API endpoint URLs in the included Postman file located in the project folder.

### Authentication
- All endpoints except register and login require authentication with a valid JWT token.
- Refer to the Simple JWT documentation for token generation and usage: https://django-rest-framework-simplejwt.readthedocs.io/