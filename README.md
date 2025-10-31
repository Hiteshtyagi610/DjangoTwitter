# 🐦 Django Twitter Clone

A fully functional **Twitter-like social media web app** built with **Django** where users can **create, edit, and delete tweets** securely. Only **authenticated users** can interact with tweets, ensuring user privacy and ownership control. This project demonstrates Django’s **Model–View–Template (MVT)** architecture, authentication system, and CRUD operations.

---

## 📚 About the Project

The **Django Twitter Clone** is a mini social platform that allows users to:
- Create short posts (tweets)
- Edit or delete their own tweets
- View tweets from all users
- Manage authentication (register, login, logout)

This project was built to practice:
- Django forms and model relationships
- Django authentication and permissions
- CRUD (Create, Read, Update, Delete) operations
- Using templates, static files, and CSRF protection

It serves as a **beginner-friendly Django project** to understand web development with Python.

---

## ✨ Features

- 🧑‍💻 User Registration, Login, Logout
- 📝 Create new tweets
- ✏️ Edit existing tweets
- 🗑️ Delete tweets
- 📋 View all tweets
- 🕐 Timestamps for tweet creation
- 🧱 Responsive design with Bootstrap
- 🔒 Secure access control for authenticated users

---

## 🛠️ Tech Stack

- **Language:** Python 3.x  
- **Framework:** Django 5.x  
- **Frontend:** HTML5, CSS3, Bootstrap 5  
- **Database:** SQLite (default, can switch to PostgreSQL/MySQL)  
- **Authentication:** Django built-in user model  
- **Templating Engine:** Django Templates  

---

## 📁 Project Structure

```

twitter_clone/
│
├── manage.py
├── db.sqlite3
├── requirements.txt
│
├── twitter_clone/          # Project configuration
│   ├── **init**.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   ├── asgi.py
│
└── tweets/                 # Main app (create, edit, delete tweets)
├── migrations/
├── templates/
│   ├── layout.html
│   ├── tweet_list.html
│   ├── tweet_form.html
│   ├── tweet_confirm_delete.html
├── static/
├── forms.py
├── models.py
├── urls.py
├── views.py

````

---

## ⚙️ Setup Instructions

### 1️⃣ Clone this repository
```bash
git clone https://github.com/yourusername/django-twitter-clone.git
cd django-twitter-clone
````

### 2️⃣ Create and activate a virtual environment

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

*(If you don’t have a `requirements.txt`, generate it using:)*

```bash
pip freeze > requirements.txt
```

### 4️⃣ Apply database migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Create a superuser

```bash
python manage.py createsuperuser
```

### 6️⃣ Run the development server

```bash
python manage.py runserver
```

### 7️⃣ Open your app

Go to 👉 **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)** in your browser.

---

## ⚙️ How It Works

1. **User Authentication:**
   Users can sign up or log in using Django’s built-in auth system.

2. **Tweet Model:**
   Each tweet is linked to a user using a foreign key. Tweets contain text, an optional image, and a timestamp.

3. **CRUD Operations:**

   * Create → Add a new tweet using a form
   * Read → View all tweets on the homepage
   * Update → Edit your own tweets only
   * Delete → Remove your tweets with confirmation

4. **Templates:**
   The app uses `layout.html` as a base template, extended by all pages for consistent design.

---

## 💻 Usage Guide

### Creating a Tweet

* Log in to your account.
* Navigate to **Create Tweet**.
* Fill out the form and submit.

### Editing a Tweet

* Open a tweet you’ve posted.
* Click the **Edit** button.
* Update content and save.

### Deleting a Tweet

* Open your tweet.
* Click **Delete** and confirm.

---



## 🚀 Future Improvements

* 🧍 User profiles with bio and profile picture
* ❤️ Like & comment system
* 🔍 Hashtags and tweet search
* 🕓 Pagination for long tweet lists
* 🖼️ Image upload preview
* 🌙 Dark mode UI

---

## 🤝 Contributing

Contributions are welcome!
To contribute:

1. Fork the repo
2. Create a new branch (`feature/your-feature-name`)
3. Commit your changes
4. Push and create a Pull Request

---



> 💡 *This Django Twitter Clone is a perfect beginner project to learn full-stack web development using Python and Django!*

```

