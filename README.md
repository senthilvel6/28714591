Setting up the system:

1)Execute the  SQL scripts to create the tables-customers,flights,reservation
reservation table consist of foreign keys which references the customer and flight tables
2)Populated the tables with sample data using the provided SQL insert scripts.
3)Create the PL/SQL procedures by executing the scripts provided.


Using the system:

1)Use the ManageReservation procedure to insert,delete reservations by passing appropriate parameters which will use upd_seats procedure to change seat availablity.
2)Use the new_Customer procedure to add new customers to the database.Once they added they can book seats
3)Use the upd_seats procedure to adjust the number of available seats on a flight after a reservation is made and also added a parameter value which efficiently increment/decrement the available seats based on booking/cancelling
4)use the search procedure to check all details of flight 
This system allows efficient management of flight reservations, customer records, and flight availability, ensuring that data integrity is maintained throughout the database.
