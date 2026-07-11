# Habit Tracker Backend

Laravel REST API backend for the Habit Tracker application.

This backend handles:
- habit management
- settings management
- API routing
- MySQL database communication

---

# Tech Stack

- Laravel
- PHP
- MySQL
- REST API
- Eloquent ORM

---

# Features

- Create habits
- Delete habits
- Fetch habits
- Settings management
- API-based architecture
- MySQL database integration

---

# API Endpoints

## Habits

GET /api/habits

POST /api/habits

DELETE /api/habits/{id}

---

## Settings

GET /api/settings

POST /api/settings

---

# Folder Structure

app/
├── Http/
├── Models/

config/
database/
routes/

# Installation
Clone Repository
git clone https://github.com/Shaksham10/habit-tracker-backend.git
Install Dependencies
composer install
Configure Environment

# Create .env file and configure:

database name
username
password

# Run Migrations
php artisan migrate

# Start Server
php artisan serve

# Frontend Repository

https://github.com/Shaksham10/habit-tracker-frontend

# Future Improvements

Authentication system
JWT authentication
Real analytics tracking
Production deployment
Better API validation
User accounts

# Author
Shaksham

# GitHub:
https://github.com/Shaksham10
