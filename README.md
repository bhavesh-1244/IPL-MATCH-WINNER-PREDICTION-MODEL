**🏏 IPL Match Winner Prediction**

A Machine Learning project that predicts the winning probability of an IPL match using real-time match conditions. The project includes full EDA, model building, and a Streamlit web app for live predictions.

📌 Project Overview

This project predicts which team is more likely to win an IPL match based on factors like:

>> Batting team
>> Bowling team
>> City
>> Target score
>> Current score
>> Overs completed
>> Wickets fallen

The model is trained using past IPL data. The web interface (built with Streamlit) provides an easy way to input match conditions and instantly get win probabilities.

**📊 Features
✔ Exploratory Data Analysis (EDA)**

Performed EDA to identify important patterns such as:

>> Run rate trends
>> Wicket fall impact
>> Target difficulty
>> Venue impact
>> Team performance

✔ Machine Learning Model

>> Preprocessed IPL dataset
>> Feature engineering (CRR, RRR, runs left, balls left, etc.)
>> Trained classification model
>> Saved model using pickle

✔ Streamlit Application

The app.py file provides an interactive UI where users can:

>> Select teams
>> Select host city
>> Enter match details
>> Get winning probabilities instantly


🛠 Technologies Used
>> Python
>> Pandas, NumPy
>> Scikit-Learn
>> Streamlit
>> Matplotlib / Seaborn (for EDA)
>> Pickle

**🚀 How to Run the Project**
**1️⃣ Clone the repository**

git clone https://github.com/bhavesh-1244/IPL-MATCH-WINNER-PREDICTION-MODEL.git
cd IPL-MATCH-WINNER-PREDICTION-MODEL

**2️⃣ Install required libraries**

pip install -r requirements.txt

**3️⃣ Run the Streamlit app**

streamlit run app.py



**👨‍💻 Developed By**

**Bhavesh Meshram**
B.Tech in Data Science
