
# Flask To-Do App

A simple, user-friendly Flask-based To-Do list application. This app allows users to create, update, mark as complete, and delete tasks.

## Features
- Add a new task
- Mark tasks as complete/incomplete
- Delete tasks
- Responsive design using **Semantic UI**

## How to Run the Project Locally

To run this project on your local machine, follow these steps:

### Prerequisites
- Python 3.x installed
- pip (Python package installer)
- Git

### Steps:

1. **Clone the repository**:

   Open your terminal or command prompt and run the following command:

   ```bash
   git clone https://github.com/yourusername/repository-name.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd repository-name
   ```

3. **Create a virtual environment (recommended but optional)**:

   ```bash
   python -m venv venv
   ```

4. **Activate the virtual environment**:

   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. **Install the required dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

6. **Run the Flask application**:

   ```bash
   python app.py
   ```

7. **Access the application**:

   Open your web browser and go to:

   ```
   http://127.0.0.1:5000
   ```

   The application will be up and running on this local server.

## Folder Structure

```
repository-name/
├── app.py                 # Main application file
├── requirements.txt       # Required packages for the project
├── templates/             # HTML templates folder
│   └── base.html
├── static/                # Static files
├── venv/                  # Virtual environment folder (ignored in .gitignore)
```

## Technologies Used

- **Backend**: Flask, SQLAlchemy (ORM), SQLite (Database)
- **Frontend**: HTML, **Semantic UI** for CSS framework
- **Templating Engine**: Jinja2


