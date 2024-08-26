
Property Rental Management System

INTRODUCTION

The property rental industry is constantly evolving, demanding efficient and user-friendly solutions for managing properties and bookings. Enter the Property Rental Management System (PRMS), a comprehensive software solution that streamlines operations and enhances the overall rental experience. A PRMS acts as a central hub for managing all aspects of property rental, from listing creation and marketing to booking management and tenant communication. This system automates tasks like scheduling viewings, collecting rent, and handling maintenance requests, freeing up landlords and property managers to focus on other critical aspects of their business. By providing a centralized platform for managing multiple properties, a PRMS fosters transparency and accountability. Landlords and tenants can access real-time information on bookings, payments, and property status, leading to improved communication and reduced disputes. In today's competitive rental market, a PRMS is an essential tool for maximizing efficiency, enhancing tenant satisfaction, and achieving sustainable growth.
 


Project Features and Characteristics

The proposed project Rental Management System Web Based consists of the following features:


•	Admin Booking Management:
Admins manage all booking activities, ensuring availability and accurate scheduling.
•	Profit Monitoring:
The system allows admins to track and analyze profit margins, aiding financial decision-making.
•	Payment Processing:
Facilitates secure payment collection and transaction tracking for room bookings.
•	Room Management:
Admins can add, delete, and update room details to maintain an accurate listing.
•	User-Friendly Booking:
Users can easily browse rooms and services, then book based on their specific needs




Project Scope

•	The Property Rental Management System is designed to streamline the management of property rentals by providing dedicated functionalities for both admin and users. On the admin side, the system enables comprehensive management of bookings, tracking of profit, processing of payments, and the ability to add or remove property listings. Admins play a crucial role in maintaining the efficiency of the system, ensuring that all data is up-to-date and accurate.
•	For users, the system offers a seamless experience through a well-organized interface. Users can navigate the homepage, explore services, view available properties, and access contact information. The booking process is simplified, allowing users to reserve properties based on their specific needs. This project aims to provide a convenient and efficient solution for property rentals, making it easier for users to book properties and for property managers to oversee their operations effectively.



Functional Requirements

User Requirements

•	Booking Status
•	Explanation: Allows users to view the current status of their room bookings. This could include information on whether a room is booked, available, or pending confirmation.

•	News Letter:
•	Explanation: A feature for subscribing to or managing newsletters. This could involve sending out updates, promotions, or news related to the service or business.



•	Manage Room Booking:
Explanation: Enables users to create, modify, or cancel room bookings. This involves selecting rooms, specifying dates, and confirming reservations.

•	Manage Payment:
Explanation: Handles payment processing for room bookings. This includes tracking payments, processing refunds, and managing payment methods.

•	View Profit:
Explanation: Provides a view of financial performance, including revenue and profit from room bookings. Useful for monitoring and analyzing the business's financial health.

•	Manage Users:
Explanation: Admin functionality for managing user accounts. This includes adding new users, updating user information, and deleting accounts.

•	Room Status:
Explanation: Displays the current status of rooms. This might show if rooms are occupied, available, or under maintenance.

•	Add Rooms:
Explanation: Allows users or administrators to add new rooms to the system. This involves entering details like room type, capacity, and amenities.

•	Update Rooms:
 
Explanation: Enables modifications to existing room details. This could involve changing room descriptions, updating availability, or adjusting rates.

•	Delete Rooms:
Explanation: Permits the removal of rooms from the system. This might be necessary if rooms are no longer available or if there are changes to the facility.


•	Users and Their Corresponding System Features General Users:
Booking Status: View the status of their own bookings.
Manage Room Booking: Make, modify, or cancel room bookings.
Room Status: See if a room is available or occupied (if applicable to the user’s role).





•	Administrative Users:

Booking Status: View the status of all bookings (for management purposes). News Letter: Create and manage newsletters, subscribe users to newsletters.
Manage Room Booking: Oversee and manage bookings, including those made by other users. Manage Payment: Process and track payments, handle refunds, and manage payment methods. View Profit: Access financial reports and profit data.
Manage Users: Create, update, or delete user accounts.
Room Status: Monitor the status of all rooms (for operational oversight).
 
•	Facility Managers:


Room Status: View current room status and manage room availability. Add Rooms: Add new rooms to the system.
Update Rooms: Modify details of existing rooms. Delete Rooms: Remove rooms from the system.



![12](https://github.com/user-attachments/assets/d5e9b9c0-af05-4727-9197-763276dae5e3)



Functional Requirements

User Requirements

•	Booking Status
•	Explanation: Allows users to view the current status of their room bookings. This could include information on whether a room is booked, available, or pending confirmation.

•	News Letter:
•	Explanation: A feature for subscribing to or managing newsletters. This could involve sending out updates, promotions, or news related to the service or business.



•	Manage Room Booking:
Explanation: Enables users to create, modify, or cancel room bookings. This involves selecting rooms, specifying dates, and confirming reservations.

•	Manage Payment:
Explanation: Handles payment processing for room bookings. This includes tracking payments, processing refunds, and managing payment methods.

•	View Profit:
Explanation: Provides a view of financial performance, including revenue and profit from room bookings. Useful for monitoring and analyzing the business's financial health.

•	Manage Users:
Explanation: Admin functionality for managing user accounts. This includes adding new users, updating user information, and deleting accounts.

•	Room Status:
Explanation: Displays the current status of rooms. This might show if rooms are occupied, available, or under maintenance.

•	Add Rooms:
Explanation: Allows users or administrators to add new rooms to the system. This involves entering details like room type, capacity, and amenities.

•	Update Rooms:
 
Explanation: Enables modifications to existing room details. This could involve changing room descriptions, updating availability, or adjusting rates.

•	Delete Rooms:
Explanation: Permits the removal of rooms from the system. This might be necessary if rooms are no longer available or if there are changes to the facility.


•	Users and Their Corresponding System Features General Users:
Booking Status: View the status of their own bookings.
Manage Room Booking: Make, modify, or cancel room bookings.
Room Status: See if a room is available or occupied (if applicable to the user’s role).





•	Administrative Users:

Booking Status: View the status of all bookings (for management purposes). News Letter: Create and manage newsletters, subscribe users to newsletters.
Manage Room Booking: Oversee and manage bookings, including those made by other users. Manage Payment: Process and track payments, handle refunds, and manage payment methods. View Profit: Access financial reports and profit data.
Manage Users: Create, update, or delete user accounts.
Room Status: Monitor the status of all rooms (for operational oversight).
 
•	Facility Managers:


Room Status: View current room status and manage room availability. Add Rooms: Add new rooms to the system.
Update Rooms: Modify details of existing rooms. Delete Rooms: Remove rooms from the system.


Use Cases 


![13](https://github.com/user-attachments/assets/e05fbe3f-3825-48e7-a6d5-30f037e4e448)


Data Dictionary


FIELD NAME	DESCRIPTION	DATA TYPE	LENGTH	SAMPLE 
id	Primary key	int unsigned	10	1
fullname	Full name	varchar	100	JohnRuzzel 
phone	Phone number	int	10	09052755830
email	Email address	text	N/A	Natojoshua22@gmail.com
date	Contact date	date	N/A	2024-08-26
approval	Approval status	varchar	12	Approved



FIELD NAME	DESCRIPTION	DATA TYPE	LENGTH	SAMPLE 
id	Unique identifier	int	10	1
name	Username	varchar	30	admin
pass	Password	varchar	30	1234



FIELD NAME	DESCRIPTION	DATA TYPE	LENGTH	SAMPLE 
id	Unique identifier	int	11	1
title	Title of the payment	varchar	5	Mr
fname	First name of the guest	varchar	30	John 
lname	Last name of the guest	varchar	30	Bacia 
troom	Type of room booked	varchar	30	Simple 
tbed	Type of bed booked	varchar	30	Simple
nroom	Number of rooms
booked	Int	11	
cin	Check – in date	date	-	2
cout	Check – in out	date	-	2024-08-25
ttot	Total amount	Double	8.2	2024-08-30
fintot	Final total amount	Double	8.2	900
mepr	Meal price	Double	8.2	550.00
meal	Meal type	varchar	30	Breakfast
btot	Total booking amount	double	8.2	1050.00
noofdays	Number of days	int	11	5
 




FIELD NAME	DESCRIPTION	DATA TYPE	LENGTH	SAMPLE 
id	Unique identifier	int	10	1
type	Room type	varchar	15	Suite
bedding	Room type	varchar	10	Double
place	Room location/area	varchar	10	North Caloocan 
cusid	Customer ID	int	11	500123



FIELD NAME	DESCRIPTION	DATA TYPE	LENGTH	
id	Unique identifier	int	10	1001
Title	Booking title	varchar	5	Mr.
FName	First name of the guest	text	-	John 
LName	Last name of the guest	text	-	Bacia 
Email	Email address	varchar	50	Natojoshua22@gmail.com
National	Nationality	varchar	30	Philippines 
Phone	Phone number	text	-	09052755830
TRoom	Type of room booked	varchar	20	Simple 
NRoom	Number of rooms
booked	varchar	2	2 
Meal	Meal preferences	varchar	15	None
cin	Check-in date	date	-	2024-08-25
cout	Check-out date	date	-	2024-08-26
stat	Booking status	varchar	15	Confirmed
nodays	Number of days booked	int	11	4
 

 









