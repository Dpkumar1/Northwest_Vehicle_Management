# Capstone_Team01
NorthWest Vehicle Management System
Project Overview – Vehicle Management System 
This project is a full-stack Vehicle Management System developed using Python (Flask) and SQLite, designed to track and manage vehicles, fuel usage, maintenance activities, and generate reports for administrative oversight. It supports both admin and user roles, allowing personalized access and secure operations.

🔧 Core Features:
🧑‍💼 User Authentication: Sign up, login, logout, role-based access control (Admin/User)

🚘 Vehicle Management: Add, edit, deactivate vehicles; track VINs, mileage, fuel type, and purchase dates

⛽ Fuel Tracking: Users can log fuel refills, mileage, and cost

🛠 Maintenance Logs: Track service types, costs, and dates for each vehicle

📊 Analytics Dashboard: Visual charts for fuel usage and maintenance costs per vehicle

📥 Report Generation: Monthly and annual reports exported to Excel format with summaries

🧾 Audit Logging: All actions performed by admins are logged in the system

📢 Alert System: Admins get alerts for maintenance due or high fuel usage

🧠 Built With:
Flask (Python web framework)

Flask-SQLAlchemy (ORM)

Werkzeug for password hashing

Matplotlib and Pandas for generating analytics and Excel reports

SQLite database (lightweight, ideal for testing and deployment)

HTML + Jinja templates for frontend rendering

🎯 Use Cases:
Fleet tracking for logistics companies or delivery services

In-house vehicle usage monitoring for enterprises
