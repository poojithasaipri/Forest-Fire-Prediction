#  Forest Fire Prediction using Machine Learning

This project predicts the likelihood of forest fires based on meteorological and environmental conditions using various machine learning models. It includes data preprocessing, exploratory data analysis (EDA), and model training/evaluation.

##  Project Overview

- **Goal**: Predict whether a forest fire will occur given features like temperature, RH (relative humidity), wind speed, and rainfall.
- **Models Used**:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - K-Nearest Neighbors (KNN)  
  - Support Vector Machine (SVM)  

##  Files

- `Forest_Fire_Prediction.ipynb`: The main Jupyter notebook containing code, visualizations, and evaluation.
- `dataset.csv`: Dataset used in the notebook (ensure this file is available in the same directory).

##  Features Used

- **Temperature (°C)**
- **Relative Humidity (%)**
- **Wind Speed (km/h)**
- **Rain (mm)**
- **Classes**: Binary target - Fire (1) or No Fire (0)

##  Steps Followed

1. **Data Loading**
2. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
3. **Exploratory Data Analysis (EDA)**
   - Heatmaps
   - Countplots
4. **Model Building**
   - Train-test split
   - Model training with 5 classifiers
   - Accuracy evaluation
5. **Performance Comparison**

##  Results

| Model               | Accuracy |
|--------------------|---------|
| Logistic Regression| 97%     |
| Decision Tree      | 97%     |
| Random Forest      | 96%     |
| KNN                | 94%     |
| SVM                | 93%     |

>  *Random Forest performed the best among all models.*

##  How to Run

1. Clone the repository or download the `.ipynb` file.
2. Install the required libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
