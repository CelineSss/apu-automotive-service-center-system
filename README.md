# APU Automotive Service Center System
A group Java desktop application developed for the **Object-Oriented Development with Java** module at Asia Pacific University of Technology & Innovation (APU).

The system supports role-based operations for **Customers, Counter Staff, Technicians, and Managers**. Key functions include appointment booking and management, technician assignment and service-status updates, payments, feedback, user management, service pricing, and reporting.

## Technologies
- Java
- Java Swing
- Object-Oriented Programming (OOP)
- File Handling
- UML
- System Testing
- Email Notification
- Excel Report Export

## System Features
- Role-based login and access control for Customers, Counter Staff, Technicians, and Managers
- OTP email verification during login
- Customer appointment viewing and feedback functions
- Counter-staff appointment booking, technician assignment, appointment viewing, and payment processing
- Technician appointment viewing and service-status updates
- Manager user management, service-price configuration, feedback viewing, and reporting
- Reports for appointments, revenue, services, payment status, customer insights, and technician performance
- Email notifications and Excel report export

## My Contribution
This was a four-member group academic project. My individual contributions as **Siew Zhen Lynn** included:

### Java Development
- Developed counter-staff appointment booking functions
- Developed counter-staff appointment-viewing functions
- Developed customer appointment-viewing functions
- Developed technician appointment-status update functions
- Developed manager reporting functions

### Documentation and Presentation
- Documented the counter-staff appointment booking and viewing modules
- Documented the customer appointment-viewing module
- Documented the technician appointment-status update module
- Documented the manager reporting module
- Explained Object-Oriented Programming concepts used in the system
- Contributed to the additional-features and conclusion sections
- Presented the Object-Oriented Programming concepts, appointment module, and reporting module

### Testing
- Participated in group system testing and checking of all system functionalities

## How to Run
1. Clone or download this repository.
2. Open the project in a Java IDE, such as Apache NetBeans.
3. Ensure a compatible Java Development Kit (JDK) is installed.
4. Run the project from the IDE.
5. The project stores sample data in text files inside the `src/data/` folder.

## Demo Login Credentials
The passwords stored in `src/data/users.txt` are encrypted or hashed. Use the plain-text demo credentials below to log in.

| Role | User ID | Password |
| Customer | CUST001 | password@123 |
| Technician | TECH001 | techpass@123 |
| Counter Staff | STAFF01 | staffpass@123 |
| Manager | MGR001 | managerpass@123 |

## OTP Email Testing
The system sends a one-time password (OTP) email during login.

The email addresses in `src/data/users.txt` are safe demo addresses and will not receive emails.

To test OTP delivery locally:

1. Open `src/data/users.txt`.
2. Choose one demo account, for example `TECH001`.
3. Replace only that account's email address with your own email address.
4. Save the file.
5. Run the application and log in with the same account.

Example:

```text
TECH001,Ahmad Ali,your-email@example.com,375d1619,Technician
```

Use these login details:

```text
User ID: TECH001
Password: techpass@123
```

Before committing or pushing changes to GitHub, change your email address back to the safe demo address:
TECH001,Ahmad Ali,ahmad.ali@example.com,375d1619,Technician


## Privacy Notice
This repository uses fictional demo accounts and sample data only.
Do not commit or upload:
- Real email addresses
- Personal information
- Email passwords, app passwords, API keys, or tokens
- Confidential data

## Academic Project Notice
This repository is shared for portfolio and learning purposes. It was completed as a group academic project. The listed contributions describe my individual work as **Siew Zhen Lynn**.