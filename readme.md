
# BookLoom 📚

**BookLoom** is a Django-based web application for managing a list of books. The project allows users to view, add, and manage books using templates for the frontend and SQLite as the database.

## Features ✨
- Add, update, and delete books from the list
- View detailed information about each book
- User-friendly interface using Django templates
- SQLite database for storing book records

## Tech Stack 🛠
- **Django**: Backend framework
- **SQLite**: Database
- **HTML/CSS**: Templates for frontend
- **Python**: Programming language

## Installation & Setup ⚙️

1. **Clone the repository**:
    ```bash
    git clone https://github.com/skp3214/bookloom.git
    cd bookloom
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run migrations** to set up the SQLite database:
    ```bash
    python manage.py migrate
    ```

5. **Run the Django development server**:
    ```bash
    python manage.py runserver
    ```

6. **Access the application**:
    Open your browser and go to `http://127.0.0.1:8000/`

## Usage 🚀
- To add a new book, use the 'Add Book' button on the homepage.
- Update or delete a book by selecting the relevant options next to each book entry.

## Future Enhancements 📝
- User authentication (login, registration)
- Book categorization and genres
- Review and rating system for books
- Pagination for long book lists

## Screenshots 📸
![image](https://github.com/user-attachments/assets/e73f4868-9168-40b8-a8e2-2ad43e166320)

https://github.com/user-attachments/assets/3505d345-c3bc-4850-b4e2-e31796da2f18



## Contact 📧
If you have any questions, feel free to reach out:
- **Email**: skprajapati3214@gmail.com
- [LinkedIn](https://www.linkedin.com/in/skp3214/)

---

Feel free to customize this README further based on your specific project setup and add any additional sections you'd like!
