"# Cars-Website" 
🚗 Cars Website – Django & React

A full-stack Cars Website built using Django (REST Framework) for the backend and React for the frontend.
This platform allows users to view cars, check on-road prices, and submit reviews, with all data securely managed on the backend.

📌 Features

🔐 User Authentication (JWT based)

🚘 View Car Listings

💰 Check On-Road Price of Cars

⭐ Add & View Car Reviews

🧾 RESTful API with Django REST Framework

⚛️ Modern React Frontend

🌐 CORS Enabled for Frontend–Backend Communication

🗄️ Centralized Backend Database

🛠️ Tech Stack
Backend

Django

Django REST Framework

JWT Authentication

SQLite / PostgreSQL

django-cors-headers

Frontend

React

Axios

React Router

⚙️ Backend Setup (Django)
# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Run server
python manage.py runserver

Backend will run at:
http://127.0.0.1:8000/


⚛️ Frontend Setup (React)
# Navigate to frontend
cd frontend

# Install dependencies
npm install

# Start development server
npm start

Frontend will run at:
http://localhost:3000/


🔐 Authentication

-JWT-based authentication

-Secure login & signup

-Protected API endpoints

-Token stored and sent via headers for secure requests