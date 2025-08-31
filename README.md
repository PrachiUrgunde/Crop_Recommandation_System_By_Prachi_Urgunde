🌱 Crop Recommendation System Using Soil and Weather Data

📌 Project Overview

The Crop Recommendation System leverages Machine Learning to recommend the most suitable crop for cultivation based on soil nutrients (N, P, K), pH, temperature, humidity, and rainfall. This system helps farmers make data-driven decisions, optimize resource usage, and promote sustainable agriculture.

✨ Features

✔️ Predicts the best crop for given soil and weather conditions

✔️ Built with Random Forest Classifier for high accuracy

✔️ Lightweight and easy to use

✔️ Can be extended to a web or mobile application


📂 Dataset

Source: Kaggle – Crop Recommendation Dataset

| Feature     | Description                         |
| ----------- | ----------------------------------- |
| N           | Nitrogen content in soil (kg/ha)    |
| P           | Phosphorous content in soil (kg/ha) |
| K           | Potassium content in soil (kg/ha)   |
| temperature | Average temperature (°C)            |
| humidity    | Relative humidity (%)               |
| ph          | Soil pH                             |
| rainfall    | Rainfall (mm)                       |
| crop        | Target crop label                   |


📊 Records: 2200+

🎯 Goal: Recommend the most suitable crop.



🛠️ Preprocessing Steps

Handle missing values & remove duplicates.

Encode categorical target (crop) using LabelEncoder.

Feature scaling with StandardScaler (for KNN/SVM).

Train-test split: 80/20.



🤖 Machine Learning Model

Algorithm: Random Forest Classifier (best accuracy)

Other Models Tested: Decision Tree, KNN, XGBoost

Evaluation Metrics: Accuracy, Confusion Matrix, F1-score



4️⃣ Input Parameters

Provide soil and weather details → Get recommended crop 🌾


🌍 Future Scope

🔹 Deploy as a Web/Mobile App for farmers

🔹 Integrate real-time weather APIs

🔹 Add fertilizer recommendation module

🔹 Extend to crop disease detection


👩‍💻 Author

Prachi Urgunde | Crop Recommandation System | Sustainable Agriculture 
