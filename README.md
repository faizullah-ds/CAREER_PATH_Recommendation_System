# CAREER_PATH_Recommendation_System
### **Career Recommendation System (Machine Learning)**

An AI-powered Career Recommendation System that suggests suitable career paths based on a user's **education level, specialization, skills, and certifications**. This project demonstrates a complete **end-to-end Machine Learning pipeline**, from data preprocessing to model deployment using **Streamlit**.

#### 🚀 Features

* Predicts recommended career paths using **Machine Learning**
* Handles categorical data with **Label Encoding** and **Ordinal Encoding**
* Interactive **Streamlit web application** with a clean, user-friendly UI
* Trained and evaluated using **Decision Tree** and **Random Forest** classifiers
* **Model persistence** using `joblib` for reuse

#### 🧠 Machine Learning Workflow

* **Data Cleaning & Exploration**
* **Feature Selection**
* **Encoding Categorical Variables**
* **Train-Test Split**
* **Model Training** (Decision Tree / Random Forest)
* **Model Evaluation**
* **Model Serialization**
* **Web App Deployment** using Streamlit

#### 📊 Dataset

**Input Features:**

* Education Level
* Specialization
* Skills
* Certifications

**Target Variable:**

* Recommended Career

#### 🛠 Tech Stack

* **Programming Language:** Python
* **Libraries:** pandas, numpy, scikit-learn, joblib, streamlit
* **Models:** Decision Tree, Random Forest Classifier
* **Deployment:** Streamlit

#### 📦 Project Structure

```
career-recommendation-system/
│
├── career.ipynb          # Jupyter Notebook (Model Training)
├── career.py             # Streamlit Application
├── career_model.pkl      # Trained ML Model
├── ordinal_encoder.pkl   # Ordinal Encoder
├── label_encoder.pkl     # Label Encoder
├── requirements.txt      # Project Dependencies
└── README.md             # Project Documentation
```

#### ▶️ How to Run the Project

1️⃣ **Clone the Repository**

```bash
git clone https://github.com/faizullah-ds/career-recommendation-system.git
cd career-recommendation-system
```

2️⃣ **Install Dependencies**

```bash
pip install -r requirements.txt
```

3️⃣ **Run the Streamlit App**

```bash
streamlit run career.py
```

#### 🖥 Streamlit App Preview

* Dropdown-based user inputs
* Instant career prediction

#### 📈 Model Performance

* Achieved high accuracy after tuning
* Evaluated using **Accuracy Score, Confusion Matrix, and Classification Report**

#### 📌 Learning Outcomes

* Hands-on experience with **categorical data encoding**
* Understanding of **classification algorithms**
* End-to-end **ML deployment experience**
* Improved **debugging and model evaluation skills**

#### 🔮 Future Enhancements

* Add more career categories
* Improve accuracy with **ensemble models**
* Deploy on **cloud platforms** (AWS / Azure / Streamlit Cloud)
* Include **resume-based career recommendations**

#### 👤 Author

**Shaik Mohammed Faiz** – Aspiring Data Analyst / Data Scientist

**🔗 LinkedIn:** [https://www.linkedin.com/in/shaik-faiz/](https://www.linkedin.com/in/shaik-faiz/)
**🔗 GitHub:** [https://github.com/faizullah-ds](https://github.com/faizullah-ds)

