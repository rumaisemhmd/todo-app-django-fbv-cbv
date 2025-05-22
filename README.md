# Django To-Do App (FBV + CBV)

This is a simple To-Do List web application built using *Python, **Django, **HTML, **CSS, and **Bootstrap*.  
It includes both *Function-Based Views (FBV)* and *Class-Based Views (CBV)* for learning purposes and comparison.

---

## Features

- Add new tasks  
- View list of tasks  
- Edit/update tasks  
- Delete tasks  
- Includes both FBV and CBV versions  

---

## Tech Stack

- *Backend:* Django (Python)  
- *Frontend:* HTML, CSS, Bootstrap  
- *Database:* PostgreSQL

---

## How to Run

1. Clone the repository  
2. Set up a virtual environment  
3. Install dependencies  
4. Apply migrations  
5. Run the server

```bash
git clone https://github.com/your-username/todo-app-django-fbv-cbv.git
cd todo-app-django-fbv-cbv
python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

