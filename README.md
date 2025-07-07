# SMART-FARMING-DATABASE-MANAGEMENT-SYSTEM-IN-DBMS
Smart Farming Database Management System (SFDMS) is a browser-based agricultural management platform built using HTML, CSS, JavaScript, and IndexedDB. It provides a digital solution for farmers and administrators to manage essential farm operations through a centralized system that simulates a smart farm environment.
The project supports the collection, tracking, and analysis of data related to farms, fields, crops, soil conditions, weather, irrigation, harvests, and sensors. Each component is modular and user-friendly, designed to reflect real-world farming needs in a structured digital format.

🔧 Key Features

🌾 Crop Management – Add and update crop types, planting dates, and field assignments.

🌱 Field & Farm Modules – Define and manage farm locations, areas, soil types, and field statuses.

💧 Sensor Management – Install and record readings for soil moisture, temperature, pH, and more.

🚿 Irrigation System – Simulate irrigation systems and track water usage per field.

🧮 Harvest Logs – Record crop yields, quality ratings, and harvest dates.

📊 Analytics Dashboard – Generate reports on farm performance, water consumption, and yield comparisons.

📡 IoT Simulation – Sensor and irrigation data mimic real-time input using IndexedDB.

This project was developed for the CGB1221 – Database Management Systems course and demonstrates how front-end technologies can simulate backend operations like CRUD, normalization, and relational data handling in a smart farming context.

🚀 How to Use

1.Download or Clone the Repository

git clone https://github.com/Ashwinvimal/sfdms.git
cd sfdms

2.Run the Application

Open index.html in your preferred browser.
No backend/server setup is required — everything runs locally.

3.Interact with the Dashboard

Navigate through tabs: Farms, Fields, Sensors, Irrigation, Harvests, and Analytics.
Fill out forms to simulate adding farms, installing sensors, logging irrigation events, and recording harvest data.

4.Analyze Results

Use the Analytics tab to:

View water usage by farm,
Compare crop yields,
Analyze field health based on sensor inputs.

5.Extend the System

While the current version uses IndexedDB, you can integrate it with:

Flask + MySQL for a full backend,
IoT sensors for real-time monitoring,
Cloud storage or mobile apps for advanced scalability.
