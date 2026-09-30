# Railway Reservation System

A Python desktop application demonstrating a complete railway ticket-booking workflow with a graphical interface, MySQL persistence, seat management, fare calculation, and digital ticket generation.

## Overview

This project combines application development, database integration, UI design, and document generation into a single end-to-end system.

## Features

- Train search by source and destination
- Class-based filtering
- Fare calculation
- Seat availability and booking
- Unique PNR generation
- Digital ticket generation
- QR-code generation
- PNG / PDF ticket export
- Booking history
- MySQL database integration

## Architecture

`text
Tkinter UI
    ↓
Application Logic
    ↓
Booking / Seat Management
    ↓
MySQL Database
    ↓
Ticket + QR Generation
`

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Python |
| UI | Tkinter / CustomTkinter |
| Database | MySQL |
| QR | qrcode |
| Images | Pillow |
| Version Control | Git + GitHub |

## Project Structure

`text
Railway-Reservation-System/
├── main.py
├── database/
│   ├── connect.py
│   └── trains.sql
├── assets/
├── tickets/
├── utils/
│   ├── qr_generator.py
│   └── pnr_generator.py
├── requirements.txt
└── README.md
`

## Local Setup

`bash
git clone https://github.com/sudipta200507/Rail-Reservation-System.git
cd Rail-Reservation-System
pip install -r requirements.txt
python main.py
`

## Engineering Concepts

- CRUD-style database operations
- Relational data modelling
- Desktop GUI development
- Input validation
- Booking workflows
- Unique identifier generation
- File generation
- Python package integration

## Future Direction

Authentication, payment integration, live train data, an admin dashboard, and a web/mobile frontend.

## Author

**Sudipta Roy**  
B.Tech CSE (AI & ML)
