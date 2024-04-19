# Vehicle Rental Management System SRS Document

# Problem Statement
The purpose of the assignment is to develop a requirements analysis document for a car rental management system. The manual car rental system was fraught with difficulties, including database management, which was a manual process. The goal is to develop a system that keeps detailed records of both the cars and the customers, the duration they rent the car, as well as the type of car they rent. The system will be mainly designed for a small company that renders car rental services to customers. The system will have the ability to generate and print invoices for each successful transaction.
The Vehicle Rental Management System aims to streamline and modernize the entire rental process, from vehicle availability and booking to vehicle return and billing. This system will not only improve the agency's operational efficiency but also enhance the customer experience by providing a user-friendly online platform. Key issues that the VRMS seeks to address include:
1.	Inefficient Reservation Process:
The current process for making vehicle reservations is cumbersome, involving paper forms and manual record-keeping. This leads to errors and delays in confirming reservations.
3.	Limited Vehicle Visibility:
Customers struggle to access real-time information about vehicle availability, types, and pricing. This lack of transparency leads to customer frustration and lost business opportunities.
5.	Inaccurate Billing:
The manual billing process often results in errors, overcharges, or undercharges. This not only affects revenue but also damages the agency's reputation.
8.	Manual Inventory Management:
Managing a large fleet of vehicles manually is prone to errors, making it difficult to track vehicle maintenance, service schedules, and retirements.
10.	Customer Engagement:
Customer interactions and feedback collection are inefficient, making it challenging to address customer concerns and improve services.

# Proper Template Usage
To use the waterfall model in a vehicle rental management system, the following steps can be taken:
1. Requirements gathering: Gather all the requirements for the system from stakeholders, including the features and functionalities that the system should have.
2. System design: Design the system architecture, including the database schema, user interface, and system modules.
3. Implementation: Develop the system modules and integrate them into the system.
4. Testing: Test the system to ensure that it meets the requirements and is free of bugs and errors.
5. Deployment: Deploy the system to the production environment.
6. Maintenance: Provide ongoing maintenance and support for the system.

The waterfall model is a linear and strict set of stages during the development process. It follows a particular process model and can be used in the development of a car rental system. The iterative waterfall model is another development methodology that can be used in the development of a car rental management system. The system architecture can be designed using the SDLC framework, which describes all activities and processes in a software development project. The proposed system can be an online system that is fully integrated and automates manual procedures

# Team
1. AASTHA ARORA
2. AAYUSHA BHATIA
3. ABHISHEK RAJPUT
4. AYUSHI MAHAJAN
5. RAVINDRANATH TAMBADE

# Functional Requirements
1.	User Registration and Authentication:
	Customers and administrators should be able to register with valid information.
	Users must authenticate their identities through secure login mechanisms.
2.	Vehicle Management:
	Administrators should be able to add new vehicles, including details such as make, model, year, rental rate, and availability status.
	Administrators should be able to update and remove vehicles from the system.
	Vehicles should be categorized by type (e.g., cars, trucks) for easy search and selection.
3.	Reservation System:
	Customers should be able to search for available vehicles based on criteria such as location, date, time, and vehicle type.
	Customers should be able to make reservations by specifying pickup and return dates and times.
	Customers should have the option to view, modify, or cancel their reservations.
	Administrators should be able to view and manage reservations, including approving or rejecting requests.
4.	Rental and Billing:
	Customers should be able to rent vehicles based on approved reservations.
	The system should track rental periods accurately, calculate rental fees, and apply discounts or promotions as applicable.
	Customers should be able to make payments securely through various methods (credit card, online wallets, cash).
	Invoices should be generated, and customers should receive digital receipts.
5.	Customer Support:
	Customers should have access to customer support features for inquiries, assistance, and issue resolution.
	Administrators should be able to respond to customer inquiries and resolve issues efficiently.
6.	Reporting and Analytics:
	The system should generate reports on revenue, vehicle utilization, customer activity, and other relevant metrics.
	Analytics features should allow administrators to make data-driven decisions regarding fleet management and pricing strategies.

# Non-Functional Requirements
1.	Performance:
	The system should be capable of handling a minimum of 500 concurrent users without significant performance degradation.
	Response times for common tasks (e.g., searching for vehicles, making reservations) should be under 2 seconds.
2.	Security:
	User data, including personal information and payment details, must be securely stored and transmitted using encryption.
	Access control mechanisms must restrict access to sensitive features and data based on user roles (e.g., customer, administrator).
	The system should be protected against common security threats, including SQL injection, cross-site scripting (XSS), and data breaches.
3.	Reliability:
	The system should aim for a minimum uptime of 99.9%, with scheduled maintenance windows communicated to users in advance.
	Backup and disaster recovery procedures should be in place to ensure data integrity and system availability.
4.	Scalability:
	The system should be designed to scale horizontally or vertically to accommodate an expanding fleet of vehicles and increasing user load during peak periods.
5.	Usability:
	The user interface should be intuitive, responsive, and accessible on various devices (desktop and mobile).
	Error messages should be clear and user-friendly to assist users in resolving issues.

# Use Case Diagram
![image](https://github.com/aayushabhatia/Vehicle-Rental-Management-System-SRS-Document/assets/112889465/0b37b94f-2c7d-445a-858e-6e10f65a1255)

# Class Diagram
![image](https://github.com/aayushabhatia/Vehicle-Rental-Management-System-SRS-Document/assets/112889465/544733b2-dfcd-42e2-a143-c1a032fc6f7c)

# ER Diagram
![image](https://github.com/aayushabhatia/Vehicle-Rental-Management-System-SRS-Document/assets/112889465/33146a16-596b-48e5-ba8a-a7905b1fb937)

# Deployment Diagram
![image](https://github.com/aayushabhatia/Vehicle-Rental-Management-System-SRS-Document/assets/112889465/805f950f-d601-436c-bb63-10661cd65841)



