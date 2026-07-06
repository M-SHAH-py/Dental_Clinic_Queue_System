# Dental Clinic Smart Queue Management System

## Overview

This project is a Dental Clinic Smart Queue Management System developed using **Python** and **Oracle Database**.

The system manages patient registration, visit scheduling, dentist assignment, smart queue handling, and performance metrics.

This project integrates a Python application with Oracle Database to demonstrate database connectivity, SQL operations, and queue management algorithms.

---

## Features

- Patient Registration
- Visit Registration
- Dentist Management
- Specialty-based Assignment
- Smart Queue Management
- Load Balancing
- Queue Priority
- Performance Metrics
- Oracle Database Integration

---

## Technologies Used

- Python
- Oracle Database 21c XE
- SQL
- OracleDB Python Driver

---

## Database

The project contains the complete Oracle SQL script.

```
dental_clinic_database.sql
```

This script creates:

- Specialty
- Dentist
- Patient
- Treatment
- Visit
- Queue
- Assignment

tables with all constraints and relationships.

---

## Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Dental_Clinic_Queue_System.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Create Oracle Database

Run

```
dental_clinic_database.sql
```

inside Oracle SQL Developer.

---

## Configure Database

Open

```
app.py
```

Update:

```python
connection = oracledb.connect(
    user="YOUR_USERNAME",
    password="YOUR_PASSWORD",
    dsn="localhost:1521/XEPDB1"
)
```

---

## Run

```bash
python app.py
```

---

## Project Modules

1. Register Patient
2. Register Visit
3. Queue Status
4. Load Balancer
5. Complete Visit
6. Performance Metrics

---

## Learning Outcomes

- Oracle Database
- SQL
- Python Database Connectivity
- Queue Management
- Load Balancing
- Relational Database Design

---

## Author

Your Name

BS Computer Science

University Project
