# SIT737 Task 4.1P – Calculator Microservice

## 📘 Overview

This project implements a simple calculator microservice using **Node.js** and **Express.js**.  
It supports basic arithmetic operations via RESTful API endpoints and includes logging using the **Winston** library.

---

## ✨ Features

| Endpoint    | Description              | Example Query              |
| ----------- | ------------------------ | -------------------------- |
| `/add`      | Adds two numbers         | `/add?num1=5&num2=2`       |
| `/subtract` | Subtracts num2 from num1 | `/subtract?num1=10&num2=4` |
| `/multiply` | Multiplies two numbers   | `/multiply?num1=3&num2=7`  |
| `/divide`   | Divides num1 by num2     | `/divide?num1=10&num2=2`   |

✅ Includes error handling for:

- Non-numeric input
- Division by zero

---

## 🛠️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/bowen159yao/sit737-2025-prac4p.git
cd sit737-2025-prac4p
```
