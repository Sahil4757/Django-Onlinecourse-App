# Django Online Course App

A full-featured online learning platform built with Django that allows users to browse courses, enroll, and take assessments.

## 📚 Features

- **Course Management**: Browse and view detailed course information
- **User Authentication**: Register, login, and manage user profiles
- **Enrollment System**: Enroll in courses and track progress
- **Assessment & Quizzes**: Take course exams and receive instant results
- **Admin Panel**: Manage courses, lessons, and users through Django admin

## 🛠️ Technologies Used

- **Backend**: Django 4.x
- **Database**: SQLite (development)
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Authentication**: Django built-in authentication system

## 📋 Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Virtual environment (recommended)

## 🚀 Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/Sahil4757/Django-Onlinecourse-App.git
cd Django-Onlinecourse-App
```

2. **Create a virtual environment**
```bash
python -m venv venv
```

3. **Activate the virtual environment**
- Windows:
```bash
venv\Scripts\activate
```
- Mac/Linux:
```bash
source venv/bin/activate
```

4. **Install dependencies**
```bash
pip install -r requirements.txt
```

5. **Run migrations**
```bash
python manage.py migrate
```

6. **Create a superuser (admin)**
```bash
python manage.py createsuperuser
```

7. **Run the development server**
```bash
python manage.py runserver
```

8. **Access the application**
- Main site: http://127.0.0.1:8000/
- Admin panel: http://127.0.0.1:8000/admin/

## 📁 Project Structure

```
djangoenv/
│
├── myproject/          # Main project settings
├── onlinecourse/       # Course app
├── static/             # Static files (CSS, JS, images)
├── manage.py           # Django management script
└── requirements.txt    # Python dependencies
```

## 📸 Screenshots

### User Registration
![Sign Up Page](https://github.com/Sahil4757/Django-Onlinecourse-App/blob/main/screenshots/sign-up.png)
*Clean and simple registration form for new users*

### Course List
![Course List](https://github.com/Sahil4757/Django-Onlinecourse-App/blob/main/screenshots/course-list.png)
*Browse available courses with enrollment status*

### Course Detail & Lessons
![Course Detail](https://github.com/Sahil4757/Django-Onlinecourse-App/blob/main/screenshots/course-details.png)
*View course lessons and take assessments*

### Exam Results
![Exam Results](https://github.com/Sahil4757/Django-Onlinecourse-App/blob/main/screenshots/exam-result.png)
*Instant feedback with score and correct answers*

### Admin Panel
![Admin Panel](https://github.com/Sahil4757/Django-Onlinecourse-App/blob/main/screenshots/admin-panel.png)
*Manage courses, lessons, questions, and users*

## 💡 Usage

1. **Admin**: Login to admin panel to create courses, lessons, and questions
2. **Students**: Register an account, browse courses, enroll, and take assessments
3. **Course Creation**: Add courses with descriptions, images, and lessons
4. **Assessments**: Create questions and track student results

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Sahil**
- GitHub: [@Sahil4757](https://github.com/Sahil4757)

## 🙏 Acknowledgments

- Built as part of learning Django framework
- Inspired by various online learning platforms

---

⭐ Star this repository if you find it helpful!
