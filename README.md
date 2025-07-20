# NYC EV Charging Station Optimization

**End-to-end data analytics project: Optimizing the placement of EV charging stations based on taxi mobility patterns in New York City.**

---

## 🚀 Background

As electric vehicle (EV) adoption rapidly grows in major cities like NYC, transportation companies need data-driven strategies for **efficient and targeted deployment of charging stations**. This project uses NYC taxi trip data as a mobility proxy to **identify optimal locations and estimate the number of EV chargers needed with high precision**.

---

## 🧩 Problem Statement

> **How can we determine the optimal number and placement of EV charging stations in NYC based on taxi fleet dropoff/pickup patterns, in order to maximize operational efficiency and customer satisfaction?**

---

## 🔑 Analysis Pipeline

1. **Data Cleaning**  
   - Handling missing values, anomalies, outliers, time conversion, and zone-to-borough mapping.
2. **Exploratory & Spatial Data Analysis**  
   - Trip distribution analysis, trip duration, activity per zone/borough, and hotspot identification for dropoff/pickup.
3. **Charger Demand Simulation**  
   - Calculating charger needs per zone/borough, across multiple charging durations and probability scenarios.
4. **Optimal Placement: Cluster Charging Station Modeling**  
   - Clustering chargers (5 units per cluster), simulating demand vs. supply, and recommending top locations.
5. **Visualization & Interactive Dashboard**  
   - Folium map, heatmap, choropleth, and dashboard for charger demand.

---

## 🏆 Key Insights & Business Recommendations

- **Cluster Charging Stations (5 units per location, 50kW each)** are recommended to minimize bottlenecks and maximize charging efficiency.
- **Data-driven charger distribution:** Manhattan and Queens are the top priorities (highest demand hours and dropoff density).
- **Scalable strategy:** Number and location of chargers are aligned with real-world supply/demand trends, allowing easy expansion as EV adoption grows.
- **Interactive dashboard and maps** enable clear communication and data-driven decisions for all stakeholders.

---

## 📑 References & Data Sources

- [NYC TLC Trip Records (Open Data)](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- [NYC Open Data: EV Charging Stations](https://data.cityofnewyork.us/Transportation/Electric-Vehicle-Charging-Stations/nc67-uf89)
- [NYC Taxi Zones GeoJSON](https://github.com/nycehs/NYC_geography)
- [Uber Movement](https://movement.uber.com/cities/new-york)
- Academic studies: Urban EV charging network optimization (San Francisco, Beijing, etc.)

---

## 🛠️ Requirements

- Python >= 3.8
- pandas, numpy, geopandas, folium, scikit-learn, seaborn, matplotlib, plotly

> Install dependencies with:  
> `pip install -r requirements.txt`

---

## 📈 How to Run

1. Clone this repo.
2. Make sure all datasets are present in the repository root.
3. Run the main notebook `capstone02.ipynb` or the modular scripts provided.
4. All results and interactive visualizations (HTML, CSV) will be generated in the root directory.

---

## 🙋 Contributors

- Muhamad Dimas Wijaya Kesuma – Data Analyst, E-Mobility Strategy

---

## 📝 License

MIT License

---

> This project is developed to support efficient and sustainable EV infrastructure in urban environments, and serves as a benchmark for data-driven charging station placement strategies.
