Job Board Application
A modern job board platform built with Django that combines social features with job posting capabilities. This project merges the functionality of a job portal with social interaction features.

🚀 Quick Start
Set Up Virtual Environment

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies

pip install -r requirements.txt
Initialize Database

python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
Set Up Static Files

python manage.py collectstatic
Run Development Server

python manage.py runserver
🏗️ Project Structure
Quiz4/
├── accounts/           # User authentication & profiles
│   ├── models.py      # CustomUser and Profile models
│   └── views.py       # Authentication views
│── posts/
│   ├── models.py      # Post models
│   └── views.py       # Post related views
├── jobs/              # Job-related functionality
│   ├── models.py      # Job and Application models
│   └── views.py       # Job management views
├── static_my_project/ # Static assets
│   ├── css/          # Bootstrap and custom styles
│   └── js/           # JavaScript files
└── templates/        # HTML templates
    ├── auth/        # Authentication templates
    └── jobs/        # Job-related templates
    └── posts/       # Post-related templates
    
📝 Submission Instructions
Create Your Own Repository

Create a new repository on GitHub
Initialize it as a public repository
Do not add any default files (README, license, etc.)
Add New Remote

# Since 'origin' is already taken, use a different name like 'submission'
git remote add submission <your-new-repo-url>

# Verify your remotes
git remote -v
# quiz4
