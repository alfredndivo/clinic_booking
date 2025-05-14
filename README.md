# 🏥 Clinic Booking System (MySQL)

## 📌 Description
A complete relational database system for managing a clinic's appointments, doctors, patients, and departments.

## 🛠️ Features
- Patients can book appointments with doctors.
- Doctors can belong to multiple departments.
- Tracks appointment statuses and schedules.

## 🧩 Tech Stack
- MySQL (only)
  
## 🔗 ERD Diagram
[Patients]───┬────────────┐
             │            │
             │            ▼
             │        [Appointments]───┬────────────┐
             │                         │            │
             ▼                         ▼            ▼
         [Doctors]               [Departments]   [Doctor_Department]


## 📁 Contents
- `clinic_booking.sql` → SQL file with all `CREATE TABLE` statements and constraints.
