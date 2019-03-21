# MoviePass-Model

#OVERVIEW 
MoviePass is an app that allows customers see an unlimited amount of movies each month. For this application there will be three models: Customer, Movie, and Ticket. 

# MODELS 
 * A customer should have a name, phone number, address, and email. (P.S. This is a good place for validations.)
 * A movie should have a title and description. 
 * A ticket should have a customer (id), a movie (id), and a date(timestamps)

#RELATIONSHIPS 
 * A customer can see many movies each month. 
 * A movie can be seen by many customers each month. 
 * Each time a customer reserves a trip to the movies, they will be issued a ticket. This ticket will include the customer's name and the particular movie they are viewing. 

#DELIVERABLES 
 * A customer should be able to join the application via a New Customer Form (new/create)
 * A customer should be able to select new tickets from the available movies. (new/create or update) (COLLECTION SELECT)
 * A customer should be able to cancel their ticket (delete)
 * The application should list all of the movies available, and link to individual show pages (index/show)
 * The customer should be able to see all of their tickets, which are linked to the particular movie. (show)
 * A customer should be able to update their profile information. 

 If you feel like it, you can attempt to do the bonus goals. 
 