🏢 Django Job Portal
A job portal web application built with Django that allows applicants to search for jobs, apply online, and track their applications while companies can post jobs and manage applicants.

📌 Features
✅ User Authentication – Login & Registration for Applicants, Companies, and Admin.
✅ Job Listings – Companies can post jobs with descriptions, requirements, and salaries.
✅ Job Applications – Applicants can apply for jobs and track their applications.
✅ Profile Management – Users can update their profile details and resumes.
✅ Admin Dashboard – Manage users, jobs, and applications.
✅ Email Notifications – Get notified when an application is accepted/rejected.
✅ Dark/Light Mode – Toggle between dark and light themes.
✅ Password Reset – Secure reset via email.

🛠️ Tech Stack
Backend: Django, Django REST Framework
Frontend: HTML, CSS, Bootstrap (or Tailwind if updated)
Database: PostgreSQL / SQLite
Authentication: Django Auth
Email Integration: SMTP (Gmail, Outlook, etc.)
📂 Project Structure
📦 job-portal
├── 📂 jobportal           # Django Project
│   ├── settings.py        # Project settings
│   ├── urls.py            # URL configurations
│   ├── wsgi.py            # WSGI application
│   ├── asgi.py            # ASGI application
│   ├── __init__.py
├── 📂 jobs                # Job Management App
│   ├── models.py          # Database Models
│   ├── views.py           # Application Views
│   ├── urls.py            # App URLs
│   ├── forms.py           # Django Forms
│   ├── templates/         # HTML Templates
│   ├── static/            # CSS, JS, Images
├── 📂 users               # User Management App
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   ├── templates/
├── 📂 templates           # Global Templates
│   ├── base.html
│   ├── home.html
├── manage.py             # Django CLI  
├── requirements.txt      # Dependencies  
├── README.md  
└── .gitignore  
🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/dhanasai2/django-job-portal.git
cd django-job-portal

2️⃣ Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Apply migrations & run the server
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

5️⃣ Create a superuser (for admin access)
python manage.py createsuperuser

🎨 UI Enhancements
Added Dark/Light Mode Toggle
Improved CSS & Animations for a professional look
Used external images instead of static files
Optimized mobile responsiveness
📜 License
This project is licensed under the MIT License.

🤝 Connect with Me
📧 Email: saigundumogula5@gmail.com
🔗 LinkedIn: www.linkedin.com/in/dhana-sai


