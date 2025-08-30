# 🐾 Petstagram 2024

A social media web application for pet lovers to share photos of their pets. Built with Django and PostgreSQL, and deployed on Render.

### Link to the website: https://petsagram-2024.onrender.com/

## 🚀 Features

- ✅ User registration, login & logout with custom user model  
- 🐶 Upload photos of pets  
- 🏷️ Tag pets in photos  
- ❤️ Like photos  
- 💬 Comment on photos  
- 👤 User profile pages  
- 🛠️ Admin panel with custom permissions  
- ☁️ Media storage with Cloudinary  
- 🌐 Deployed on Render with CI/CD via Jenkins  

## 🧰 Tech Stack

- **Backend:** Django 5, PostgreSQL  
- **Frontend:** HTML, CSS, JavaScript  
- **CI/CD:** Jenkins, GitHub Webhooks  
- **Deployment:** Render  
- **Cloud Storage:** Cloudinary  

## 📁 Project Structure

petstagram_2024/ ├── common/ # Base templates, static files ├── photos/ # Photo model, views, forms ├── pets/ # Pet model and logic ├── accounts/ # Custom user logic and profile management ├── templates/ # HTML templates ├── static/ # CSS, JS, images ├── manage.py


# Project setup

### 1. Clone the repo
   
  ```terminal

    git clone https://github.com/DiyanKalaydzhiev23/petstagram-2024.git

  ```

### 2. Open the project


### 3. Install dependencies
 
   ```terminal
   
     pip install -r requirements.txt
  
   ```

### 4. Change DB settings in settings.py

  ```py
    DATABASES = {
        "default": {
            "ENGINE": "django.db.backends.postgresql",
            "NAME": "your_db_name",
            "USER": "your_username",
            "PASSWORD": "your_pass",
            "HOST": "127.0.0.1",
            "PORT": "5432",
        }
    }
  ```

### 5. Run the migrations

  ```terminal

    python manage.py migrate

  ```

### 6. Run the project

  ```terminal

    python manage.py runserver

  ```
