# AppSystem Project - https://appsys.kzprojects.site/

This is a basic web-based application for streamlined recruitment! It allows job seekers to effortlessly browse and apply for positions, while offering recruiters efficient tools to manage applications and track open positions in real-time.

Log in credentials:
- Username: user
- Password: 123456

Functionalities for Job Seekers:
- Apply for an open job position;
- Browse all open job positions;

Functionalities for Recruiters or HR:
- Logging in as a recruiter opens an additional menu /HR menu/;
- Browse and manage all applications;
- Open/close job positions;

Additional functionalities:
- Upon submission of an application, the system automatically sends a confirmation email to the applicant. The email is sent to the email address provided in the application form.
- When a new job position is opened, the system automatically creates a LinkedIn post at this address: https://www.linkedin.com/in/appsys-project-24768a2a9/recent-activity/all/

Additional Info About the Project Execution:

I have executed this project using the MVC design pattern with Java and Spring framework. The base layer of the UI is a free Bootstrap template that has been customized with additional CSS, HTML, and Bootstrap components. As this project serves educational purposes, the user interface is not optimized for mobile devices.

Data exchange between the frontend and backend is managed by Thymeleaf.

The project utilizes **Maven** as the build tool and is deployed on an **AWS EC2 Linux virtual machine**. Network communication is secured via **HTTPS**.

The functionalities for sending emails and creating posts on LinkedIn are implemented using the **Google and LinkedIn APIs**.


