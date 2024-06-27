# Screening Process for Applicants

This repository contains the backend components for a screening process designed to evaluate applicant submissions. The system leverages an AI engine to analyze applications and automates the notification process to inform applicants of their status.

## High-Level Architecture

1. **Application Submission**: Applicants submit their data through an API Gateway, which forwards the information to the backend server.
2. **Data Storage & Retrieval**: The backend server interacts with a database to store and retrieve application data and analysis results.
3. **Application Analysis**: The backend server sends the application data to an AI engine for evaluation.
4. **Analysis Results**: The AI engine returns the analysis results to the backend server.
5. **Notification Trigger**: The backend server initiates the notification system to send an email to the applicant.
6. **Email Notification**: The notification system sends an email to the applicant regarding their application status.
