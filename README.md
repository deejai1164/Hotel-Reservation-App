Hotel Reservation Application
A robust Java-based command-line application built using Object-Oriented Programming (OOP) principles to manage hotel rooms, customers, and reservations.

Key Features
Singleton Pattern: Implemented in the service and API layers to ensure consistent data management.

Polymorphism: Uses the IRoom interface to handle both standard and free rooms seamlessly.

RegEx Validation: Ensures customer emails follow the name@domain.extension format.

Reservation Logic: Prevents double-booking and offers a 7-day recommended search if no rooms are available for requested dates.

Project Structure
Model: Defines core entities like Customer, Room, and Reservation.

Service: Handles business logic and data storage using Java Collections.

API: Provides an intermediary layer between the UI and backend services.

UI: Interactive CLI with separate MainMenu and AdminMenu for users and staff.
