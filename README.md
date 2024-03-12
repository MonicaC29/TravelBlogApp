# TravelApp

Travel application

Welcome to TravelExplorer, a collaborative travel management system designed to bring together travel bloggers and agencies for seamless content creation and sharing. This README provides an overview of the application, including its architecture, features, and deployment process.

## GitHub Repository:

[TravelExplorer GitHub Repository https://github.com/MonicaC29/TravelApp.git]

# System Architecture

## Frontend Stack:

React with Next.js framework

## Backend Stack:

MongoDB for the database
Express for the server
Node.js for server-side JavaScript runtime

## Deployment:

Vercel

https://travel-ckull8w87-monicac29s-projects.vercel.app

## Overview:

TravelExplorer enables travel bloggers to document their journeys with photos, videos, and descriptions. Agencies can curate and share this content on social media, fostering collaboration between bloggers and the travel industry.

# User Stories:

## Travel Blogger Stories:

Record travel experiences
Manage a wishlist of places to visit

## Agency Stories:

Curate and share travel content
View, edit, and publish blog posts

# Functional Requirements

## User Authentication:

Secure authentication for bloggers and agencies
Password reset functionality

## Travel Documentation:

Add new travel entries
Manage wishlist of places to visit

## Agency Content Management:

View, edit, and publish blog posts

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

# Use Cases or Scenarios

Detailed use cases for blogger documentation and agency content curation will be outlined.

# Error Handling

Clear error messages and guidance for users in case of authentication failure, input errors, or system unavailability.

# Data Privacy and Compliance

Adherence to data privacy standards and regulations, with secure storage and restricted access.

# Testing Requirements

Unit Testing
Integration Testing
User Acceptance Testing (UAT)

# API Documentation

Overview of main API endpoints for authentication, travel entries, wishlist, and agency dashboard.

# Accessibility Considerations

Implementation of accessibility standards for usability by individuals with disabilities.

# Deployment Process

## Frontend Deployment:

Build Frontend: Run npm run build in the frontend directory.
Push Build to Repository: Ensure the build directory is included in the repository.
Create Static Site on Heroku: Deploy the pre-built frontend to Heroku as a static site.

# Backend Deployment:

## Set Up MongoDB:

Choose a managed MongoDB service or set up an external service.

## Create Backend Service on Heroku:

Deploy the backend code to Heroku and configure environment variables, including the MongoDB connection string.

# Continuous Deployment:

Set up continuous deployment for the backend to automatically deploy changes from the repository.
