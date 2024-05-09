# PROJECT NAME: Townhouse

## Description.  

Townhouse is an innovative community engagement platform aimed at enhancing community and resident engagement within neighbourhoods. Our goal is to provide a transparent centralised digital space where residents can connect, communicate, and collaborate with one another and local government agencies and their local community.

Figma design: 

## GitHub Repositories
Frontend Repository:  Contains the code for the Townhouse user interface, built using web technologies.

Server Repository: Contains the code for Townhouse server responsible for Authentication, data storage, Groups, Marketplace, Bulletin Board, Events and Community Directories.

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

## Neighborhood Groups

~ Neiborhood Groups allows residents to connect with their neighbors and engage with their local community. 

~ After user authentication, joining a neighborhood group is mandatory

~ User can create a group by entering name and location fields or user can join a an existing group based on their residential area.

~ Group discussions, polls, and file sharing functionalities within each group.


## Marketplace

~ users can explore local businesses and services within their neighbourhood

~ Business owners can advertise their services by creating listings with descriptions, images, and contact information

~ User can interact with listing and can make payments securely through payment gateways(eg. Paypal, Stripe)

~ User can not see groups in other zipcodes


## Bulletin Board

~ User can see post, announcements, and discussions on the bulletin board

~ Users can post texts, images and links on the bulletin board and can like, share and comment on the posts

~ Users have the ability to pin important posts for easy access.

~ The data for posts is stored in the database using an api call

~ The data retrieved will be displayed in chronological order on the bulletin board


## Events

~ resident can view the events in his neighbourhood and filter events by date, category, or location.

~ Event organiser can create and manage events

~ Events are displayed with details (title, date, location, description). Users can RSVP to events.

~ Event creation form UI consists fields for title, date, location, description

~ Integration with calendar applications for easy scheduling and reminders


## Community Directory

~ Users can access a directory of local services, and amenities such as hospital, police, fire municipalities within his neighbourhood.

~ Users can search and browse a categorised directory of services. 
Directory entries display contact information and details.

~ Users can submit new listing for approval.

~ The directory UI provides the functionality to search and apply category filters.

~ Backend API manages the directories entries and subimissions.