Car Rental Management System

This is a car rental management system built using the MySQL. The system allows users to rent a car and return it when they are finished, 
while also allowing the management to keep track of the available cars and also track the location of the rented cars. We have even provided a Front-End using Streamlit.

Requirements:

Xampp
Python 3.x
Frontend: Streamlit 
Backend: MySQL
Databse: MariaDB

Installation:

1. Clone this repository:

2. Install streamlit using the command
pip install streamlit

3. Install mysql connector using the command
pip install mysql-connector-python

4. Install pandas for display of tables using the command
pip install pandas

5. Create a new MySQL database and import the car_rental.sql file to create the necessary tables.

Running the application:

1. Open Xampp, start MySQL and Tomcat server
2. Open the terminal and navigate to the folder where the application is stored.
3. Run the following command to start the streamlit server
streamlit run Home.py
4. The application will be displayed on the browser

Features:
1. Driver Info: Allows the management/user to know all the details of a car driver
2. Driver Contacts: Allows the management/user to know all the Contact Details 
3. Customer Info: Allows the Management to maintain all the details of the Customer.
4. Car Locations:  Allows the User/Management to view the Location of the Car.
5. Car Category: Allows the User/Management to Know the car that comes under a specific Category like Sedan, SUV, etc. This allows us to set a fixed price for a specific category of cars.
6. Car Details: Allows the management/User to know all the details of a specific Car.
9. Discount: Allows the management/User to know all the details of the Coupon Name and code for giving the discount and also the expiry date. 
10. Booking Details: Allows users to rent a car for a specified duration

Results:
On the front End you can perform CRED Operations on the databas


