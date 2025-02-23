# Project Installation

## Requirements
- Python 3.x
- pipenv

## Setup Instructions

1. Clone the repository `https://github.com/delwarrz/Module25Assignment.git`.
2. Navigate to the project directory:
   ```
   cd Module25Assignment
   ```
3. Install dependencies:
   ```
   pipenv install
   ```
4. Activate the virtual environment:
   ```
   pipenv shell
   ```
5. Run migrations:
   ```
   python manage.py migrate
   ```
6. Start the server:
   ```
   python manage.py runserver
   ```
