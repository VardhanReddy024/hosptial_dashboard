# 🏥 Hospital Management Dashboard

A comprehensive Hospital Management Dashboard built using **Python, Streamlit, SQLite, Pandas, Plotly, and Machine Learning**. The system provides role-based access for Admins, Doctors, and Patients, enabling appointment management, healthcare analytics, and predictive insights through an interactive web application.

---

## 🚀 Live Project

**GitHub Repository:**  
https://github.com/VardhanReddy024/hosptial_dashboard

---

## 📖 Project Overview

The Hospital Management Dashboard is designed to streamline hospital operations by integrating patient management, appointment scheduling, doctor workflows, business analytics, and machine learning-powered forecasting into a single platform.

The application supports three user roles:

### 👨‍💼 Admin
- View complete analytics dashboard
- Monitor appointments
- Track hospital revenue and expenses
- Analyze doctor performance
- Access audit logs

### 👨‍⚕️ Doctor
- Manage availability and schedules
- View assigned appointments
- Update appointment status
- Create patient notes and prescriptions
- Access patient medical history

### 👤 Patient
- Book appointments
- View appointment history
- Access medical records
- Receive doctor recommendations based on symptoms

---

# ✨ Features

## 🔐 Authentication & Authorization
- Secure Login and Signup
- Role-Based Access Control
- Password Hashing using bcrypt
- Session Management

## 📅 Appointment Management
- Appointment Booking System
- Doctor Availability Management
- Time Slot Conflict Detection
- Appointment Status Tracking
- Appointment History

## 👨‍⚕️ Doctor Portal
- Manage Working Days
- Manage Available Time Slots
- Update Appointment Status
- Add Patient Notes
- Maintain Medical History

## 👤 Patient Portal
- Book Appointments
- View Appointment Status
- View Medical History
- Symptom-Based Doctor Recommendation

## 📊 Analytics Dashboard
- Revenue Analysis
- Expense Analysis
- Profit Analysis
- Department Performance
- Doctor Performance
- Patient Distribution
- Gender Analytics
- Payment Mode Analytics

## 📈 Business Intelligence
- KPI Cards
- Revenue Growth Insights
- Department Performance Tracking
- Operational Notifications
- Doctor Utilization Metrics

## 🤖 Machine Learning
- Revenue Forecasting
- Appointment Volume Prediction
- Future Trend Analysis
- Random Forest Regression Model

## 🧾 Audit Logging
- Track Appointment Status Changes
- Monitor Administrative Actions
- Improve System Transparency

---

# 🏗️ Architecture

## Frontend Layer
- Streamlit
- Responsive Dashboard UI
- Interactive Components

## Business Logic Layer
- Authentication
- Appointment Management
- Doctor Management
- Analytics Processing

## Data Layer
- SQLite Database
- Patient Records
- Appointment Records
- Audit Logs

## Analytics & ML Layer
- Pandas Data Processing
- Plotly Visualizations
- Scikit-learn Machine Learning Models

---

# 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### Database
- SQLite

### Data Processing
- Pandas
- NumPy

### Visualization
- Plotly

### Machine Learning
- Scikit-learn
- Random Forest Regressor

### Security
- bcrypt

---

# 📂 Project Structure

```text
hosptial_dashboard/
│
├── app.py
├── config.py
├── requirements.txt
├── README.md
├── hospital.db
│
├── database/
│   └── db.py
│
├── modules/
│   ├── auth.py
│   ├── appointments.py
│   ├── charts.py
│   ├── data_loader.py
│   ├── filters.py
│   ├── insights.py
│   ├── kpi.py
│   └── ml_model.py
│
├── data/
│   └── hospital_data.csv
│
└── assets/
    └── aiimage.png
```

---

# 🗄️ Database Design

### Users Table
Stores:
- Username
- Password
- Role
- Specialization
- Availability
- Doctor Status

### Appointments Table
Stores:
- Patient Name
- Doctor Name
- Appointment Date
- Time Slot
- Issue
- Status

### Patient History Table
Stores:
- Diagnosis
- Prescription
- Follow-up Details
- Notes

### Audit Logs Table
Stores:
- Appointment Updates
- User Actions
- Status Changes

---

# 🔄 Application Workflow

### Step 1
User logs in as Admin, Doctor, or Patient.

### Step 2
Authentication validates credentials using bcrypt.

### Step 3
Based on role:
- Admin accesses analytics
- Doctor accesses appointment management
- Patient accesses booking portal

### Step 4
Data is stored and retrieved from SQLite.

### Step 5
Pandas processes hospital data.

### Step 6
Plotly generates interactive charts.

### Step 7
Machine Learning predicts:
- Future Revenue
- Future Appointment Volume

---

# 📈 Machine Learning Workflow

## Revenue Prediction
1. Historical revenue data is collected.
2. Monthly revenue trends are generated.
3. Random Forest Regressor is trained.
4. Revenue for the next 3 months is predicted.

## Appointment Forecasting
1. Historical appointment data is analyzed.
2. Monthly appointment trends are created.
3. Future appointment volumes are forecasted.

---

# 📊 Dashboard Analytics

### Financial Metrics
- Revenue
- Expense
- Profit

### Operational Metrics
- Total Patients
- Total Doctors
- Total Appointments
- Average Patient Stay

### Department Metrics
- Department Revenue
- Department Profit
- Department Patient Load

### Doctor Metrics
- Revenue by Doctor
- Patients by Doctor
- Appointment Status Tracking

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/VardhanReddy024/hosptial_dashboard.git
```

```bash
cd hosptial_dashboard
```

## Create Virtual Environment

```bash
python -m venv venv
```

## Activate Environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
streamlit run app.py
```

---

# 🎯 Real-World Applications

- Hospitals
- Clinics
- Healthcare Centers
- Medical Administration
- Healthcare Analytics
- Revenue Monitoring
- Resource Planning

---

# 🔮 Future Improvements

- PostgreSQL Integration
- Email Notifications
- SMS Alerts
- PDF Report Generation
- Electronic Health Records (EHR)
- Docker Deployment
- AI Disease Prediction
- Multi-Hospital Support
- Cloud-Native Architecture

---

# 💼 Resume Description

Developed a full-stack Hospital Management Dashboard using Python, Streamlit, SQLite, Plotly, and Scikit-learn. Implemented role-based authentication, appointment scheduling, doctor availability management, patient history tracking, audit logging, business intelligence dashboards, and machine learning-based forecasting. Built interactive analytics dashboards to support data-driven healthcare decision-making.

---

# 👨‍💻 Author

**Vardhan Reddy**

GitHub: https://github.com/VardhanReddy024

Project Repository:  
https://github.com/VardhanReddy024/hosptial_dashboard
