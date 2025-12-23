# Building a RESTful API

### Overview
This project demonstrates the design and development of a RESTful API using Python and Flask. The API serves as a backend for a sample business application, allowing clients to perform CRUD (Create, Read, Update, Delete) operations on resources stored in a database.  

---

### Objective
- Design and implement a robust REST API for a business application.  
- Learn best practices for API development, including routing, validation, and testing.  
- Integrate a backend database and handle real-world data scenarios.  
- Demonstrate knowledge of Python, Flask, and web development principles.  

---

### Tools & Technologies
<img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=Python&logoColor=white" />  
<img src="https://img.shields.io/badge/-Flask-000000?style=for-the-badge&logo=Flask&logoColor=white" />  
<img src="https://img.shields.io/badge/-SQLite-07405E?style=for-the-badge&logo=SQLite&logoColor=white" />  

---

### Steps Taken

<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/7702a033-55d1-4dad-b59f-9b2eb5c6ab35" />


## 📂 RESTful API Project Walkthrough

This project demonstrates building a RESTful API with Python and Flask. The following steps guide you through the development, testing, authentication, and deployment process.

---

### **Step 1: Set Up Development Environment** 
Developer machine creating a Python virtual environment and installing dependencies (Flask, SQLAlchemy).  
Arrows show Python environment → installed packages → ready for Flask app development.
 
---

### **Step 2: Initialize Flask App**  
  Flask app folder structure (`app.py`, `routes.py`, `models.py`).  
  Arrow from app initialization → API object creation.

---

### **Step 3: Create Database Models** 
  Flask app connected to database (SQLite/MySQL).  
  Table representation for `Item` with `id`, `name`, `price` columns.  
  Arrow representing app → database model mapping.

---

### **Step 4: Build API Endpoints**
  Client requests (POST, GET, PUT, DELETE) hitting Flask API endpoints (`/item`, `/item/<id>`).  
  Arrow showing Flask app processing requests and returning responses.
 
---

### **Step 5: Test API** 
  Postman or curl sending requests to API.  
  Responses coming back to client.  
  Optional: include success/failure icons.

---

### **Step 6: Add Authentication 
  Client requests → Flask API → JWT token validation → database/user verification.  
  Arrow returning token to client.  
  Label components clearly (Client, Flask API, JWT Auth, Database).

---

### **Step 7: Deploy API**
- **Diagram Concept:**  
  API deployed to cloud (Azure).  
  Client sends requests over internet → cloud-hosted API → database.  
  Highlight accessibility for testing.





