## Car Price Prediction System
This project is a Car Price Prediction System developed using Python, Flask, HTML, CSS, and Bootstrap. It utilizes a Linear Regression model trained on the Quikr Car Dataset to accurately estimate used car prices based on key features. The system combines a simple, responsive web interface with a reliable machine learning backend, enabling users to obtain real-time predictions with ease.


## Features
- Predicts used car prices using a trained Linear Regression model
- Web-based UI built with HTML, CSS, and Bootstrap
- Flask backend for handling user input and serving predictions
- Data preprocessing and feature engineering for improved model accuracy
- Clean and maintainable project structure


## Tech Stack
- Python
- Flask (Backend)
- HTML, CSS, Bootstrap (Frontend)
- Pandas, NumPy
- Scikit-learn (Model Training)
- Quikr Car Dataset


## Dataset
The system is trained on the Quikr Car Dataset, which includes important attributes such as:
- Name
- Company
- Year
- Kms Driven
- Fuel Type
  
These features are processed and used to train the Linear Regression model for price prediction.


## How It Works
1. The dataset is cleaned and preprocessed, handling missing values and converting textual fields into usable formats.
2. A Linear Regression model is trained using numerical and categorical features.
3. The Flask API receives user inputs from the web form (car name, company, year, kilometers driven, and fuel type).
4. The model processes the input and returns a predicted price.
5. The frontend displays the predicted value with a simple and responsive UI.


## Conclusion
The Car Price Prediction System delivers a practical and data-driven solution for estimating used car prices with accuracy and ease. By combining clean data preprocessing, a trained Linear Regression model, and a user-friendly Flask-based interface, the system enables users to make informed pricing decisions in real time. Its modular structure, responsive UI, and reliable backend make it an efficient tool for both learners and developers exploring machine learning deployment in web applications. This project demonstrates how predictive analytics can be seamlessly integrated into a modern web app to deliver meaningful, real-world value.

