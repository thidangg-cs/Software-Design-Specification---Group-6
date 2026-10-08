# Software-Design-Specification---Group-6
Movie Theater Ticketing Service

Description of the Software Architecture
1. Presentation Layer
This is the part that users interact with through a web browser. Customers can search movies, view showtimes, select seats, purchase tickets, and manage their accounts. Employees, managers, and administrators have different interfaces based on their roles.The system can be accessed through computers, tablets, and smartphones.
2. Application Layer
This layer contains the main business logic of the system. It handles user accounts, movie searches, screenings, seat selection, ticket purchases, payments, refunds, loyalty information, and policies. It also handles the 5-minute seat hold and maximum 20 tickets per transaction.
3. Data Layer
The database stores users, movies, screenings, seats, tickets, payments, and purchase information. The application layer reads and updates this information when customers make purchases or when employees and managers update the system.
4. External Services
The system communicates with external services for payment processing, email/SMS notifications, authentication, CAPTCHA/bot protection, movie reviews, and currency conversion. These services allow the movie ticketing system to provide functions that are outside the main application.
