# PROJECT NAME: Townhouse

## Description.  

Townhouse is an innovative community engagement platform aimed at enhancing community and resident engagement within neighbourhoods. Our goal is to provide a transparent centralised digital space where residents can connect, communicate, and collaborate with one another and local government agencies and their local community.

Figma design: 

## GitHub Repositories
Frontend Repository:  Contains the code for the Townhouse user interface, built using web technologies.

Server Repository: Contains the code for Townhouse server responsible for Authentication, data storage, Groups, Markek place, Bulletin Board, Events and Community Directories.

Deployment Link: 

## Features 

## User Authentication and account management

### Account Creation

~ Allows users to register using Google, facebook or their email id.

~ Accepts user input and inserts new user details into the database after hashing the password for security

### Email Verification

~ When a user attempts to register with a new email address, the system sends a verification email containing a code.

~ Verifies that the user has access to the provided email address and prevent unauthorized account creation.

~ Uses Gmail API to send emails with a verification code generated based on the current time and a user ID.

### User Login

~ Allows registered users to log into their accounts using google, facebook or their email and password.

~ Verifies user credentials against stored hashed passwords and issues a JWT token for authentication.

### Protected Routes

~ Restricts access to certain routes based on user authentication, Uses JWT tokens to protect routes.

~ Ensure that only authenticated users can access sensitive or personal information.
