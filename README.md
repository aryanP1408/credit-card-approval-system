# credit-card-approval-system
A machine learning project that predicts credit card approval status 

This project was developed during my internship at **Clevered**.

##  Features
* **Data Preprocessing:** Handles missing values and uses `LabelEncoder` to transform categorical data into numerical formats.
* **Machine Learning Model:** Utilizes a Random Forest Classifier to evaluate applications based on 16 different features.
* **Desktop GUI:** An interactive interface built with Tkinter, allowing users to input application details and get real-time predictions.
* **Text-to-Speech:** Integrated voice assistance using `pyttsx3` for an interactive "About Us" section.
* **Model Serialization:** Uses `pickle` to save and instantly load the pre-trained model without needing to retrain it on every launch.

##  Dataset
The model is trained on the `CC_data.csv` dataset, which contains **690 records** and **16 features**. 
Key features evaluated by the model include:
* Age
* Debt
* Education Level
* Years Employed
* Prior Defaults
* Credit Score
* Annual Income

##  Tech Stack & Tools
* **Programming Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Random Forest Classifier, train_test_split, LabelEncoder)
* **GUI Framework:** Tkinter
* **Utilities:** Pickle (model saving), Pyttsx3 (text-to-speech)

##  Results
The Random Forest Classifier achieved robust predictive performance:
* **Testing Accuracy:** ~86.8%

