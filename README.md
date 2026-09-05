# NLP-Based Customer Query Intent Classification

## Project Overview

This project uses Natural Language Processing and machine learning to classify customer queries into different intent categories and automatically suggest a suitable support route.

## Dataset

The project uses the **CLINC150** intent-classification dataset. Ten relevant intents were selected for this project, including:

* Book Flight
* Book Hotel
* Flight Status
* Lost Luggage
* Restaurant Reservation
* Weather
* Car Rental
* Travel Suggestion
* Directions
* Restaurant Suggestion

## Methodology

The project follows these steps:

**Text Preprocessing → TF-IDF → Machine Learning → Intent Prediction → Support Routing**

The text was converted into TF-IDF features using unigrams and bigrams.

## Models

Two models were implemented:

* Logistic Regression
* Multinomial Naive Bayes

## Results

| Model                   |   Accuracy |
| ----------------------- | ---------: |
| Logistic Regression     | **97.33%** |
| Multinomial Naive Bayes | **97.00%** |

**Logistic Regression** performed best and was selected as the final model.

## Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Files

* `NLP_Project.ipynb` – Complete project notebook
* `source_code.py` – Python source code
* `screenshots/` – Project screenshots
* `report/` – Final project report
* `requirements.txt` – Required libraries
