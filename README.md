# Final Year Project

## A Searchable and Verifiable Data Protection Scheme for Scholarly Big Data

This repository contains a JSP-based web application for searchable and verifiable data protection in scholarly data sharing environments.

### Features
- User roles: data owners, consumers, and administrators
- File upload, search, download, and verification workflows
- Domain management and access control
- Block verification and attacker detection
- JSP pages for frontend interaction and Java servlets for backend logic

### Structure
- `*.jsp` — application pages for different users and workflows
- `css/`, `js/`, `images/`, `Gallery/` — frontend assets
- `WEB-INF/` — deployment descriptors, libraries and configuration
- `database/Database.sql` — schema and initial data for the project

### Usage
1. Deploy this application to a compatible servlet container (e.g. Apache Tomcat)
2. Configure the database connection in the application settings
3. Access the application through the browser and register users for each role

### Notes
This is an academic project with a focus on protecting and verifying shared scholarly data.
