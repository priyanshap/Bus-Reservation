# Bus-Reservation

This code implements a bus reservation system in C++. Here's a description of its main components and functionality:

## Classes:
customers: Stores customer information and registration details.
buses: Base class for bus information, including routes and stops.
vijayawada, guntur, tenali: Derived classes from buses for specific routes.


## Main functions:
Customer login: Allows adding, deleting, and modifying customer details.
Bus admin login: Enables adding, deleting, modifying, and displaying bus routes.


## Key features:
Customer registration: Customers can register for a bus on various routes.
Bus route management: Admins can add, delete, and modify bus routes.
Multiple routes: Supports buses from Vijayawada, Guntur, and Tenali to SRM AP University.


## Data structure:
Uses arrays to store customer and bus information.
Implements a struct for bus stops within the buses class.


## User interface:
Menu-driven interface for both customers and admins.
Allows selection of routes, buses, and stops.


## Functionality:
Customer registration checks for existing registrations.
Admins can view all registered buses for each route.
Supports modification of both customer and bus details.


## Limitations:
Uses fixed-size arrays, limiting the number of customers and buses.
Lacks file I/O for persistent data storage.
