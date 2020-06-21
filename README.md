# Movie-Renting-MongoDb-Express-Nodejs-----SAKSHAM

Movie Renting System using Express , MongoDB and NodeJS

PROBLEM STATEMENT:
Create the backend for a video rental store application using Node and Express:
1. A user of the application would be the store salesman.
2. An admin user of the application is the store owner.
3. A customer of the application would be the person renting the video
The application should support different configurations for supporting multiple environments. These environments could differ in the:
1. Databases used
2. Private keys for encryption

APIs
1. Customer
    1. Get the list of all customers
    2. Get the details of a specific customer
    3. Create a new customer
    4. Delete an existing customer
    5. Update the details of a customer
2. Movie
    1. Get the list of all movies
    2. Get the details of a specific movie
    3. Add a new movie
    4. Delete an existing movie
    5. Update the details of a movie
3. User
    1. Get the details of the current user
    2. Register a new user
4. Rental
    1. List the rental details of currently rented out movies sorted by dateOut desc
    2. Get the rental history of a specific movie
    3. Customer rents a movie
    4. Customer returns a movie
5. Authentication
    1. Login a user

Middlewares
	1. Only admin can perform delete operations
	2. Implement JWT for authentication

Testing (Integration)

1. Auth middle
2. One happy path and one non happy path for
    1. GET, 
    2. GET /:id, 
    3. POST /:id, for any one resource

Model data validation, input validation and error handling must also be implemented. Use of logging, pagination is not mandatory but extra points for handling these.

Example model
	1. Customer
		1. Name
		2. Phone
	2. Movie
		1. Title
		2. numberInStock
		3. dailyRentalRate
	3. Rental
		1. Customer
		2. Movie
		3. dateOut
		4. dateReturned
		5. rentalFee
		6. damageCharges
	4. User
		1. Name
		2. Email
		3. Password








