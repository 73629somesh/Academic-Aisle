TITLE:
Software Requirements Specification (SRS) for Academic Aisle Resale Online Marketplace
Objective:
This document outlines the software requirements for Academic Aisle, an online resale marketplace for educational products and services. The website will be accessible through a web browser. The website will allow users to create accounts, post advertisements for products and services, communicate with other users through messaging, and search for items based on various criteria.

Scope:
The scope of this project includes the development of the Academic Aisle online resale marketplace website, which will allow users to buy and sell educational products and services. The website will include features such as user registration, login, advertisement posting, messaging, search functionality, and payment processing. The website will also include administrative features such as user management, advertisement approval, and site maintenance.

Functional Requirements:
User Registration -
- Users should be able to register using their email address or phone number.
- Users should be required to provide a unique username and password during registration.
- Users should be able to select their preferred language from a list of available languages.
- Users should be required to provide their full name, phone number, and email address during registration.
- Users should be able to specify their preferred educational qualification level during registration.
- Users should be required to agree to the terms and conditions of the site during registration.
- Users should be able to upload a profile picture during registration (optional).
- Users should be able to select their preferred area of residence during registration.
- Users should be required to confirm their email address or phone number during registration (verification).
- Users should be able to edit their profile information after registration (optional).

3.2 User Login - 
- Users should be able to log in using their username or email address and password.
- Users should be able to log in using their phone number and password (optional).
- Users should be able to save their login credentials for future use (optional).
- Users should be able to reset their password if they forget it (forgot password feature).
- Users should be automatically logged out after a certain period of inactivity (session timeout).

3.3 Advertisement Posting -
- Registered users should be able to post advertisements for educational products and services.
- Advertisements should include a title, description, price, product/service category, area of residence, contact information, and product/service condition (new or used).
- Advertisements should include at least one image or video (optional).
- Advertisements should include a verification status (pending or approved) until they are approved by an administrator.
- Advertisements should have a start date and end date (optional).
- Advertisements should have an active status until they are sold or removed by the seller (optional).
- Advertisements should have a searchable status until they are sold or removed by the seller (optional).
- Advertisements should have a feature for sellers to renew their advertisements for a certain period of time at an additional fee (optional).
- Advertisements should have a feature for buyers to save advertisements for future reference (optional).
- Advertisements should have a feature for sellers to edit their advertisements after posting (optional).
- Advertisements should have a feature for sellers to delete their advertisements at any time (optional).
- Advertisements should have a feature for buyers to contact sellers through messaging after viewing an advertisement (optional).
- Advertisements should have a feature for sellers to track the views and clicks on their advertisements (optional).
- Advertisements should have a feature for sellers to track the sales and ratings of their products/services (optional).
- Advertisements should have a feature for buyers to rate and review the products/services they receive from sellers (optional).
- Advertisements should have a feature for sellers to respond to ratings and reviews from buyers (optional).
- Advertisements should have a feature for buyers and sellers to communicate through messaging about the product/service being sold or purchased (optional). 


3.4 Messaging System -
- Registered users who are logged in can send messages to other registered users who are also logged in using the messaging system provided by Academic Aisle.
 - Messages can include text, images, videos, audio files, documents, or links (optional). 
- Messages can include an attachment feature that allows users to attach files up to a certain size limit (optional).
 - Messages can include an emoji feature that allows users to add emojis while sending messages (optional).
 - Messages can include a read receipt feature that allows users to see whether the recipient has read the message or not (optional).
- Messages can include a delete message feature that allows users to delete messages they have sent or received from their inbox or sent items folder (optional).
- Messages can include a search message feature that allows users to search for messages based on keywords or message content (optional). 
- Messages can include an archive message feature that allows users to archive messages they want to keep but do not want them cluttering up their inbox or sent items folder (optional). 
- Messages can include an ignore message sender feature that allows users to block messages from specific senders without deleting them from their inbox or sent items folder (optional). 

Non Functional Requirements:
Security:
- The website should implement strong password policies for user accounts, requiring passwords with a minimum length of 8 characters, containing both uppercase and lowercase letters, numbers, and special characters such as !@#$%. Passwords should also be required to be changed every 90 days for added security against unauthorized access or account takeovers by hackers or cybercriminals using brute force attacks or password-guessing techniques.
- The website should implement two-factor authentication (2FA) as an optional security feature for user accounts, requiring users to provide a second form of identification such as a one-time code sent via SMS or email in addition to their password at login time, adding an extra layer of protection against account takeovers by hackers or cybercriminals using phishing attacks or social engineering techniques such as password guessing or phishing emails asking users to reveal their passwords under pretenses such as fake login pages or emails claiming to be from legitimate organizations such as banks or eCommerce websites asking users to update their account information by clicking on a link in the email or entering their password on a fake login page hosted on a malicious server controlled by the attacker instead of the legitimate organization's server controlled by the legitimate organization itself (phishing).



Reliability:
- The website should have an SSL certificate for secure data transmission between the user's browser and the server, protecting sensitive information such as passwords and credit card details from unauthorized access or theft by hackers or cybercriminals.
- The website should implement regular backups of all data to prevent data loss in case of any unexpected events such as server crashes or cyber-attacks.

Availability:
Server availability 24*7.

Maintainability:
The website should be easy to maintain and update, with clear documentation and support resources available. This will ensure that the website remains functional and effective over time, without requiring excessive resources or expertise.

Scalability:
The website should be scalable to sell other category products which can attract a large variety of customers and vendors who want to sell different products. This website can handle large user traffic.

Portability:
Web Application System will provide a portable User Interface ( HTML, CSS, JS) through which users will be able to access online websites. The system can be deployed to a single server, multi-server, to any OS, Cloud (Azure or AWS or GCP).
