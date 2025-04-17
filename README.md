# ✈️ Online Air Ticket Booking System (Java Console Application)

This is a simple console-based **Online Air Ticket Booking System** developed in Java. It allows users to register, login, view available flights, and book tickets. The system also maintains basic user session handling and seat availability tracking.

## Features

- User registration and login
- Flight management (preloaded flights)
- Search flights by destination
- Book tickets with seat availability check
- View logged-in customer details
- Logout functionality

## Sample Flights Preloaded

- `AI101`: New York → London, Seats: 5, Price: $450.00  
- `BA202`: Paris → Tokyo, Seats: 3, Price: $800.00  
- `DL303`: Sydney → Dubai, Seats: 4, Price: $620.00  

## Project Structure

All the code is contained within a single `Main` class:

- `Flight`: Represents an individual flight
- `BookingSystem`: Handles flight listings, bookings, user registration, login/logout
- `main()`: Runs the interactive console menu for users

## Getting Started

### Requirements

- Java 8 or higher
- A Java IDE or terminal with `javac` and `java`

### Run the Program

1. Save the code in a file named `Main.java`
2. Open terminal and compile:
   ```bash
   javac Main.java
   ```
3. Run the application:
   ```bash
   java Main
   ```

## Screenshots

```
=== Online Air Ticket Booking System ===
1. Login
2. Register
3. Exit
Choose an option: 2
Enter username: john
Enter password: 1234
Registration successful! You can now log in.

...

1. View Available Flights
2. Book a Ticket
3. View Customer Details
4. Logout
Choose an option: 1
Enter destination to view flights: London
1. Flight: AI101, From: New York, To: London, Seats: 5, Price: $450.0
```

