# Customer 360 Pipeline

A simple Django application for managing customer records and tracking customer interactions across channels such as phone, SMS, email, letter, and social media.

## Features

- Add customer profiles
- View a list of customers
- Log customer interactions
- Review recent customer interaction summaries
- Basic dashboard-style overview of interaction activity

## Project Structure

- `customer360/` – Django project app containing models, views, URLs, and templates
- `static/` – CSS assets
- `db.sqlite3` – local SQLite database
- `manage.py` – Django management entry point

## Requirements

- Python 3.10+
- Django 5.2+

## Setup

1. Open a terminal in the project root.
2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install django
   ```

4. Run database migrations:

   ```bash
   python manage.py migrate
   ```

5. Start the development server:

   ```bash
   python manage.py runserver
   ```

6. Open the app in a browser at:

   ```text
   http://127.0.0.1:8000/
   ```

## Common Commands

- Create migrations:

  ```bash
  python manage.py makemigrations
  ```

- Apply migrations:

  ```bash
  python manage.py migrate
  ```

- Start the app:

  ```bash
  python manage.py runserver
  ```

- Open Django shell:

  ```bash
  python manage.py shell
  ```

## Notes

This project uses SQLite for local development, so no external database service is required for basic setup.
