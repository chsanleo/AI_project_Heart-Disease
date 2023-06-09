# AI_project
## Heart-Disease-Dataset
UCI Cleveland Heart disease dataset

![badge](https://img.shields.io/badge/working-active-brig)

## Introduction

The Heart-Disease-Dataset database consists of 76 attributes, but only a subset of 14 attributes has been utilized in all published experiments thus far. Among these experiments, ML researchers have exclusively employed the Cleveland database. The attribute labeled "goal" indicates the presence of heart disease in a patient and is represented by an integer ranging from 0 (indicating no presence) to 4. Previous studies conducted using the Cleveland database have primarily focused on distinguishing between the presence (values 1, 2, 3, 4) and absence (value 0) of heart disease.

____
## Goal

The goal of this project is to build a model that can predict the presence of heart disease using a serie of parameters.

The main goal of all the project is to learn.
____
## 🚀 How to start:

+ Download the repository in your machine.

+ Use the docker file to work with docker:
```console

> docker compose up

```

+ Follow the link in the terminal for access to jupyter-lab

+ Load the data in the jupyter-lab

+ Execute the code and work

____
## Data
The dataset is available at [kaggle](https://www.kaggle.com/datasets/ineubytes/heart-disease-dataset)

Total registers 1025, 14 parameters.

Parameters:
- age => age in years
- sex => (1 = male; 0 = female)
- cp => chest pain type (4 values)
- trestbps => resting blood pressure (in mm Hg on admission to the hospital)
- chol => serum cholestoral in mg/dl
- fbs => (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- restecg => resting electrocardiographic results
- thalach => maximum heart rate achieved
- exang => exercise induced angina (1 = yes; 0 = no)
- oldpeak => ST depression induced by exercise relative to rest
- slope => the slope of the peak exercise ST segment
- ca => number of major vessels (0-3) colored by flourosopy
- thal => 0 = normal; 1 = fixed defect; 2 = reversable defect
- target => 0 absence heart disease
