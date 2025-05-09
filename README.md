# BackEnd for CRM with NoSQL DB

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-0.95.1-009688?style=for-the-badge&logo=fastapi)
![MongoDB](https://img.shields.io/badge/MongoDB-6.0-green?style=for-the-badge&logo=mongodb)
![Pytest](https://img.shields.io/badge/Pytest-7.2.0-yellow?style=for-the-badge&logo=pytest)
![License](https://img.shields.io/badge/License-Educational-lightgrey?style=for-the-badge)

---

## 📌 Overview

**CRM_NoSQL** is a lightweight Customer Relationship Management (CRM) system designed to manage contacts and track interaction history. Built with **FastAPI** and **MongoDB**, it offers a RESTful API for efficient data operations.

---

## 🚀 Features

- 🔐 User authentication
- 📇 Contact management (CRUD operations)
- 📁 MongoDB integration for data storage
- 🌐 RESTful API endpoints
- 🧪 Unit and API testing with Pytest

---

## 🛠️ Tech Stack

- **Backend:** Python 3.10, FastAPI
- **Database:** MongoDB 6.0
- **Testing:** Pytest
- **Logging:** Built-in logging module

---

## ⚙️ Installation

### Prerequisites

- Python 3.10+
- MongoDB 6.0+

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/IvashDima/CRM_NoSQL.git
   cd CRM_NoSQL

2. **Create a virtual environment and activate it:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt

4. **Start MongoDB: Ensure MongoDB is running on its default port.**

5. **Run the application:**

   ```bash
   python main.py

6. **Access the API documentation:**

Open your browser and navigate to http://localhost:4558/docs#/ to explore the interactive API docs.

---

## 🧪 Testing

**Run unit and API tests using Pytest:**

   ```bash
   pytest -v test_api.py
   ```

---

## 📂 Project Structure

   ```text
   CRM_NoSQL/
   ├── core/               # Core logic and utilities
   ├── logs/               # Log files
   ├── src/                # Source code
   ├── tests/              # Test cases
   ├── main.py             # Entry point of the application
   ├── requirements.txt    # Python dependencies
   └── README.md           # Project documentation
   ```

---

## 📸 Screenshots

---

## 📌 Important Notes

- **Educational Purpose:** This project was developed as a final assignment for a Back-End Development course. It serves as a demonstration of integrating FastAPI with MongoDB.

- **Not Production-Ready:** While functional, this application is not optimized for production environments. Features like advanced security, scalability, and error handling may need enhancements.

- **Feedback Welcome:** Contributions, suggestions, and feedback are appreciated to improve the project further.

---

## 📫 Contact

- **GitHub:** [IvashDima](https://github.com/IvashDima/)
- **LinkedIn:** [Dmytro Ivashchenko](https://www.linkedin.com/in/dmytro-ivashchenko/)
- **Email:** dnytsyk@gmail.com

Feel free to reach out for questions, suggestions, or collaborations!

---

## 📝 License

This project is provided for educational purposes only and does not have a specific license.

Feel free to contribute, suggest improvements, or fork the project! 🚀