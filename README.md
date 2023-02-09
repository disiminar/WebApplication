# C#, ASP.NET Core, Entity Framework, Microsoft SQL Server Web Application
This is a food delivery service web application based on ASP.NET Core and Entity framework, using the Model-View-Controller (MVC) as an architectural pattern.
This project was created during the third semester of Computer science degree as a coursework at the university. 

### Available entities:
- Guest
- User
- Courier
- Administrator

### Capabilities of the following entities:
- Guests can only register their own account and view general information about the service, such as the home page.
- Users can order selected products from the catalog (add them to the cart or proceed to payment immediately), change their personal data in the profile, monitor the status of one or another order, view the history of their orders.
- Courier has all the same capabilities as a regular user. But during registration, he has to provide some additional data to get this role in the system. This also includes the ability to accept and change orders their status, for example, "in progress" or "ready to delivery".
- Admin manages this entire system. He has access to everyone
pages, including those that are hidden from other users. Such pages are: data on all completed orders with all details (type of goods sold, their date of sale, quantity, within a certain period of time, which of the couriers fulfilled it, etc.), information on all users who registered in the system, a page for editing the existing product catalog. It is obvious that all the given data can be changed by him both through the web application and directly in the database.
