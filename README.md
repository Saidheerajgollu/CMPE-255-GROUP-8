# CMPE-255-GROUP-8
# Traffic Violation Analysis

### Team:
 1. Abhinav Sriharsha Anumanchi - 017514900
 2. Harshavardhan Kuruvella - 017534582
 3. Sai Dheeraj Gollu - 017520503

# Traffic Violation Analysis

This project explores traffic violation data to uncover patterns, identify geographical hotspots, and build machine learning models to predict violation types. By leveraging data preprocessing, geospatial analysis, and predictive modeling, the project offers insights that could inform targeted enforcement strategies and improve road safety.

---

## 1. Introduction
Traffic violations contribute significantly to road accidents and fatalities. This project utilizes machine learning and data analytics to analyze traffic violations, focusing on geospatial and statistical patterns. The primary objective is to provide actionable insights for traffic authorities.

---

## 2. Features
- **Geospatial Clustering:** Identifies high-risk areas using K-Means clustering.
- **Predictive Modeling:** Predicts violation types using Logistic Regression, Decision Trees, and Random Forest Classifiers.
- **Data Visualization:** Generates visual insights using Matplotlib, Seaborn, and GeoPandas.
- **Feature Engineering:** Extracts and creates meaningful features like vehicle conditions and time-based patterns.

---

## 3. Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Data Processing: Pandas, NumPy
  - Machine Learning: Scikit-learn
  - Visualization: Matplotlib, Seaborn
  - Geospatial Analysis: GeoPandas, Shapely
  - Statistical Testing: SciPy

---

## 4. Project Workflow
1. **Data Preprocessing:** Cleaned and transformed dataset (~1 million records).
2. **Exploratory Data Analysis:** Visualized data distributions and patterns.
3. **Geospatial Analysis:** Clustered geographic data to identify violation hotspots.
4. **Model Development:**
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
5. **Evaluation:** Assessed models using metrics like accuracy, precision, recall, and F1 Score.

---

## 5. Results
- The **Random Forest Classifier** emerged as the most effective model with an accuracy of 82% and an F1 Score of 81%.
- Geospatial clustering identified downtown areas and zones near pubs as high-risk regions.

---

## 6. Instructions to Run the Code
To run the code in a Jupyter Notebook:

1. Clone the repository:
   ```bash
   git clone <repository_url>

2. Navigate to the project directory:
   Use the ⁠ cd ⁠ command to move into the directory where the project files are located.
   ```bash
   cd <project_directory>

3. Open Jupyter Notebook
   Launch Jupyter Nitebook environment to acess the project code
   ```bash
   jupyter notebook
4. Run the code
   Open the .ipynb file in the Jupyter Notebook interface and execute the code cells step by step to analyze the data interactively.

---

## 7. Dataset
- **Dataset Source:** [Traffic Violations Dataset on Kaggle](https://www.kaggle.com)
- Contains records of traffic violations, including:
  - Driver demographics
  - Geolocation data
  - Vehicle details

---

## 8. Project Contributors
- **Harshavardhan Kuruvella:** Data preprocessing, Random Forest implementation, feature importance analysis.
- **Sai Dheeraj Gollu:** Logistic Regression implementation, feature engineering.
- **Abhinav Sriharsha Anumanchi:** Gradient Boosting implementation, geospatial visualization.

---

## 9. Acknowledgments
Special thanks to Professor and peers for their guidance and support throughout this project. This project is part of CMPE 255 coursework at San Jose State University.

