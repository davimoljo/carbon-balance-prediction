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

## ⚙️ How to Run the Project (Reproducibility)
Due to the large size of the integrated datasets (>100MB, exceeding GitHub storage limits), the complete datasets and the interactive Jupyter Notebooks required to reproduce the ML results are hosted securely on Google Drive.
## ⚠️ Important Execution Step for Google Colab:
To run the notebooks seamlessly and without altering any directory paths, please download the project folder from the link provided and upload it directly to the root of your own Google Drive ("My Drive"). The script is natively designed to mount your Drive and locate the files automatically.

📥 **[CLICK HERE TO DOWNLOAD THE PROJECT FOLDER FROM GOOGLE DRIVE](https://drive.google.com/drive/folders/1fX9FBQgPGEcuXs3zou5eRAg1QY-2zDKg?usp=sharing)**

### Prerequisites
* **IDE:** [Visual Studio Code (VS Code)](https://code.visualstudio.com/) is highly recommended.
* **VS Code Extensions:** Ensure you have the **Python** and **Jupyter** extensions installed in VS Code to run the notebooks properly. Additionally, it is highly required to install the **Google Colab** extension. This allows you to run the heavy ML notebooks using cloud processing power, preventing any performance issues or overload on your local machine's hardware.
* **Python:** Version 3.8 or higher.

### Step-by-Step Execution
1. **Download and Extract:** Download the complete folder from the Google Drive link above and extract it on your local machine.
2. **Open the Project:** Open the extracted folder in Visual Studio Code.
3. **Install Dependencies:** Open the VS Code integrated terminal (`Ctrl` + `'`) and install the required libraries:
   ```bash
   pip install streamlit scikit-learn pandas numpy folium geopy yellowbrick
