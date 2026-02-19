# SaaS Subscription Platform (Django)

A SaaS application prototype built using Django that demonstrates authentication, subscription-based access control, and production-style deployment workflows.

## 🚀 Features

- User authentication with Django AllAuth (email + GitHub login)
- Subscription-based feature access using Django Groups and Permissions
- Stripe checkout integration for recurring billing workflows
- PostgreSQL database integration using Neon
- Automated workflows using GitHub Actions
- Deployment setup using Railway
- TailwindCSS-based responsive UI

## 🧱 Tech Stack

- Backend: Django
- Database: PostgreSQL (Neon)
- Authentication: Django AllAuth
- Payments: Stripe
- CI/CD: GitHub Actions
- Deployment: Railway
- Frontend: Django Templates, TailwindCSS

## ⚙️ Local Setup

```bash
git clone https://github.com/aryan2ab/SaaS-rnd
cd SaaS-rnd
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
