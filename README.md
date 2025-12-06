# Naman Jain - DevOps Engineer Portfolio

A modern, responsive portfolio website built with Django, showcasing my skills, experience, and projects as a DevOps Engineer.

## 🚀 Features

- **Responsive Design**: Looks great on all devices
- **Modern UI**: Clean and professional interface with dark/light mode
- **Sections**:
  - About Me
  - Skills & Tools
  - Experience
  - Projects
  - Contact Form
- **Interactive Elements**: Smooth scrolling, theme toggle, and form handling

## �️ Tech Stack

- **Backend**: Django 5.2
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Database**: SQLite (Development)
- **Deployment**: Ready for production deployment

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip (Python package manager)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone [your-repository-url]
   cd portfolio
   ```

2. **Create and activate a virtual environment**
   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate
   
   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations**
   ```bash
   python manage.py migrate
   ```

5. **Start the development server**
   ```bash
   python manage.py runserver
   ```

6. **Access the website**
   Open your browser and go to `http://127.0.0.1:8000/`

## 🌐 Deployment

This project is configured for deployment. Update the following in `core/settings.py` for production:
- Set `DEBUG = False`
- Configure `ALLOWED_HOSTS` with your domain
- Set up a production database (PostgreSQL recommended)
- Configure static files for production
- Set up a proper web server (Nginx/Apache) with Gunicorn/uWSGI

## 🛠️ Project Structure

```
portfolio/
├── core/               # Django project settings
├── home/               # Main app
│   ├── migrations/     # Database migrations
│   ├── static/         # Static files (CSS, JS, images)
│   ├── templates/      # HTML templates
│   ├── admin.py        # Admin configuration
│   ├── apps.py         # App configuration
│   ├── models.py       # Database models
│   ├── tests.py        # Test cases
│   └── views.py        # View functions
├── manage.py           # Django management script
└── db.sqlite3          # SQLite database (development)
```

## 🤝 Contributing

Contributions are welcome! If you find any issues or want to enhance the project:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 📬 Contact

- **Name**: Naman Jain
- **Role**: DevOps Engineer
- **Email**: [Your Email]
- **LinkedIn**: [Your LinkedIn Profile]
- **GitHub**: [Your GitHub Profile]

---

Made with ❤️ by Naman Jain
