# Assignments: Database Fundamentals

Student: Elima⭐

1. Designing and Implementing a Relational Database for a Bookstore- I designed a relational database for the "BookHaven" bookstore management system that eliminates data redundancy, ensures data consistency, and provides efficient data retrieval.
The "BookHaven" database schema adheres to the principles of normalization. By ensuring that the database design meets the criteria of 1NF, 2NF, and 3NF, we minimize redundancy, ensure data integrity, and optimize the efficiency of data retrieval. This structured approach helps maintain a clean and reliable database structure, making it easier to manage and query the data.

2. Constructing a Database for a Car Rental Service- I designed a relational database for "AutoRent," a car rental service, with a specific focus on implementing one-to-one relationships to efficiently manage vehicle and rental agreement details.
Detailed Analysis
The one-to-one relationship between Vehicles and Rental_Agreements ensures clear and efficient management of the car rental service, addressing various operational scenarios effectively.
Scenarios:
1)New Vehicle Additions- Vehicles can be added to the fleet without an associated rental agreement initially, with the RentalAgreementID in the Vehicles table remaining NULL until rented;
2)Rental Agreement Updates- When a vehicle is rented, a new rental agreement is created and the vehicle record is updated with the new `RentalAgreementID`, ensuring each vehicle has only one active rental agreement at a time;
3)Vehicle Availability Checks- By querying the `Vehicles` table for NULL `RentalAgreementID` values identifies available vehicles, while cross-referencing with the `Rental_Agreements` table tracks ongoing rentals.




