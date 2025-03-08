# Algerian Forest Fires Analysis and Prediction

This project aims to analyze and predict forest fires in Algeria using various machine learning techniques. Forest fires are a significant environmental concern, and accurate prediction can help in timely intervention and resource allocation. The project includes **data cleaning**, **exploratory data analysis (EDA)**, **feature engineering**, **model training**, and **deployment using Flask**.


## Project Structure
1. `dataset/`: Contains the dataset used in this project.
2. `models/`: Contains the trained models.
3. `notebooks/`: Contains the Jupyter notebooks used in this project.
4. `templates/`: Contains the HTML templates for the Flask application.
5. `application.py`: Contains the Flask application for the model deployment.
6. `requirements.txt`: Contains the required Python packages for this project.

## Notebooks

- `notebooks/EDA_And_FE_Algerian_Forest_Fires.ipynb`: This notebook contains the exploratory data analysis and feature engineering steps.
- `notebooks/Model_Training.ipynb`: This notebook contains the model training and evaluation steps.

## Dataset

The dataset used in this project is located in the `dataset/` directory:
- `Algerian_forest_fires_cleaned_dataset.csv`
- `Algerian_forest_fires_dataset_UPDATE.csv`

You can find the original dataset on Kaggle at the following link:[Algerian Forest Fires Dataset](https://www.kaggle.com/datasets/mbharti321/algerian-forest-fires-dataset-updatecsv)

## Models

The trained models are saved in the `models/` directory:
- `ridge.pkl`: Trained Ridge regression model.
- `scaler.pkl`: Scaler used for data normalization.

## Deployment Using Flask

The trained model is deployed as a web application using Flask. Users can interact with the model through a web interface, input relevant data, and receive predictions about forest fire likelihood. To run the Flask app, use the following command:

```sh
python application.py
```

## Requirements

The required Python packages are listed in the `requirements.txt` file. You can install them using the following command:

```sh
pip install -r requirements.txt
```