# ☀️ Clustering Solar Energy Production Zones

This project uses unsupervised machine learning techniques to identify and cluster solar energy production zones based on various environmental, geographical, and energy generation parameters. The goal is to group regions with similar solar production potential to support energy planning, infrastructure development, and investment strategies.

---

## 📌 Problem Statement

Solar energy production varies across geographic locations due to factors such as sunlight intensity, weather patterns, and elevation. This project aims to:
- Cluster geographic zones based on their solar energy production characteristics.
- Identify high-potential zones for renewable energy investments.
- Visualize clusters for easier interpretation and decision-making.

---

## 🧠 Techniques Used

- **Data Cleaning & Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Unsupervised Learning**
  - K-Means Clustering
  - Hierarchical Clustering (optional)
  - DBSCAN (optional)
- **Dimensionality Reduction** (e.g., PCA or t-SNE)
- **Geospatial Visualization** (e.g., Plotly, Folium, or Geopandas)

---

## 🗂️ Dataset

The dataset includes information like:
- Data Through Date: The date up to which the data in the dataset is valid or relevant.
- Project ID: A unique identifier for each solar power project in the dataset.
- Interconnection Date: The date when the solar power project was connected to the grid or power distribution system.
- Utility: The utility company or organization responsible for managing the power grid and distributing electricity.
- City/Town: The location of the solar power project (city or town).
- County: The administrative division within the state where the solar project is situated.
- Zip: The postal code or ZIP code corresponding to the project’s location.
- Division: A further geographical subdivision within the state (if applicable).
- Substation: The electrical substation where the solar power project is connected to the grid.
- Circuit ID: The unique identifier for the circuit within the substation that the solar project is connected to.
- Developer: The entity or organization responsible for developing and implementing the solar power project.
- Metering Method: The method used to measure and record the solar energy production (e.g., net metering, gross metering).
- Estimated PV System Size (kWdc): The estimated size of the photovoltaic (PV) system in kilowatts direct current (kWdc). This represents the total capacity of the solar panels.
- PV System Size (kWac): The actual size of the PV system in kilowatts alternating current (kWac). This accounts for system losses and efficiency.
- Estimated Annual PV Energy Production (kWh): The projected annual energy production from the PV system in kilowatt-hours (kWh). This estimate considers factors like solar irradiance, panel orientation, and efficiency.
- Energy Storage System Size (kWac): If applicable, the size of any energy storage system (such as batteries) connected to the solar project, measured in kilowatts alternating current (kWac).
- Number of Projects: The total count of solar power projects represented in the dataset.

---
