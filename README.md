# CivicConnect: Community Grievance Redressal System

## 🏙️ Overview
CivicConnect is a comprehensive digital platform (web and mobile) bridging the gap between citizens and local municipalities. It enables users to easily report infrastructural or community issues (e.g., potholes, broken streetlights, water supply problems) and tracks the resolution progress transparently through an automated pipeline.

## 🚀 Key Features
1. **Intuitive Issue Reporting:** Users can upload photos, add detailed descriptions, and tag the exact geolocation of the issue on an interactive map.
2. **Automated NLP Categorization:** A dedicated NLP Python microservice automatically analyzes the grievance description and routes it to the correct municipal department (e.g., Water Board, Public Works, Electricity) without manual intervention.
3. **Real-Time Status Tracking:** Citizens receive instant push notifications and real-time updates when an issue's status progresses from "Reported" to "In Progress" and finally to "Resolved."
4. **Admin Dashboard:** A secured portal for municipal workers featuring a heat map of regional issues, department filters, and status management tools.

## 🛠️ Tech Stack & Architecture
* **Mobile/Frontend:** React Native (Mobile), React.js (Web Admin)
* **Backend API:** Node.js, Express.js
* **Database:** PostgreSQL (with PostGIS for advanced geospatial querying)
* **AI/NLP Service:** Python, Scikit-learn (Text classification)
* **Deployment:** Containerized with Docker

## 🏃‍♂️ Running Locally
```bash
# Clone the repository
git clone https://github.com/Sensei-Ohmm/CivicConnect.git

# Start the backend and database services
docker-compose up --build
```

## 🌱 Why this project?
This project highlights an understanding of civic tech and digital governance, showcasing how modern architectures and machine learning can improve public service delivery and empower citizens.
