# Secure-Web-Base-Online-Voting-System-SRS-
1. Introduction :

1.1 Purpose 
The purpose of this document is to provide a detailed description of the requirements for Secure Wed-Based Online Voting System. it outlines the system's functionalities. constraints, and overall behavior to guide developers and stakeholders during development.

1.2 Scope
The Online Voting System is a Web-based platform that allows registered users to cast their votes securely over the internet.
It will include:
1. Voter interface for casting votes
2. Admin panel for managing elections
3. Real-time vote counting

1.3 References 
1. IEEE SRS Documentation Standards
2. Web Development Documentation (HTML,CSS ,JavaScript)
3. Django Framework Documentation

1.5 Overview
This document describes system features, external interface, and design constraints.

2. Overall Description :

2.1 Product Perspective
The system is a standalone web application that interacts with a database server. It will be accessible through a web browser.

2.2 Product Functions
The system will perform the following functions:
1. User registration and login
2. Authentication and authorization
3. Display candidates
4. voting functionality
5. Admin management system
6. Result generation

2.3 User Classes and Characteristics

Voter:
1. Basic computer and internet knowledge
2. Can register, login, and vote
Admin:
1. Advanced user with system control
2. Manages elections, candidates, and users

2.4 Operating Environment

1. Web Browser(Chrome, Firefox, Edge)
2. Operating System: Window / Linux / MacOS
3. Server: localhost or Cloud Server
4. Backend: Python(Django)

2.5 Design and Implementation Constraints

1. System must be web based
2. Secure authentication required
3. Database must ensure data consistency
4. One user can vote only once

2.6 Assumptions and Dependencies

1. User have internet access
2. Server remain available during voting
3. Basic cybersecurity measures are implemented

3. System Features:

3.1 User Registration
Description:
Allow new users to register in the system.

Inputs:
Name, Email, and Password

Output:
Successful registration message

3.2 User login
Inputs:
Email, Password

Output:
Access to dashboard

3.3 Vote Casting
Description:
Users can cast their vote.

Constraints:
One user can vote only once

Output:
Vote confirmation

3.4 Candidate Management(Admin)
Description:
Admin can add, update, or delete candidates.

3.5 Election Management
Description:
Admin can create and manage elections.

3.6 Result Management
Description:
System automatically calculates and displays results

4. External Interface Requirements

4.1 User Interface
1. Simple and user friendly design
2. Responsive layout
3. Dashboard for users and admin

4.2  Hardware Interface
1. Standard computer
2. Internet connectivity

4.3 Software Interface
1. Web browser
2. Database
3. Backend framework

4.4 Communication Interface
Internet(HTTP/HTTPS protocol)

5. Non-Functional Requirements

5.1 Security 

1. Password encryption
2. Secure login system
3. Protection against unauthorized access

5.2 Performance

1. Fast response time
2. Efficient data processing

5.3 Usability

1. Easy Navigation
2. Minimal user training required

5.4 Reliability

1. System should operate without failure
2. Data should not be lost

5.5 Availability
System should e available during election time

6. Future Enhancements

1. OTP verification system
2. Biometric authentication
3. Mobile application version
4. Blockchain based voting

7. Conclusion
This SRS document defines all functional and non functional requirements for the Secure Web-Based Online Voting System. It Serves as a foundation for system design and implementation.



