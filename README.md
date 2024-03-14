# TravelApp

Travel application

Welcome to TravelExplorer, a collaborative travel management system designed to bring together travel bloggers and agencies for seamless content creation and sharing. This README provides an overview of the application, including its architecture, features, and deployment process.

## GitHub Repository:

[TravelExplorer GitHub Repository https://github.com/MonicaC29/TravelApp-2024.git]

# 1.System Architecture

## Frontend Stack:

React for building the user interface

## Backend Stack:

The backend server will be built using the MERN stack:

- MongoDB for the database
- Express for the server
- Node.js for the server-side JavaScript runtime

## Deployment:

The application will be deployed using Render

# 2.System Requirements Specification

## Overview:

This application is designed to provide normal access and admin access.
TravelExplorer is a collaborative travel management system that allows travel bloggers to document and share their journeys. The app enables bloggers to add travel details, including dates and descriptions. The agency can log and change country information, descriptions and dates and delete countries.

# User Stories:

**Travel Blogger Stories:**

- As a travel blogger, I want to record my travel experiences by adding, description and date of the travel.

**Agency Stories:**

- As an agency, I want to view and edit travel blog posts from collaborating bloggers.

# Competitor Differentiation:

TravelApp-2024 distinguishes itself by fostering a symbiotic relationship between travel bloggers and the agency, allowing for efficient content management and promotion.

# Functional Requirements

## User Authentication:

The system shall provide secure user authentication for travel bloggers and the agency.

## Travel Documentation:

- Bloggers can add new travel entries with details and travel dates.

## Agency Content Management:

- The agency can log in and view a dashboard of travel blogger submissions.
- The agency can edit or delete travel blog posts.

# Non-Functional Requirements

## Performance:

Response time within 3 seconds
Support for 100 concurrent users

## Security:

Secure storage with encryption
Logging of unauthorized access attempts

## Reliability:

Availability during peak hours
Regular automated backups

## Mockups

Mockups showcasing application layout, design, and functionality will be provided.

# 6.Use Cases or Scenarios

# Use Case 1: Blogger Documenting a Trip

Scenario: A travel blogger logs in and documents a recent trip, adding dates.
Steps:
2.1 Blogger logs in with their credentials.
2.2 The blogger selects "Add New Trip" and fills in details.

# Use Case 2: Agency Curating Content

Scenario: An agency representative logs in and curates content from collaborating bloggers.
Steps:
2.1 Agency logs in with their credentials.
2.2 The agency views the dashboard with submitted blog posts.
2.3 The agency selects a post and edits if necessary.

# Error Handling

- The app will display clear error messages for users in case of authentication failure, data input errors, or system unavailability.

# Data Privacy and Compliance

- TravelExplorer adheres to data privacy standards, ensuring compliance with relevant regulations.
- Travel data is stored securely, and access is restricted to authorized personnel.

# Testing Requirements

Unit Testing
Comprehensive unit tests will be implemented for each module, ensuring the correctness of individual components.

# API Documentation

The TravelExplorer API provides endpoints for various functionalities within the application. Below is an overview of the main API endpoints and their usage:

## Authentication API:

**Endpoint:** `/api/auth`
Manages user authentication for travel bloggers and agency representatives. Supports secure login and authentication through various methods.

## Travel Entries API:

**Endpoint:** `/api/travel-entries`
Enables CRUD operations for travel bloggers to document their trips.

## Agency Dashboard API:

**Endpoint:** `/api/agency-dashboard`
Facilitates agency content management by providing access to a dashboard with features for viewing, editing and delete countries.

# Deployment Process

## Frontend Deployment:

- The deployment process involves publishing the app on Render.
- Regular updates and feature releases will be managed through version control.

# Backend Deployment:

Deploy the backend code to Render and configure environment variables, including the MongoDB connection string.

# Continuous Deployment:

Set up continuous deployment for the backend to automatically deploy changes from the repository.

## Admin Access:

The application includes an admin role with a designated username and password. The admin has the authority to correct country information, descriptions, and dates.

- Admin  
  Username: tee  
  Password: 12345

## User Access:

Normal users, such as travel bloggers, can register and only add new countries to the system.

- Normal  
  Username: Moni  
  Password: 123456

To modify data with CRUD operations, the user must use the admin password. Only the admin can authorize a normal user to become an admin like him. Normal users can register and access the system, but they can only add blogs and cannot use CRUD operations.
