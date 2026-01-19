# 🎓 School Website – Django Project

A modern **School Website** developed using **Django 5.1.3**, designed with Django templates and static assets, and configured for deployment on **Vercel**.

This project is ideal for:
- School / college projects
- Django practice
- Backend learning
- Portfolio demonstration

---

## 🌐 Live Website
(After deployment on Vercel)

https://your-project-name.vercel.app

---

## 🚀 Features

✔ Django 5.1.3  
✔ Template-based frontend  
✔ Static file management  
✔ WhiteNoise integration  
✔ Vercel-compatible setup  
✔ Clean and scalable structure  
✔ Secure production settings  
✔ Ready for backend expansion  

---

## 🧩 Technologies Used

- Python  
- Django  
- HTML5  
- CSS3  
- Tailwind CSS  
- WhiteNoise  
- Git & GitHub  
- Vercel  

---

## 📁 Project Structure

```
School-Website/
│
├── school/                 # Django project folder
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── templates/              # HTML templates
│   └── index.html
│
├── static/                 # CSS, JavaScript, Images
│
├── manage.py               # Django main file
├── requirements.txt        # Python dependencies
├── vercel.json             # Vercel configuration
├── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/AkPrajapati8719/School-Website.git
cd School-Website
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv .venv
```

Activate:

**PowerShell**
```bash
.venv\Scripts\activate
```

**Git Bash**
```bash
source .venv/Scripts/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Collect Static Files

```bash
python manage.py collectstatic
```

Type **yes** when asked.

---

### 5️⃣ Run Development Server

```bash
python manage.py runserver
```

Open in browser:

http://127.0.0.1:8000

---

## 🔐 Environment Variables

Create a `.env` file (recommended):

```
SECRET_KEY=your-secret-key
DEBUG=False
```

For Vercel, add these values inside **Environment Variables**.

---

## ☁️ Deployment on Vercel

1. Push project to GitHub  
2. Go to https://vercel.com  
3. Click **New Project**  
4. Import GitHub repository  
5. Choose **Other Framework**  
6. Click **Deploy**  

---

## ⚠️ Important Notes

- SQLite is recommended only for development
- Vercel does not support permanent media storage
- Use Cloudinary or AWS S3 for uploads
- WhiteNoise handles static files

---

## 🛡️ Security Configuration

- DEBUG disabled in production
- ALLOWED_HOSTS configured
- HTTPS proxy handling enabled
- CSRF protection enabled
- Secure cookies enabled

---

## 🧠 Future Improvements

- User authentication system  
- Student management  
- Teacher dashboard  
- Online admission form  
- REST API integration  
- PostgreSQL database  
- Admin analytics panel  

---

## 👨‍💻 Author

**Ak Prajapati**  
GitHub: https://github.com/AkPrajapati8719

---

## 📜 License

This project is open-source and free to use for educational and learning purposes.

---

⭐ If you like this project, please give it a star on GitHub!
