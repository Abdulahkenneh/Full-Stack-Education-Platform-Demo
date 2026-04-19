# Full-Stack Data Skills Academy - Demo

> ⚠️ **Important Notice:** This is a **sanitized demonstration version** of the actual production platform. The real application contains proprietary business logic, API keys, client data, and secure credentials that cannot be shared publicly. This demo showcases the architecture, features, and code structure without exposing any sensitive information.

A full-stack web application built using **Django**, designed to manage courses, coding problems, AI chat assistance, quizzes, and user progress tracking for an educational platform.

---

## 📸 Screenshots

### 🤖 AI Chat Assistant
*Personalized learning assistant that answers questions about courses and services*

![AI Chat Assistant](https://pub-45dc233b122746059d63ca735b2e1231.r2.dev/images/Screenshot%202026-04-16%20201246.png)

---

### 💻 Coding Problems Dashboard
*Browse and filter coding problems by category, difficulty, and track your progress*

![Coding Problems Dashboard](https://pub-45dc233b122746059d63ca735b2e1231.r2.dev/images/Screenshot%202026-04-16%20203430.png)

---

### ✏️ Code Editor / Problem Solver
*Interactive Python coding environment with test cases and expected outputs*

![Code Editor](https://pub-45dc233b122746059d63ca735b2e1231.r2.dev/images/Screenshot%202026-04-16%20203523.png)

---

### 📚 Course Overview Page
*View prerequisites, learning outcomes, and course details before enrolling*

![Course Overview](https://pub-45dc233b122746059d63ca735b2e1231.r2.dev/images/Screenshot%202026-04-16%20203659.png)

---

### 📊 User Progress Dashboard
*Track course completion percentage and overall learning journey*

![Progress Dashboard](https://pub-45dc233b122746059d63ca735b2e1231.r2.dev/images/Screenshot%202026-04-16%20203726.png)

---

### 📖 Lesson Content Page
*Interactive lessons with AI-powered explanations and summarization*

![Lesson Content](https://pub-45dc233b122746059d63ca735b2e1231.r2.dev/images/Screenshot%202026-04-16%20203811.png)

---

### 🗺️ Course Curriculum / Learning Path
*Structured modules with topics like Python Basics, SQL, Pandas, and Machine Learning*

![Course Curriculum](https://pub-45dc233b122746059d63ca735b2e1231.r2.dev/images/Screenshot%202026-04-16%20204010.png)

---

### ❓ Quiz Interface
*Interactive quizzes with drag-and-drop answers and instant feedback*

![Quiz Interface](https://pub-45dc233b122746059d63ca735b2e1231.r2.dev/images/Screenshot%202026-04-16%20204100.png)

---

> 🎥 **Full interactive demo available upon request** — [Contact me](mailto:info@dataskillacademy.com) for a private walkthrough.

---

## 📚 Features

- **AI Chat Assistant**: Personalized learning support powered by AI
- **Interactive Code Editor**: Solve coding problems with real-time testing
- **Course Management**: Structured learning paths with progress tracking
- **Quiz System**: Interactive quizzes with drag-and-drop answers
- **User Progress Dashboard**: Track completion across multiple courses
- **Discussion Forum**: Community discussions for each course
- **Blog Posts**: Educational content and learning resources
- **Google OAuth2**: Secure social authentication
- **Sitemaps & SEO**: SEO-friendly URLs and automatic sitemap generation

---

## 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| **Backend** | Django, Python |
| **Frontend** | HTML5, CSS3, Bootstrap |
| **Database** | SQLite (demo) / PostgreSQL (production) |
| **Authentication** | Django-Allauth, Google OAuth2 |
| **AI Features** | OpenAI API / Custom LLM integration |
| **Environment** | python-decouple |
| **Other** | Django Sitemaps, Requests |

---

## 📁 Project Structure
Data-Skills-Academy/
├── blogs/ # Blog application
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ ├── admin.py
│ ├── forms.py
│ ├── middleware.py
│ ├── signals.py
│ ├── sitemaps.py
│ ├── backends.py
│ ├── utils.py
│ ├── templatetags/
│ ├── templates/blogs/
│ └── migrations/
├── logusers/ # User activity logging
├── media/ # User-uploaded files (gitignored)
├── newblogs/ # Secondary blog features
├── pythonIDE/ # Python code execution environment
├── Dockerfile
├── LICENSE
├── README.md
└── requirements.txt

text

---

## 🔧 Installation

Follow these steps to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/Abdulahkenneh/Full-Stack-Data-Skills-Academy-Demo.git
cd Full-Stack-Data-Skills-Academy-Demo
2. Create a virtual environment
bash
python -m venv env
3. Activate the virtual environment
Windows:

bash
.\env\Scripts\activate
MacOS/Linux:

bash
source env/bin/activate
4. Install dependencies
bash
pip install -r requirements.txt
5. Set up environment variables
Create a .env file in the project root:

text
SECRET_KEY='your-secret-key-here'
DEBUG=True
DATABASE_URL='sqlite:///db.sqlite3'
OPENAI_API_KEY='your-openai-key-here'
6. Apply migrations
bash
python manage.py migrate
7. Create a superuser
bash
python manage.py createsuperuser
8. Run the development server
bash
python manage.py runserver
Then navigate to http://127.0.0.1:8000/

📖 Usage
Page	URL
Home	/
Admin Panel	/admin/
All Courses	/all_courses/
Coding Problems	/problems/
Code Editor	/editor/<problem_id>/
Blog Posts	/post/
User Profile	/profile/
Discussion Forum	/discusion-forum-home/<course_pk>/
Quiz	/course/<course_id>/quiz/
Sitemap	/sitemap.xml
📦 Dependencies
text
Django >= 3.2
django-allauth
django-sitemaps
psycopg2 (for PostgreSQL)
python-decouple
requests
openai (for AI features)
Install all at once:

bash
pip install -r requirements.txt
📄 License
This is a demo/portfolio project only.
For licensing inquiries about the production platform, contact: info@dataskillacademy.com

👨‍💻 Author
Abdulah Mamadee Kenneh
Founder & CEO @ Data Skills Academy
GitHub | LinkedIn

🙏 Acknowledgments
Built as a demonstration of full-stack Django capabilities

Inspired by real-world educational platform requirements

AI integration for personalized learning assistance

---

