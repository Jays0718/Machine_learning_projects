

---

# 🎓 Course Recommendation System

Welcome to the **Course Recommendation System**, a smart web application designed to help students navigate their academic journey by recommending the most suitable courses based on their individual profiles. Built with **Flask** and powered by the **XGBoost** machine learning algorithm, this application achieves an impressive accuracy of **93.70%**!

---

## 🚀 Table of Contents
- [Project Overview](#project-overview)
- [🎯 Goal of the Project](#goal-of-the-project)
- [✨ Features](#features)
- [🛠️ Tech Stack](#tech-stack)
- [📥 Installation](#installation)
- [👨‍💻 Usage](#usage)
- [📊 Model Details](#model-details)
- [🏆 Results](#results)
- [🤝 Contributors](#contributors)
- [📜 License](#license)

---

## 📖 Project Overview

This project aims to simplify the course selection process for students by analyzing their academic background and preferences. Our intelligent system leverages machine learning to deliver personalized course recommendations, empowering users to make informed decisions about their education.

### How it Works:
1. Users input their **graduation**, **areas of interest**, and **entrance test scores**.
2. The system processes this data through a trained machine learning model.
3. Based on user inputs, the model predicts the most suitable course from a predefined list.
4. The recommended course is displayed on an easy-to-navigate web interface.

---

## 🎯 Goal of the Project

The primary goal of this project is to create an intelligent recommendation system that assists students in choosing the right courses tailored to their academic profiles, interests, and capabilities. By utilizing advanced machine learning techniques, this system aims to reduce the complexity of course selection, providing personalized and accurate suggestions for each user.

---

## ✨ Features

- **User Input Form**: Intuitive input fields for graduation, interests, prerequisites, and test scores.
- **Machine Learning Prediction**: Accurate predictions of the best-fit courses using the XGBoost algorithm.
- **High Accuracy**: Exceptional model performance with an accuracy of **93.70%** on test data.
- **Flask Web Application**: A user-friendly web interface that makes interaction seamless and engaging.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: Flask (Python)
- **Machine Learning**: XGBoost, joblib (for model serialization)
- **Data Processing**: Pandas, Scikit-learn
- **Model Training**: Python, XGBoost
- **Deployment**: Flask web server

---

## 📥 Installation

Follow these simple steps to get your project up and running:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Jays0718/course-recommendation-system.git
   cd course-recommendation-system
   ```

2. **Set up the environment:**
   - Create a virtual environment (recommended):
     ```bash
     python -m venv env
     source env/bin/activate  # On Windows: env\Scripts\activate
     ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask app:**
   ```bash
   flask run
   ```
   The web app will be available at `http://127.0.0.1:5000`.

---

## 👨‍💻 Usage

1. Launch the web application.
2. Fill out the form with your **graduation**, **interests**, **prerequisites**, and **entrance test scores**.
3. Submit the form.
4. View the recommended course displayed on the result page.

---

## 📊 Model Details

- **Algorithm**: XGBoost (Extreme Gradient Boosting)
- **Accuracy**: 93.70% on test data
- **Training**:
  - The model is trained using a labeled dataset consisting of various course options and relevant features.
  - The model is serialized using **joblib** for easy integration into the Flask application.

---

## 🏆 Results

The model effectively predicts suitable courses with high accuracy and has been tested with diverse student datasets, showcasing its reliability and performance.

---

## 🤝 Contributors

- [Jaydeep Shinde](https://github.com/Jays0718) - Developer

---

## 📜 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---
