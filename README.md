# Django Online Course Assessment Feature

This project adds a **course assessment feature** to an existing Django-based online course platform. As part of a full-stack developer task, I implemented the ability to create and manage exams (questions and choices), allow users to submit answers, and view graded results.

## 📌 Project Description

The objective was to enhance an online course application by adding a complete exam and submission system. Users can now:

- View course exams
- Select answers from choices
- Submit responses
- View graded exam results

This was done using Django models, views, templates, and the admin interface.

## 🧩 Features Implemented

- `Question`, `Choice`, and `Submission` models
- Admin site integration to manage exam content
- Exam form on the course detail page
- Result evaluation logic and grading view
- Result display template with correct/incorrect answers

## 🛠️ Tech Stack

- Python 3.11
- Django Web Framework
- SQLite3 (default)
- HTML/CSS (Django templating)
- Git + GitHub for version control

## 🚀 How to Run Locally

```bash
# Clone the starter repo
git clone https://github.com/amrmosit/PythonDjango-cloud-app-with-database.git
cd PythonDjango-cloud-app-with-database

# Set up virtual environment
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate

# Install required packages
pip install -U -r requirements.txt

# Apply migrations
python manage.py makemigrations
python manage.py migrate

# Run the development server
python manage.py runserver
