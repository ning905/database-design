# Database Design

## Epic

A local cinema wants to allow people to book tickets online to see movies that are being shown in its various screens. These tickets should be delivered to customers via email. The cinema wants to keep a record of their customers and the tickets they purchase, as well as offer a regularly updated list of movies for them to choose from. A single screen might show multiple movies a day, and even the same movie at multiple times. The cinema will expand its number of screens in the future, so the potential for growth needs to be accounted for.

## User stories

- As a customer, so I can decide which movie I want to watch, I want to see a list of movies.
- As a customer, so I can decide when I want to watch, I want to see a list of showing time for a chosen movie.
- As a customer, so I can book tickets with friends, I want to book multiple tickets at once.
- As a customer, so I can receive my tickets, I want to provide my email address.
- As a customer, so I can book tickets for friends, I want the tickets to be sent to them by email.
- As a customer, so I can know when and where to watch the movie, I want to know the screen number, seat numbers and showing time.
- As an admin, so I can manage the movies shown at the cinema, I want to update the list of movies.
- As an admin, so I can manage the screens showing movies at the cinema, I want to update the list of screens.
- As an admin, I want  keep a record of customers.
- As an admin, I want keep a record of the tickets being purchased.

## Models

- user
- contact
- cinema
- screen
- movie
- booking
- ticket
- seat
- showing
