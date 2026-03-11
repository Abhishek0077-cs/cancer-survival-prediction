# cancer-survival-prediction
"A machine learning pipeline for cancer survival classification achieving 77% accuracy using Random Forest and Grid Search optimization. Includes 3D decision boundary visualizations"


# 📊 The Data
The dataset includes diverse features such as:

Clinical: Cancer Stage (I-IV), Tumor Size, Metastasis status.

Demographic: Age, Gender, BMI.

Environmental: Smoking Status, Air Pollution Exposure, Occupational Hazards.

# 🛠️ Implementation Highlights
1. Advanced Feature Engineering
Ordinal Encoding: Mapped Cancer Stages to numerical values to preserve the biological progression (Stage I < Stage IV).

Interaction Terms: Analyzed the relationship between Age and Tumor_Size_cm to capture non-linear risks.

Categorical Handling: Implemented pd.get_dummies with drop_first=True to avoid the dummy variable trap.

2. Model Optimization
I benchmarked multiple algorithms to find the most robust predictor:

Logistic Regression: Used as a baseline to understand linear relationships.

Random Forest Classifier: Selected for its ability to handle non-linear decision boundaries.

GridSearchCV: Conducted an exhaustive search over n_estimators, max_depth, and min_samples_split to optimize performance.

3. Visualization
To understand how the model "thinks," I generated a 3D Decision Hyperplane using Plotly, visualizing the boundary between survivors and non-survivors across Age, Stage, and Tumor Size.


# Author

Hello , I am Abhishek singh here are my links to contact
1. https://github.com/Abhishek0077-cs
2. https://linkedin.com/Abhishek-singhtech


