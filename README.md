# 📖 Project Description
This project is a web-based Event Booking System built using Flask (Python) and PostgreSQL database. It allows users to view events, register, login, and book tickets, while an admin can manage events and users.  The system works like an online platform where people can browse upcoming events (concerts, festivals, etc.) and reserve tickets easily.

# ⚙️ Technologies Used
Frontend: HTML, CSS

Backend: Python (Flask Framework)

Database: PostgreSQL

Security: Password hashing using Werkzeug

Other: psycopg2 (database connection)
# 🧠 How the System Works
Database Connection

The system connects to PostgreSQL using psycopg2.

Database details (name, user, password) are taken from environment variables.

2. Database Initialization

If tables don’t exist → they are created using schema.sql.

If no events exist → sample events are automatically added.

Sample artists and events are inserted.

3. User Roles
👤 Normal User

Register account

Login

View events

Book tickets

See dashboard

🛠 Admin

Default admin is created:

Email: admin@example.com

Password: admin123

Admin can:

Manage events

View bookings

Control system

# 🌐 Main Features
🔐 Authentication

User registration

Login system

Passwords are securely hashed

# 🎟 Event Management

View available events

Each event has:

Name

Date

Venue

Price

Tickets available

🧾 Booking System

Users can book tickets

Ticket availability is tracked

Booking updates database

📬 Contact Form

Users can send messages

Messages are stored in database (contact_submissions table)

# 📊 Dashboards

User Dashboard: Shows bookings and events

Admin Dashboard: Manage system data





This project is a complete event booking web system that demonstrates:

Backend development (Flask)

Database handling (PostgreSQL)

User authentication

Real-world booking logic
