# FixMyStreet - AI-Powered Public Infrastructure Repair Prioritization

FixMyStreet is a comprehensive solution for tracking, reporting, and prioritizing repairs of potholes in public infrastructure. This project integrates a mobile app, backend server, AI model, and frontend GUI to ensure that high-priority issues are handled swiftly and effectively. It leverages AI to determine the severity of potholes and provides teams with a centralized platform for monitoring and resolving cases.

This project demonstrates an end-to-end solution for public infrastructure management, making it easier for municipalities to handle urgent road repairs and improve public safety.


## Overview
This project automates and streamlines the process of identifying and resolving pothole issues:
- **Mobile App**: Captures images of potholes with geolocation data and submits them to the backend.
- **Backend Server**: Processes image data, triggers webhooks, and interacts with the AI model to determine severity levels.
- **AI Server**: Receives geotagged images from the backend and returns a threat level, allowing teams to prioritize repairs.
- **Frontend GUI**: Provides users with a real-time dashboard to view all reported cases, mark issues as resolved, and track ongoing repairs.

## Key Functionalities
- **AI-Driven Severity Rating**: Automatically assesses the threat level of each reported pothole.
- **Real-Time Updates**: WebSocket integration ensures updates are instantly synchronized across team members.
- **RESTful API & Webhooks**: A robust API enables interactions with the AI server and mobile app, while webhooks automate data retrieval from external services.
- **User Management**: Authentication and authorization for accessing and managing case statuses.
- **Location-Based View**: Direct integration with Google Maps to pinpoint each pothole's location for field teams.

## Tech Stack
- **Backend**: Node.js, Express, MongoDB, Multer, Webhooks
- **Frontend**: React, Bootstrap
- **AI Server**: Python, TensorFlow (or appropriate framework for model inference)
- **Database**: MongoDB for flexible document storage

## How to Use
1. Use the mobile app to report potholes by capturing images and submitting location data.
2. The backend processes the data and forwards the image to the AI server via a webhook for severity assessment.
3. Access the frontend dashboard to view cases sorted by threat level, update statuses, and view locations on Google Maps.
