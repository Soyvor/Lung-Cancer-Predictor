# Lung Cancer Prediction

This repository contains Jupyter Notebooks for a project focused on predicting lung cancer. It includes two main parts:

1. **Data Analysis and Preprocessing**: In this part, we analyze the dataset and prepare it for machine learning. It covers data visualization, handling missing values, encoding categorical variables, and data splitting. The details are available in the "Data_Analysis_Preprocessing.ipynb" notebook.

2. **Model Building and Evaluation**: In this part, we build a machine learning model for lung cancer prediction. The main focus is on using Support Vector Machines (SVM) to create a predictive model. The model is trained, evaluated, and tested for its performance. The details are available in the "Model_Building_Evaluation.ipynb" notebook.

## Data

The dataset used in this project is named "survey_lung_cancer.csv," which contains information related to lung cancer, including patient attributes and health-related features. The dataset is analyzed to understand its characteristics and features.

## Data Analysis and Preprocessing

In the "Data_Analysis_Preprocessing.ipynb" notebook, we perform the following steps:

- Data exploration and description.
- Handling missing values (no missing values found in this dataset).
- Data visualization to understand feature distributions and relationships.
- Encoding of categorical columns.
- Data splitting for training and testing.

## Model Building and Evaluation

In the "Model_Building_Evaluation.ipynb" notebook, we build and evaluate a machine learning model:

- Exploration of different models (including K-Nearest Neighbors) and selection of the Support Vector Machine (SVM) model.
- Model training and optimization.
- Evaluation metrics, including precision, recall, accuracy, and AUC.
- ROC curve for model performance visualization.
- Conclusion and user input for predictions.

## Usage

To use this repository and run the Jupyter Notebooks:

1. Clone the repository to your local machine.

```bash
git clone https://github.com/your-username/lung-cancer-prediction.git
```

Install the required Python libraries if you haven't already. You can use requirements.txt for this.

```bash
pip install -r requirements.txt
```
Launch Jupyter Notebook and open the relevant notebook for your task.

```bash
jupyter notebook Data_Analysis_Preprocessing.ipynb
```

Follow the instructions within the notebooks for data analysis, preprocessing, and model building.
Conclusion
The primary goal of this project is to predict lung cancer and assess the model's performance. The Support Vector Machine (SVM) model was selected for this task, achieving high accuracy and recall rates.

Author
Yajushreshtha Shukla 
Sanika Upasani
Swayam Pendgaonkar


License
This project is open source and available under the MIT License.
