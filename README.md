API Requirements:
Librarian APIs:
Create a new library user with an email and password.
View all book borrow requests.
Approve or deny a borrow request.
View a user’s book borrow history.
Library User APIs:
Get list of books
Submit a request to borrow a book for specific dates (date1 to date2).
View personal book borrow history.





Key Rules:
A book cannot be borrowed by more than one user during the same period. (There can be multiple books of same name but each book will be considered as unique)
Use Basic Authentication for all APIs.
Handle all edge cases, such as:
Invalid or incomplete requests.
Overlapping borrow dates.
Requests for non-existent users or books.

Database Schema:
You are expected to design and create the database schema required to support the functionality.

Bonus Features:
Allow library users to download all their data (borrow history) as a CSV file.
Implement JWT-based authentication instead of basic authentication.
Create clear and detailed API documentation (e.g., using Swagger or Postman).
