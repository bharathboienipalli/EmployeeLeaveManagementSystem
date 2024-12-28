# Employee Leave Management System

## Overview

The Employee Leave Management System is a Spring Boot-based web application designed to streamline the management of employee leave requests within organizations. It features user authentication, an approval workflow for leave requests, and leave balance tracking, enhancing efficiency and transparency in handling time-off requests.

## Features

- **User  Authentication**: Secure login for employees and administrators.
- **Leave Application**: Employees can submit leave requests with details such as leave type, start date, end date, and reason.
- **Approval Workflow**: Managers can review, approve, or reject leave requests with comments.
- **Leave Balance Tracking**: Employees can view their available leave balances and history of leave taken.
- **Notifications**: Email notifications for leave request submissions and status updates.
- **Admin Dashboard**: Administrators can manage users, view leave statistics, and generate reports.

## Technologies Used

- **Backend**: Spring Boot
- **Database**: MySQL (or any other preferred database)
- **Security**: Spring Security for authentication and authorization
- **Email**: JavaMailSender for sending notifications
- **Build Tool**: Maven or Gradle
- **API Documentation**: Swagger for API documentation

## Getting Started

To get a local copy up and running, follow these steps:

1. **Clone the repository**:
   git clone https://github.com/bharathboienipalli/EmployeeLeaveManagementSystem.git


   2.**Navigate to the project directory**:
   cd employee-leave-management-system

   3.**Build the project**:
   mvn clean install

   4.**Run the application**:
   mvn spring-boot:run
