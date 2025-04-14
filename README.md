# 🏢 Django Job Portal

A **fully functional job portal** built with **Django**, where applicants can search and apply for jobs, and companies can post job listings and manage applicants.

---
Website Link :- https://mohansaladi.pythonanywhere.com/

## 🌟 Features

- 🔑 **User Authentication** – Register/Login for Applicants, Companies, and Admin.  
- 📌 **Job Listings** – Companies can post jobs with detailed descriptions.  
- 📝 **Job Applications** – Applicants can apply for jobs and track status.  
- 👤 **Profile Management** – Users can update resumes and personal details.  
- 🏛️ **Admin Dashboard** – Manage jobs, users, and applications.  
- 📧 **Email Notifications** – Alerts for job application acceptance/rejection.  
- 🎨 **Dark/Light Mode** – Switch themes for better user experience.  
- 🔒 **Password Reset** – Secure reset via email.  

---

## 🛠️ Tech Stack

| Technology  | Description |
|------------|-------------|
| **Django** | Backend framework |
| **SQLite / PostgreSQL** | Database |
| **HTML, CSS, Bootstrap** | Frontend design |
| **Django Auth** | User authentication |
| **SMTP / Email APIs** | Email integration |
| **TailwindCSS (Optional)** | Enhanced UI styling |

---

## 📂 Project Structure

```
📦 django-job-portal
├── 📂 jobportal            # Main Django project
│   ├── settings.py        # Project settings
│   ├── urls.py            # Global URL configurations
│   ├── wsgi.py            # WSGI application
│   ├── asgi.py            # ASGI application
│   ├── __init__.py
│
├── 📂 jobs                 # Job Management App
│   ├── models.py          # Job-related models
│   ├── views.py           # Job views & logic
│   ├── urls.py            # Job-related routes
│   ├── forms.py           # Job application forms
│   ├── templates/         # Job HTML templates
│   ├── static/            # Job-related static files
│
├── 📂 users                # User Management App
│   ├── models.py          # User models
│   ├── views.py           # User authentication views
│   ├── forms.py           # User-related forms
│   ├── urls.py            # User-related routes
│   ├── templates/         # User HTML templates
│
├── 📂 templates            # Global HTML Templates
│   ├── base.html          # Main layout template
│   ├── home.html          # Homepage
│
├── manage.py              # Django CLI entry point
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── .gitignore             # Ignore unnecessary files
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/dhanasai2/django-job-portal.git
cd django-job-portal
```

### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scriptsctivate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Apply Migrations & Start Server
```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

### 5️⃣ Create a Superuser (Admin Panel)
```bash
python manage.py createsuperuser
```

---

## 🎨 Enhancements

✅ **Dark/Light Mode Toggle** for improved UX  
✅ **Responsive UI** optimized for mobile & desktop  
✅ **Professional CSS & Animations** for a clean interface  
✅ **Secure Authentication & Authorization**  
✅ **Email Alerts for Job Application Updates**  

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🤝 Connect with Me

📧 Email: saaigundumogula5@email.com  
🔗 [LinkedIn] www.linkedin.com/in/dhana-sai 

---
