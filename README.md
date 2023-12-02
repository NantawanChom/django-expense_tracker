# Expense Tracker

Expense Tracker is a simple Django web application that helps you track your expenses. It allows you to add, edit, and delete expense entries. The project uses PostgreSQL as the database and Firebase for real-time updates on the frontend.

## Features

- Add new expenses with a description, amount, and date.
- Edit existing expenses to update details.
- Delete expenses you no longer want to track.
- Real-time updates on the frontend using Firebase.

## Technologies Used

- Django: Web framework for backend development.
- PostgreSQL: Database for storing expense data.
- Firebase: Real-time updates for the frontend.
- Python: Programming language used for Django backend.
- HTML, CSS, and JavaScript: Frontend development.
- python-decouple and dj-database-url: For managing environment variables and database configurations.

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/expense_tracker.git
   cd expense_tracker
   ```

2. **Install dependencies**

    ```bash
    pip install -r requirements.txt
    ```

3. **Create and apply database migrations (setup value in .env file)**

    ```bash
    python manage.py migrate
    ```

4. **Run the development server**

    ```bash
    python manage.py runserver
    ```
    The application will be available at http://localhost:8000.
