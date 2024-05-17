# Smart India Hackathon Workshop
# Date:17-05-2024
## Register Number:212223240095
## Name:Mohanram Gunasekar
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment

## Idea
The idea is to develop a website that helps users locate the nearest e-waste collection and recycling facilities. Additionally, the site will offer educational pop-ups on the harmful components of e-waste and their environmental and health effects. Users can input their old device models to earn credit points based on the amount of precious metals recovered if disposed of correctly.

## Proposed Solution / Architecture Diagram
![Screenshot 2024-05-17 094005](https://github.com/MohanramGunasekar/SIHPS/assets/139841812/641054d0-baeb-44cc-9ceb-4ed1ffb4dbe4)


## Use Cases
Locate E-Waste Facility

Actor: User
Description: User enters their location to find the nearest e-waste collection and recycling facilities.
Steps:
User inputs their zip code or allows location access.
The system uses Google Maps API to show nearby facilities.
User selects a facility to view details such as address, hours of operation, and types of e-waste accepted.
Educational Pop-Ups

Actor: User
Description: User clicks on an e-waste item icon to learn about its harmful components and effects.
Steps:
User navigates the site and clicks on an e-waste item (e.g., phone, battery).
A pop-up appears with information on harmful materials and environmental/health impacts.
User reads the information and can close the pop-up to continue browsing.
Device Model Input and Credit Points

Actor: User
Description: User inputs their old device model to earn credit points based on recoverable materials.
Steps:
User enters the make and model of their device.
The system assesses the device for recoverable precious metals.
The system calculates and displays potential credit points.
User disposes of the device correctly and submits proof.
User earns credit points added to their account.
User Account Management

Actor: User
Description: User creates and manages their account to track recycling efforts and credit points.
Steps:
User signs up and logs into their account.
User views their recycling history and accumulated points.
User redeems points for rewards.

## Technology Stack
Frontend
HTML/CSS/JavaScript: For basic structure and styling.
React.js: For building dynamic and responsive UI components.
Redux: For state management.
Backend
Node.js with Express.js: For server-side logic and API handling.
Python with Django (Alternative): For server-side logic and API handling.
Database
MongoDB: For storing facility data, user information, and device models.
PostgreSQL (Alternative): For relational data management.
APIs
Google Maps API: For location services and facility mapping.
Custom REST API: For handling device model inputs, user accounts, and credit points.

## Dependencies
Google Maps API: For geolocation and mapping services.
Material-UI or Bootstrap: For UI components and styling.
Mongoose: For MongoDB object modeling and schema management.
Django ORM (Alternative): For database interactions in a Django setup.
JWT (JSON Web Tokens): For secure user authentication.
Axios: For making HTTP requests from the frontend to the backend.
