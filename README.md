## Railway-reservation-in-django
**Train Booking System**
This Django-based web application serves as a simple train booking system. It provides functionality for users to view available trains, register, log in, book tickets, and manage bookings. Admin users can add new trains and view passenger details for each train.

**Features**
User Authentication: Users can register, log in, and log out. Authentication is implemented using Django's built-in user authentication system.

Train Management: Admin users can add new trains, including details such as source, destination, departure time, available seats, train name, and price.

Booking: Authenticated users can search for available trains based on source and destination, select a train, and book tickets. The system ensures that available seats are updated upon successful booking.

My Bookings: Authenticated users can view their booking history, including details of the trains they have booked.

**Usage**
Clone the repository to your local machine.

bash
Copy code
git clone https://github.com/your-username/Railway-reservation-in-django.git
Navigate to the project directory.



bash
Copy code
**pip install -r requirements.txt**
Apply migrations to set up the database.

bash
Copy code
**python manage.py migrate**
Create a superuser account for admin access.

bash
Copy code
**python manage.py createsuperuser**
Run the development server.

bash
Copy code
**python manage.py runserver**
Access the application in your web browser at http://localhost:8000.

Admin users can log in using the superuser credentials and access the admin interface at http://localhost:8000/admin.



**Contributing**
Contributions are welcome! Feel free to open issues or submit pull requests to improve the functionality, user interface, or documentation.
