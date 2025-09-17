-> Plant Disease Prediction using Random Forest

* Project Overview
This project focuses on -predicting plant disease status- (Healthy, Mild, Severe) using features such as plant type, leaf color, leaf spot size, humidity, and temperature**.  
The goal is to support early disease detection, enabling better crop management and improving agricultural productivity.  

A **Random Forest Classifier** was applied to train and test the dataset. Additionally, feature importance analysis was performed to identify key contributors to plant disease prediction.

---

Dataset
-> File used: `plant_disease_data.csv` , `plant_disease_dataset.csv`
->Features included:
  - `Plant_Type` – Type of plant (e.g., Corn, Rice, Potato)  
  - `Leaf_Color` – Observed color of the leaf  
  - `Leaf_Spot_Size` – Size of spots on leaves (numeric)  
  - `Humidity` – Humidity level (%)  
  - `Temperature` – Temperature (°C)  
  >Target Variable:** `Disease_Status`  
  - Healthy  
  - Mild Infection  
  - Severe Infection  

---

## 🛠️ Installation
Clone the repository and install required dependencies:  

```bash
git clone https://github.com/AditiG-code/plant-disease-prediction.git
cd Plant_Disease_Prediction
pip install -r requirements.txt
