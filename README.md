# BookMyTicket

An application to book movie tickets.

## Description

The application is designed for two types of users: Theatre Staff and Customers.  
- **Theatre Staff**: Can create, update, and delete movies, and manage shows for any day.  
- **Customers**: Can browse movies, register for an account, and book tickets for available shows.  

The application is built using **Django**, with **PostgreSQL** as the database.  

#### Application Structure
The project contains the following apps:  
- `accounts`: Manages user authentication and registration.  
- `staff`: Handles movie and show management for theatre staff.  
- `booking`: Facilitates the ticket booking process for customers.  

Steps to set up:  
- Add app names in `INSTALLED_APPS`.  
- Replace the default user model with a custom user model.  
- Update database configuration in a `.env` file.  

---

## Getting Started

### Dependencies

Ensure you have the following installed:  
- Python 3.x  
- Pip  
- Virtualenv  
- Django and required packages (e.g., `psycopg2-binary`, `crispy-bootstrap5`, `django-crispy-forms`, `python-dotenv`)  

Install dependencies using:  
```bash
pip install -r requirements.txt
