# 
RescueReady – Flood & Thunderstorm Preparedness Web Application

RescueReady is a Progressive Web Application (PWA) developed as part of my final year research project. The system is designed to enhance community preparedness for floods and thunderstorms in Sri Lanka by combining machine learning, real-time weather analytics, and GIS-based visualization to deliver localized disaster warnings and actionable emergency guidance.

🌩️ Project Overview

Sri Lanka frequently experiences floods and thunderstorms, yet existing early warning systems often lack locality-specific guidance and real-time accuracy. RescueReady addresses this gap by providing:

Real-time flood & thunderstorm predictions using ML

Location-based alerts (Push Notifications & SMS)

Live risk maps with GIS

Safe route navigation & nearby shelter information

Personalized emergency checklists

Offline accessibility via PWA technology

This system aims to improve disaster resilience and support timely decision-making for vulnerable communities.

🧠 Machine Learning Models

The backend includes trained ML models for:

Flood Prediction

Algorithm: Support Vector Machine (SVM)

Accuracy: 87.18%

AUC: 0.93

Techniques: SMOTE balancing, feature engineering

Thunderstorm Prediction

Algorithm: Logistic Regression (after undersampling)

AUC: 0.78

Features: Temperature, wind speed, humidity & lightning indicators

Models were trained on historical data from Sri Lanka Meteorology Department & Disaster Management Centre.

🛠️ Technologies Used
Frontend

React.js

Progressive Web App (PWA)

Leaflet / Mapbox for GIS Maps

Backend

Node.js & Express.js

Python (ML model training)

RESTful API integration

Database

MongoDB

Other Services

Push Notifications

SMS Gateway Integration

Geolocation API

Map Routing (Evacuation Paths)

📌 Key Features

✔️ Real-time alerts (SMS + Push Notifications)

✔️ Live danger zones mapped using GIS

✔️ ML-powered predictions for floods & thunderstorms

✔️ Offline mode support

✔️ Evacuation route guidance

✔️ Nearby safe shelters & emergency contacts

✔️ User-friendly dashboard with risk indicators

✔️ Secure authentication & responsive UI

📘 Research Background

This system is built as part of the research titled:

“RescueReady: An Application to Prepare for Floods and Thunderstorms”

The study evaluates community preparedness, analyzes meteorological datasets, and integrates ML predictions into a real-world web application to support disaster resilience efforts in Sri Lanka.
