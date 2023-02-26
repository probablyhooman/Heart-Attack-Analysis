# Heart Attack Analysis 
This project aims to analyze a dataset containing information about patients who have had heart attacks. The dataset includes various demographic, medical, and lifestyle variables, and our goal is to use the Python libraries NumPy, Pandas, Matplotlib, and Seaborn to explore and visualize the data.

### Getting Started
To run this project, you'll need to have Python 3.6 and the following libraries installed:

- `NumPy`
- `Pandas`
- `Matplotlib`
- `Seaborn`
#### You can install these libraries using pip, a package manager for Python:
```sh 
    import pandas as pd
    import numpy as np
    import matplotlib.pyplot as plt
    import seaborn as sns
```
## Dataset
The dataset we will be using is called the [Heart Attack Analysis & Prediction Dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)," and it can be downloaded from [Kaggle](https://www.kaggle.com/).
### The dataset contains the following variables:

`age` :  Age of the patient

`sex`:  Sex of the patient (1 = male, 0 = female)

`cp`:  Chest pain type (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)

`trtbps`:  Resting blood pressure (in mm Hg)

`chol`:  Cholesterol level (in mg/dl)

`fbs`:  Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)

`restecg`:  Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy)

`thalachh`:  Maximum heart rate achieved (in bpm)

`exng`:  Exercise induced angina (1 = yes, 0 = no)

`oldpeak`: ST depression induced by exercise relative to rest

slp:   of the peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping)

`caa`:   Number of major vessels (0-3) colored by fluoroscopy

`thall`:  Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)


> output: Target variable indicating whether or not the patient had a heart attack (1 = yes, 0 = no)
Analysis
We will use NumPy and Pandas to clean and manipulate the data, and then use Matplotlib and Seaborn to create visualizations to help us better understand the data.

### The analysis will be divided into the following steps:

- Loading the data
- Cleaning the data
- Exploratory Data Analysis (EDA)
- Creating visualizations
- Drawing conclusions

### Conclusion
Through this project, we will explore the Heart Attack Analysis & Prediction Dataset using the Python libraries NumPy, Pandas, Matplotlib, and Seaborn. We will clean and manipulate the data, perform exploratory data analysis, create visualizations, and draw conclusions about the dataset.
