# ✈️ British Airways Booking Completion Prediction

## 📌 Project Overview
This project builds a machine learning model to predict whether a customer will complete a flight booking, using behavioral and preference data provided by British Airways. It was developed as part of the British Airways Data Science Internship simulation on Forage.

## 🎯 Objective
To identify key factors influencing booking completion and use predictive modeling to support targeted marketing, resource optimization, and customer experience strategies.

## 🧠 Approach
- Explored and cleaned the dataset
- Engineered features such as `is_weekend`, `is_long_haul`, and `premium_intent`
- Encoded categorical variables using one-hot encoding
- Trained a Random Forest classifier using an 80/20 train-test split
- Evaluated model performance using precision, recall, F1-score, and feature importance

## 📊 Model Performance
- **Accuracy**: 0.85  
- **Precision**: 0.81  
- **Recall**: 0.85  
- **F1-score**: 0.82  
- **Top Features**: `purchase_lead`, `flight_hour`, `length_of_stay`, `flight_duration`, `num_passengers`

## 📈 Feature Importance Chart
*Top 10 features influencing booking completion based on Random Forest model.*

## 📁 Files Included
- `booking_model.ipynb`: Jupyter notebook with full workflow
- `README.md`: Project documentation
- `presentation.pptx`: Summary slide deck for stakeholders

## 💡 Business Impact
The model helps British Airways:
- Target high-intent customers with personalized offers
- Reduce booking drop-offs through proactive engagement
- Optimize lounge access and upgrade strategies

## 🛠️ Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Forage simulation dataset

---

Feel free to customize the chart path or add links to your notebook and presentation once they’re uploaded. Let me know if you want a version with badges or a more visual layout!
