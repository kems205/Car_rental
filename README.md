# 🚗 Car Rental - Location de Voitures

A web application for managing car rentals, built with Django.

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 About

Car Rental is a full-featured web application that allows users to browse available vehicles, make reservations, and manage rentals. Administrators can manage the fleet, track rentals, and handle customer accounts.

---

## ✨ Features

- 🚘 Browse and search available vehicles
- 📅 Make and manage reservations
- 👤 User authentication and profiles
- 🛠️ Admin dashboard for fleet management
- 📊 Rental history and reporting

---

## 🛠️ Tech Stack

- **Backend** - Python / Django
- **API** - Django REST Framework
- **Database** - SQLite (dev) / PostgreSQL (prod)
- **Auth** - Django Authentication System

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Git

### Installation

1. Clone the repository
```bash
   git clone https://github.com/kems205/Car_rental.git
   cd Car_rental
```

2. Create and activate virtual environment
```bash
   python3 -m venv env
   source env/bin/activate
```

3. Install dependencies
```bash
   pip install -r requirements.txt
```

4. Apply migrations
```bash
   python manage.py migrate
```

5. Create a superuser
```bash
   python manage.py createsuperuser
```

6. Run the development server
```bash
   python manage.py runserver
```

7. Visit `http://127.0.0.1:8000`

---

## 📁 Project Structure
```
Car_rental/
├── config/          # Project settings and URLs
├── cars/            # Vehicle management
├── rentals/         # Rental and reservation logic
├── accounts/        # User authentication
├── requirements.txt
└── manage.py
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

<p align="center">Made with ❤️ by <a href="https://github.com/kems205">kems205</a></p>
