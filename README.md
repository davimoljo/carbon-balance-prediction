# 🌱 Carbon Prediction Dashboard

## 📌 Overview
This project presents a Measurement, Reporting, and Verification (MRV) platform. It integrates spatial agricultural data with Machine Learning to predict carbon balances (emissions and sequestration) across Brazilian farms.

By combining the deterministic logic of the **CarbOnto** ontology (based on IPCC guidelines) with a **Multiple Decision Tree Regression** model, the system achieves highly scalable and accurate carbon estimations. This research is developed at the Federal University of Juiz de Fora (UFJF).

## 🚀 Key Features
* **Interactive MRV Dashboard:** Built with Streamlit for real-time visualization of carbon metrics.
* **High-Accuracy Inference:** The ML model internalizes exact mathematical rules from the ontological reasoner.
* **Spatial Context:** Dynamic map generation using Folium and Geopy to estimate farm boundaries based on area size (hectares).
* **Deterministic Mapping:** Data is grounded in physical realities using MapBiomas and validated against IPCC emission factors.

## 🛠️ Tech Stack
* **Frontend/Interface:** Streamlit
* **Machine Learning:** Scikit-Learn (Decision Tree Regressor), Yellowbrick (Evaluation)
* **Geospatial & Mapping:** Folium, Geopy
* **Data Manipulation:** Pandas, NumPy

## 📊 How it Works
1. **Location Filters:** Navigate through States, Cities, and specific Farm IDs.
2. **Carbon Metrics:** The system compares the historical reality (tCO2/ha) against the Artificial Intelligence prediction. It also calculates the total volume of CO2.
3. **Spatial Awareness:** Generates a proportional boundary circle on the map to represent the farm size.

## 🔮 Roadmap & Future Work
* **Explainable AI (xAI):** Implementation of SHAP (SHapley Additive exPlanations) to provide feature importance transparency. This will prove the model's reliance on domain-specific rules (e.g., land use) rather than environmental noise.

## 🎓 Acknowledgements
This project is part of an undergraduate research (Iniciação Científica) at the **Universidade Federal de Juiz de Fora (UFJF)**. 
