# Adults Income Dataset kNN Model and Interactive Visualizations using Plotly Dash 💰📈
[![kNN](https://img.youtube.com/vi/SL2yieiaI7I/maxresdefault.jpg)](https://www.youtube.com/watch?v=SL2yieiaI7I)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![Dist](https://img.youtube.com/vi/LTO0hUeRsS4/hqdefault.jpg)](https://www.youtube.com/watch?v=LTO0hUeRsS4)
## Introduction
This project aims to build a kNN (k-Nearest Neighbors) model for predicting the income levels of adults based on various features. Additionally, interactive visualizations using Plotly Dash have been implemented to explore the dataset and model results.
### Prerequisites
Before running the notebook, ensure that you have the following Python packages installed:
- dash
- jupyter_dash
- pandas
- numpy
- sklearn
- plotly
You can install these packages using pip:

```bash
pip install dash jupyter_dash pandas numpy sklearn plotly
```
## Dataset
The dataset used in this project is the "Adults Income" dataset. It contains various attributes such as age, workclass, education, marital status, occupation, relationship, race, gender, hours-per-week, native country, and income. The goal is to predict whether an adult earns more than $50K annually.

## Notebook Overview
1. **Installing and Importing Packages**: Necessary packages are installed and imported.
2. **Loading and Cleaning Data**: The dataset is loaded and cleaned by removing records with missing values and duplicates.
3. **Encoding Categorical Data**: Categorical variables are encoded using LabelEncoder from sklearn.
4. **Exploratory Data Analysis (EDA)**:
   - Correlation Heatmap: Visualizes the correlation between features using Plotly Express.
   - Feature Selection: Determines the most important features using SelectKBest, PCA, and ExtraTreesClassifier.
5. **Interactive Visualizations**:
   - Distribution Analysis: Implements an interactive histogram for analyzing the distribution of variables.
<br></br>
[<img src="https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/3575d55d-cf29-4df0-a30c-99db4669eece" width="2000"/>](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/3575d55d-cf29-4df0-a30c-99db4669eece)
<br></br>
   - Feature Importance: Visualizes the importance of features using Plotly Dash.
   - Confusion Matrix: Displays a confusion matrix for model evaluation.
<br></br>
[<img src="https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/f0aedd1a-343e-4bc0-bee1-2a3ac62fff59" width="2000"/>](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/f0aedd1a-343e-4bc0-bee1-2a3ac62fff59)
<br></br>
   - kNN Classification Prediction Plot: Implements an interactive plot to visualize kNN classification predictions.
6. **Model Building and Evaluation**:
   - Model Training: Builds a kNN model and evaluates its performance.
   - Model Benchmarking: Benchmarks different models using accuracy, precision, recall, and F1-score.
<br></br>
[<img src="https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/93d23c5b-b23e-459f-b86a-7a659b8c2070" width="2000"/>](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/93d23c5b-b23e-459f-b86a-7a659b8c2070)
<br></br>
   - Cross-Validation: Performs K-fold cross-validation to assess model performance.
7. **Conclusion**: Summarizes the project and findings.

## Conclusion
This project demonstrates the process of building a kNN model for predicting adult income levels and creating interactive visualizations to explore the dataset and model results. By leveraging Plotly Dash, users can interactively analyze the data and understand the model's performance.

## Note
To fully interact with the visualizations, it's recommended to run the notebook in a Jupyter environment or Google Colab. Enjoy exploring the dataset and model predictions!

<details>
<summary><b>Images used in notebook</b></summary>
![Bins_metric](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/c5f7d4f8-ed79-40c0-a235-3b54d91adecd)
![Manhattan_formula](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/68414f26-ae4e-48cf-8c02-fb8f890d75d4)
![Hamming_metric](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/342c7c12-32b4-4ddb-b9ad-408a85b046f2)
![Hanhattan_metric](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/5f6a46dd-3b89-4169-96f1-f1de1e3536d3)
![Canaberra_formula](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/ed8770fc-2d46-49ed-baf5-413cba0f0e3e)
![K_values_plot](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/d73fe850-a035-4f90-bed4-92ee8cff0127)
![Cross_validation_KFold](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/d97b660b-aa49-4498-bc75-fd6ff639dbed)
![Stratified_shuffle_split](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/7eee6439-f336-44e9-bd2c-e6bfc03876a0)
![Adults_Income_Visualisation_Dash_App](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/3575d55d-cf29-4df0-a30c-99db4669eece)
![Confusion_Matrix](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/f0aedd1a-343e-4bc0-bee1-2a3ac62fff59)
![kNN_Visualisation_Dash_App](https://github.com/tobi303x/Adults-Income-KNN-model/assets/114963170/93d23c5b-b23e-459f-b86a-7a659b8c2070)
</details>
