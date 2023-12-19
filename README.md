# Restaurant-Reservations-system
Develop a web application using servlets and JSPs following the MVC architecture pattern to manage restaurant reservations.
##
Model:

Create a Restaurant class with the following attributes:
name: String
address: String
phoneNumber: String
capacity: int

Create a Table class with the following attributes:
id: int
capacity: int
available: boolean

Create a Reservation class with the following attributes:
id: int
date: Date
time: Time
partySize: int
customerName: String
phoneNumber: String
tableId: int

View:

Design JSP pages for the following functionalities:

Home: Displays information about the restaurant, including name, address, phone number,
and available time slots for reservations.
Reservation Form: Allows users to enter their details, party size, and desired date and time
for the reservation.

Confirmation Page: Displays confirmation details for the successful reservation.

Error Page: Informs users of any errors encountered during the reservation process.

Controller:

Implement a Servlet class to handle user requests and process data:
Receive user input: Parse user input from forms and requests.
Validate data: Ensure user input is valid and complete.
Check availability: Verify if a table is available for the requested date and time.

Perform actions:
Create a new reservation.
Update a reservation.
Cancel a reservation.
Forward requests: Redirect to the appropriate JSP page based on the action performed.

Additional Features:

Implement database connectivity to store and retrieve information about restaurants,
tables, and reservations.
Allow users to modify existing reservations.
Display a list of upcoming reservations for the restaurant.
Implement user authentication and authorization to restrict access to specific
functionalities.
