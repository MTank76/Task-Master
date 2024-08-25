# Task-Master
Task Master is a dynamic and vibrant ToDo web app built with Django, designed specifically for engineers to ensure they never forget a task or miss a deadline. With its sleek and user-friendly interface, Task Master helps engineers manage their tasks efficiently and stay organized in the fast-paced world of engineering. to ensure they never forget a task or miss a deadline. 

## Requirements

- Python 3.8 or higher
- Django 4.0 or higher
- SQLite3 (included with Python)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/task-master.git
   cd task-master
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional, for admin access):**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

7. **Access the application:**

   Open your web browser and go to `http://127.0.0.1:8000` to start using Task Master.

## Usage

- **Dashboard:** View and manage your tasks from the dashboard.
- **Add Task:** Click on "Add Task" to create a new task, set a deadline, and assign a priority level.
- **Edit Task:** Modify existing tasks by selecting them from the list.
- **View Tasks:** Use the customizable views to see tasks by day, week, or project.
- **Code Snippets:** You can enhance productivity by seamlessly adding, managing, and referencing code snippets directly within your tasks.

## Contributing

If you'd like to contribute to Task Master, please fork the repository and submit a pull request with your changes. For bug reports or feature requests, open an issue on GitHub.
