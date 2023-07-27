# FMLiveStreaming

This repository contains the prototype for Fremantles Live Streaming system, an internal tool designed for managing live streams, users, and shows. 

## Project Overview

This system provides a new and more efficient method for managing live streams, user accounts, and access to shows for Fremantle. Utilizing the Microsoft Azure tech stack, including Azure B2C and Cosmos DB to handle user management and data storage.

## Structure

The project is primarily composed of several HTML and CSS files, providing a prototype of the user interface. The pages include:

- `login.html`: Allows users to log into the system.
- `register.html`: Enables new users to create an account.
- `dashboard.html`: A user-friendly interface for administrators to manage live streams and users.
- `settings.html`: Enables users to manage their account settings.
- `show-catalog.html`: Lists the available shows for a user.
- `password-reset.html`: Lets users reset their forgotten password.


## Requirements
These requirements cover a range of functionalities and potential use-cases for the system:

- Live Stream Management: Implement a system for efficient and user-friendly live stream management.
- User Management: Provide a flexible user management system that allows for the assignment of users to multiple shows. 
- User role assignment (such as admin, viewer, etc.), and user auditing (including bandwidth and login history).
- Project Auditing: Implement a system to view bandwidth history per project or show.
- Integration with External Systems: Ensure compatibility with Fremantle’s SSO system, as well as the ability to handle users with different email service providers or logins.
- User Authentication: Implement a secure authentication system that includes functionalities such as password reset and user activation upon approval.
- User Notifications: Implement a system for sending automatic emails for important user events such as password reset, account activation, and access approvals.
- Admin Approvals: Create an approvals system with different levels of administration.
- Azure Integration: Seamlessly integrate the system with Azure B2C for user management and Cosmos DB for data storage.




## Continued Development

This prototype will eventually be integrated with Azure B2C for user management and authentication, and Cosmos DB for data storage. More features and functionalities will be added to the project.