#  Crop Recommendation System

##  Overview

This project is a Machine Learning-based system that recommends the most suitable crop based on soil nutrients and environmental conditions. It helps in making informed agricultural decisions.

---

##  Objective

To build a predictive model that suggests the best crop using parameters like Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall.

---

##  Dataset

The dataset includes the following features:

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature (°C)
* Humidity (%)
* pH value
* Rainfall (mm)

**Target Variable:** Crop name

---

##  Algorithm

**Random Forest Classifier**

An ensemble learning algorithm that uses multiple decision trees to improve accuracy and reduce overfitting.

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

##  Workflow

1. Load dataset
2. Data preprocessing
3. Train-test split
4. Model training (Random Forest)
5. Prediction
6. Model evaluation

---

##  Performance

* Achieved accuracy: **~99%**

---

##  Example

**Input:**
N=90, P=42, K=43, Temperature=20.8, Humidity=82, pH=6.5, Rainfall=200

**Output:**
Rice

---

##  How to Run

1. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
2. Open Jupyter Notebook:

   ```
   jupyter notebook
   ```
3. Run `crop_recommendation.ipynb`

---

##  Conclusion

The model successfully predicts suitable crops based on given conditions and can assist in improving agricultural productivity.

---

##  Future Improvements

* Web application integration
* Real-time weather data usage
* More advanced ML models

---

##  Author

Yash Pratap Singh
