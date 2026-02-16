# HBnB - Holberton AirBnB Clone Project

## 📋 Part 1 - UML Design & Documentation
📋 **Architectural Design**: This part contains all the design documentation and UML architecture of the project. It defines class diagrams, entity relationships, business rules, and layered architecture (Presentation → Business Logic → Persistence). It's the architectural blueprint that guides the development of the other parts.

**Technologies**: Mermaid.js, Markdown, UML

---

## 🚀 Part 2 - Basic Flask API  
🚀 **Basic RESTful API**: Implementation of the Flask API with CRUD operations for the 4 main entities (User, Place, Amenity, Review). Uses in-memory persistence via a repository pattern, includes data validation, automatic Swagger documentation, and unit tests. Facade pattern architecture to separate layers.

**Technologies**: Python, Flask, Flask-RESTx, pytest

---

## 🔐 Part 3 - Advanced Flask API with Authentication & DB
🔐 **Secure and Persistent API**: Evolution of Part 2 with the addition of JWT authentication, role management (admin/user), protection of sensitive endpoints, and migration to a SQLite database with SQLAlchemy ORM. Introduces durable data persistence with database relationships (Foreign Keys, Many-to-Many).

**Technologies**: Flask-JWT-Extended, Flask-Bcrypt, SQLAlchemy, SQLite

---

## 🌐 Part 4 - Frontend Web Application
🌐 **Modern User Interface**: Responsive frontend web application that consumes the API. Includes a secure login system with token management, dynamic property display with filtering, complete review system, and intuitive user interface. Built with HTML, CSS, JavaScript for a fluid user experience.

**Technologies**: HTML5, CSS3, JavaScript ES6+, Fetch API, Google Fonts

---

## 🚀 Getting Started

### Quick Start
```bash
# Part 2&3 - API Backend
cd part3/hbnb
pip install -r requirements.txt
python3 run.py

# Part 4 - Frontend
# Open part4/base_files/index.html in your browser
```

### API Access
- **API**: `http://127.0.0.1:5000`
- **Documentation**: `http://127.0.0.1:5000/doc`

---

## 👥 Authors

### Team Development

- **Lucas Boyadjian** - [@Yadjian](https://github.com/Yadjian)
- **Wassef Abdallah**
- **Julien Girardey**  

---

