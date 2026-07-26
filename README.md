# 🧮 Distributed Calculator Web Service

A distributed calculator application developed in Python as part of the **Parallel and Distributed Computing Systems** course.

The project demonstrates distributed system concepts by separating arithmetic operations into independent microservices coordinated through a centralized API Gateway. A graphical user interface (GUI) allows users to perform calculations while the backend routes requests to the appropriate service.

---

## ✨ Features

- ➕ Addition Service
- ➖ Subtraction Service
- ✖️ Multiplication Service
- ➗ Division Service
- 🌐 API Gateway for request routing
- 🖥️ Desktop GUI built with Tkinter
- 🔄 RESTful communication using HTTP & JSON
- ⚡ Distributed service architecture
- 🛡️ Basic fault handling and service monitoring

---

## 🏗️ System Architecture

The system consists of four main components:

- Client GUI
- API Gateway
- Independent Calculation Services
- Communication through REST APIs

Each arithmetic operation runs as a separate service, while the gateway forwards client requests to the appropriate service and returns the result.

---

## 📂 Project Structure

```
Distributed-Calculator/
│
├── gateway/
├── gui/
├── services/
├── run_all.py
└── README.md
```

---

## 🛠️ Technologies Used

- Python
- Flask
- Tkinter
- REST API
- JSON
- HTTP
- Distributed Systems Concepts

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/MaysAlsalum/Distributed-Calculator.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the project

```bash
python run_all.py
```

---

## 📖 Learning Outcomes

This project demonstrates:

- Distributed Computing
- Service-Oriented Architecture (SOA)
- Microservices
- API Gateway Design
- RESTful Communication
- Parallel Request Processing
- Modular Software Design

---

##  Team Members

- Mays Alsalum
- Hailah Albijadi
- Maha Alotaibi
- Sadeem Albukhaytan
- Deem Albukhaytan

---

##  Academic Information

**Course:** Parallel and Distributed Computing Systems

This project was developed as an educational project to demonstrate the practical implementation of distributed computing concepts using Python and Flask.

---

## License

This project is intended for educational and learning purposes.
