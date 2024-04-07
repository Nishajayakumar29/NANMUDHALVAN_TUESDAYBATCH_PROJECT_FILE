Bus Reservation System using Python and Django
This repository contains a Bus Reservation System implemented using Python and Django, 
providing a web-based platform for managing bus ticket bookings.

Features:

User Authentication: Users can register, log in, and log out securely.
Bus Search: Users can search for available buses based on source, destination, and date.
Ticket Booking: Users can book bus tickets for their desired route and date.
Reservation Management: Admins can view and manage bus reservations, including editing and canceling bookings.
Responsive Design: The system is designed with a responsive layout to ensure compatibility across various devices.
Installation
To run the Bus Reservation System locally, follow these steps:

1. Clone this repository to your local machine:

code : git clone https://github.com/Nishajayakumar29/NANMUDHALVAN_TUESDAYBATCH_PROJECT_FILE

2. Navigate to the project directory:


code : cd bus-reservation-system

3. Create a virtual environment:


code : python3 -m venv env

4. Activate the virtual environment:

=> On Windows:


code : env\Scripts\activate

=>On macOS and Linux:

code : source env/bin/activate

5. Install the dependencies:

code : pip install -r requirements.txt

6. Perform database migrations:


code : python manage.py migrate

7. Create a superuser (admin):


code : python manage.py createsuperuser

8. Run the development server:


code : python manage.py runserver

9. Access the application in your web browser at http://127.0.0.1:8000/

Usage: 

Navigate to the home page to register or log in.
Use the bus search feature to find available buses based on your preferred route and date.
Book tickets by selecting your desired bus and providing necessary details.
Admins can log in and access the admin panel at  http://127.0.0.1:8000/ admin to manage reservations.