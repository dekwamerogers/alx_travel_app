# ALX Travel App

The ALX Travel App is a real-world Django application that serves as the foundation for a travel listing platform. This project is designed to demonstrate and equip learners with industry-standard best practices for starting and managing Django-based projects efficiently.

This milestone focuses on setting up the initial project structure, configuring a robust database, and integrating tools to ensure clear API documentation and maintainable configurations.

## About This Milestone

This milestone will teach you to set up a scalable backend, integrate MySQL for database management, and use Swagger for automated API documentation. These foundational steps are critical in preparing the application for future features and seamless team collaboration.

### Key Learning Objectives

* **Scalable Django Backend:** Learn to set up a well-structured and scalable Django project from scratch.
* **Database Integration:** Configure and connect a Django application with a powerful relational database like MySQL.
* **API Documentation:** Integrate `drf-yasg` to automatically generate Swagger/OpenAPI documentation for your APIs, making them easy to understand and consume.
* **Configuration Management:** Use environment variables for sensitive data and application settings, promoting security and maintainability.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* Python 3.8+
* `pip` and `virtualenv`
* MySQL Server
* djangorestframework
* drf-yasg
* django-cors-headers
* celery
* rabbitmq
* django

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/alx_travel_app.git
    cd alx_travel_app
    ```

2. **Create and activate a virtual environment:**

    ```sh
    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate

    # For Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```

3. **Install dependencies:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables:**
    Create a `.env` file in the project root directory. You can copy the example file to get started:

    ```sh
    cp .env.example .env
    ```

    Now, open the `.env` file and update the values for your local environment:


5. **Set up the database:**
    Make sure your MySQL server is running and create a new database for the project.

6. **Run database migrations:**

    ```sh
    python manage.py migrate
    ```

7. **Run the development server:**

    ```sh
    python manage.py runserver
    ```

    The application will be available at `http://127.0.0.1:8000/`.

## API Documentation

Once the server is running, you can access the automatically generated API documentation (Swagger UI) to view and test the available API endpoints.

* **Swagger UI:** <http://127.0.0.1:8000/swagger/>
* **ReDoc:** <http://127.0.0.1:8000/redoc/>
