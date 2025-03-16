# Main_project
Brain stroke prediction project
# 🧠 Brain Stroke Prediction

## 📋 Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Methodology](#methodology)
7. [Technologies Used](#technologies-used)
8. [Contributing](#contributing)

---

## Introduction

Brain strokes are a leading cause of death and disability worldwide. Early prediction and intervention can significantly reduce the adverse effects of strokes. This project leverages machine learning techniques to predict the likelihood of a stroke based on various health parameters.

---

## Features

- User-Friendly Interface: Intuitive web application for data input and result visualization.
- Real-Time Predictions: Immediate assessment of stroke risk upon data submission.
- Educational Insights: Provides information on factors influencing stroke risk.

---

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/d1i2v3ya/Main_project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Main_project
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:

   ```bash
   python app.py
   ```

   The application will be accessible at Open Application:[http://127.0.0.1:5000/](http://127.0.0.1:5000/)
.

---

## Usage

1. Access the Web Application:

   Open a web browser and navigate to Open Application:[http://127.0.0.1:5000/](http://127.0.0.1:5000/)
.

2. Input Health Parameters:

   Fill in the required fields such as age, gender, hypertension status, heart disease history, etc.

3. Get Prediction:

   Click the 'Predict' button to receive your stroke risk assessment.

---

## Project Structure

```
Main_project/
│
├── Brain_stroke_KNN/
│   └── Brain_stroke_knn.ipynb  # Jupyter Notebook for data analysis and model training
│
├── Flask/
│   ├── static/
│   │   └── css/
│   │       └── style.css       # CSS styling for the web application
│   │
│   ├── templates/
│   │   └── healthbot.html      # HTML template for the web application
│   │
│   ├── app.py                  # Flask application script
│   └── usemodel.py             # Script to load the trained model and make predictions
│
├── requirements.txt            # List of Python dependencies
└── README.md                   # Project documentation
```

---

## Project Flowchart

Below is a structured representation of the project's workflow:

![image](https://github.com/user-attachments/assets/e2067ad7-8918-4783-906d-d6732edbcc79)




---

## Methodology

1. Data Collection:

   Utilized a publicly available dataset containing health records related to stroke incidents.

2. Data Preprocessing:

   - Handled missing values.
   - Encoded categorical variables.
   - Normalized numerical features.

3. Model Selection:

   Implemented the K-Nearest Neighbors (KNN) algorithm to predict stroke risk.

4. Model Evaluation:

   Assessed model performance using metrics such as accuracy, precision, recall, and F1-score.

5. Web Integration:

   Developed a Flask-based web interface to allow users to input data and receive predictions.

---

## Technologies Used

- Frontend: HTML, CSS
- Backend: Python, Flask
- Machine Learning: scikit-learn, pandas, numpy
- Visualization: Matplotlib, Seaborn

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.

2. Create a new branch(e.g., for a feature like improving UI):

   ```bash
   git checkout -b feature-improve-ui
   ```

3. Commit your changes:

   ```bash
   git commit -m 'Improved UI for better user experience'
   ```

4. Push to the branch:

   ```bash
   git push origin feature-improve-ui
   ```

5. Open a Pull Request.

### The Snapshots of the website featuring the stroke prediction analysis


![Screenshot 2025-03-16 134801](https://github.com/user-attachments/assets/df490c9f-5ff2-418c-812a-65ec21bc9af4)


![Screenshot 2025-03-16 135037](https://github.com/user-attachments/assets/2b5199c0-09be-4015-a746-f7c5b2c710ee)


![Screenshot 2025-03-16 150100](https://github.com/user-attachments/assets/9494aabd-dd69-4e4d-a9db-ffc21a12a331)



![Screenshot 2025-03-16 150021](https://github.com/user-attachments/assets/adc428f8-050d-4b09-9cab-f83de4d74153)


![Screenshot 2025-03-16 140405](https://github.com/user-attachments/assets/8d5f835c-86ff-4c70-8187-842bbe79d51a)
