# TASK MASTER - Flask To-Do List Application

This is a simple to-do list web application built using Flask and SQLAlchemy.

## Installation

1. Clone this repository to your local machine:

    `git clone <repository_url>`

2. Navigate to the project directory:

    `cd <project_directory>`

3. Install the required dependencies:

    `pip install -r requirements.txt`

## Usage

1. Run the Flask application:

    `python app.py`

2. Open your web browser and go to [http://localhost:5000](http://localhost:5000).

3. You can add tasks by typing them into the input field and pressing "Add Task". Tasks can be marked as completed by clicking the checkbox next to them.

4. To delete a task, click the "Delete" button next to it.

5. To update a task, click the "Update" button next to it and edit the task content in the provided input field.

## File Structure

-   `app.py`: Contains the Flask application code.
-   `templates/`: Contains HTML templates for rendering the web pages.
-   `test.db`: SQLite database file to store tasks.

## Dependencies

-   Flask
-   Flask-SQLAlchemy

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
