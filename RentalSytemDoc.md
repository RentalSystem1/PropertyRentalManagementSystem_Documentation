
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


| FIELD NAME | DESCRIPTION                          | DATA TYPE | LENGTH | SAMPLE        |
|------------|--------------------------------------|-----------|--------|---------------|
| USER_ID    | Primary key, unique identifier for users        | Int    | 255    | GETGETG2344   |
| USERNAME     | Username for login    | Varchar    | 255     | idanan      |
| EMAIL    | User's email address           | Varchar   | 255       | idanan@gmail.com          |
| PASSWORD_HASH     | Encrypted password        | Varchar      | 255       | $3z$21$f5tHR8f9K7... |
| ROLE     | User role (e.g., employer, job seeker, admin)        | Enum      |        | employer |
| CREATED_AT    | Timestamp when the user was created        | Datetime      |        | 2024-08-20 12:34:56 |
| UPDATED_AT    | Timestamp when the user data was last updated        | Datetime      |        | 2024-08-21 08:45:12 |

### Table 2: JOB_POSTINGS

| FIELD NAME | DESCRIPTION                          | DATA TYPE | LENGTH | SAMPLE        |
|------------|--------------------------------------|-----------|--------|---------------|
| JOB_ID    | Primary key, unique identifier for job postings        | Int    | 255    | HFQHFQH3455   |
| EMPLOYER_ID     | Foreign key, references Users (employer)    | Int    | 255     | IGRIGRI4566      |
| JOB_TITLE    | Title of the job           | Varchar   | 255       | Software Engineer          |
| JOB_DESCRIPTION     | Detailed description of the job        | Text      |        | We are looking for a skilled developer... |
| LOCATION     | Location of the job        | Varchar      | 255       | Philippines, Caloocan City |
| CATEGORY    | Job category or industry        | Varchar      | 255       | Information Technology |
| SALARY_RANGE    | Salary range for the position        | Varchar      | 50       | ₱45,000 - ₱65,000 |
| CREATED_AT    | Timestamp when the job was posted        | Datetime      |        | 2024-08-20 09:15:30 |
| UPDATED_AT    | Timestamp when the job posting was last updated        | Datetime      |        | 2024-08-21 10:00:00 |

### Table 3: APPLICATIONS

| FIELD NAME | DESCRIPTION                          | DATA TYPE | LENGTH | SAMPLE        |
|------------|--------------------------------------|-----------|--------|---------------|
| APPLICATION_ID    | Primary key, unique identifier for applications        | Int    | 255    | JHSJHSJ5677   |
| JOB_ID     | Foreign key, references Job_Postings    | Int    | 255     | KITKITK6788      |
| JOB_SEEKER_ID    | Foreign key, references Users (job seeker)           | Int   | 255       | LJULGUL7899          |
| RESUME     | Uploaded resume file        | Blob      |        | Binary Data |
| STATUS     | Application status (e.g., applied, under review)        | Enum      |        | under review |
| APPLIED_AT    | Timestamp when the application was submitted        | Datetime      |        | 2024-08-20 14:22:45 |
| UPDATED_AT    | Timestamp when the application status was updated        | Datetime      |        | 2024-08-21 11:30:00 |

### Table 4: MESSAGES

| FIELD NAME | DESCRIPTION                          | DATA TYPE | LENGTH | SAMPLE        |
|------------|--------------------------------------|-----------|--------|---------------|
| MESSAGE_ID    | Primary key, unique identifier for messages        | Int    | 255    | MKVMKVM8900   |
| SENDER_ID     | Foreign key, references Users (sender)    | Int    | 255     | NLWNLWN9011      |
| RECIPIENT_ID    | Foreign key, references Users (recipient)           | Int   | 255       | OMXOMXO0122          |
| MESSAGE_TEXT     | Content of the message        | Text      |        | Hello, thank you for applying! |
| SENT_AT     | Timestamp when the message was sent        | Datetime      |        | 2024-08-21 09:15:00 |









Entity Relationship Diagrams
![14](https://github.com/user-attachments/assets/363b0b05-82b2-4ab7-8e66-b21990404b23)
 









