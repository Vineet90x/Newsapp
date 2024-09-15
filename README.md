# NewsApp - Django Application

This is a **Django-based News Application** that allows users to readnews articles. 

## Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: SQLite (can be configured to use PostgreSQL or MySQL)
- **Templates**: Django Templating Engine

## Installation

### Prerequisites

- Python 3.x
- Django 4.x
- Git

### Setup Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/NewsApp.git
    ```

2. Navigate to the project directory:

    ```bash
    cd NewsApp
    ```

3. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On MacOS/Linux:
        ```bash
        source venv/bin/activate
        ```

5. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

6. Run migrations:

    ```bash
    python manage.py migrate
    ```

7. Create a superuser (for admin access):

    ```bash
    python manage.py createsuperuser
    ```

8. Start the development server:

    ```bash
    python manage.py runserver
    ```

9. Open your browser and visit `http://127.0.0.1:8000` to access the application.


