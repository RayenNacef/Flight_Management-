# Flight Management Program
## Overview
This project is a Flight Management System developed for a travel agency. It is a Command-Line Application (CMD) written in C that allows the management of flights, including the addition of new flights, editing flight details, searching flights by date, and adding clients to a flight. The program stores the flight data in a binary file, making it persistent between executions.
## Features
- **Add a flight:** Input details about a flight such as destination, flight number, available seats, price, date, and time.
- *Display flight details:** Retrieve and display the description of a flight based on its flight number.
- **Edit flight details:** Modify flight details such as date, time, destination, available seats, and price.
- **Search flights by date:** Find and list flights scheduled on a specific date.
- **Add a client to a flight:** Register clients to a flight by storing their information and reducing the number of available seats.
## Files
- <span style="color:green;">Travel_agency.c: </span>The main C program that contains the logic for the flight management system.

## Data Structures
The program makes use of several custom data structures to represent flights, clients, and time information:
- <span style="color:green;">struct Date: </span> Holds the day, month, and year of a flight.
struct Horloge: Stores the flight time with hour and minute.
- <span style="color:green;">struct Horloge: </span> Stores the flight time with hour and minute.
- <span style="color:green;">struct Client: </span> Contains client information such as first name, last name, ID number, and phone number.
- <span style="color:green;">struct Flight: </span> Represents a flight, storing details like destination, price, available seats, flight number, flight date and time, and the list of clients booked on that flight.
## How to Run
### Prerequisites
- A C compiler (e.g., GCC).
- A terminal or CMD prompt to execute the program.
### Steps to Compile and Run
1. **Clone the repository or copy the source code** into your local environment.
2. **Compile the C program** using a C compiler like <span style="color:green;">gcc: </span>
bash

