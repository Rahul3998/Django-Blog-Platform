# 📝 Django Blog Platform

A full-featured blog platform built using Django and Django REST Framework.  
It supports user registration, login, CRUD operations on blog posts, and a responsive Bootstrap UI with dark/light theme toggle.

---

## 🔧 Features

- User Registration and Login (with Django auth)
- Create, Edit, Delete your own blog posts
- View all posts (public access)
- Responsive UI with Bootstrap 5
- Dark/Light theme toggle (via localStorage)
- Only logged-in users can create/edit/delete their own posts
- Django admin interface for superusers

---

## 🚀 Tech Stack

- Python 3.10+
- Django 4.x
- SQLite (default DB)
- Bootstrap 5 (CDN)
- HTML/CSS (Django templating)

---

## 📦 Setup Instructions

```bash
# 1. Clone the repo
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py migrate

# 5. Create superuser (optional for admin access)
python manage.py createsuperuser

# 6. Start the development server
python manage.py runserver
