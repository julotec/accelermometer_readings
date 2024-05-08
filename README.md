# Activity Classification Using Accelerometer Data

## Description

This project is dedicated to the classification of different activities (e.g., walking, running, standing still, climbing stairs) based on accelerometer data from a mobile phone. It utilizes Support Vector Machine (SVM) and Random Forest algorithms from the scikit-learn library.

## Data

The dataset contains accelerometer readings from a mobile phone in the form of CSV files. Each file contains readings in three axes: X, Y, and Z.

## Data Preparation

1. Download the data from [here](https://drive.google.com/file/d/1nzrtQpfaHL0OgJ_eXzA7VuEj7XotrSWO/view).
2. Place the CSV files into appropriate folders: `running`, `idle`, `walking`, `stairs`.
3. Run the `prepare_data.ipynb` script to calculate time domain features for each activity.

## Models

The project utilizes two classification models:
- SVM (Support Vector Machine)
- Random Forest

## Performance Evaluation

After training the models, their performance was evaluated on the test data. The following results were obtained:

## Requirements

The project was built using the following libraries:
- pandas
- numpy
- scikit-learn

## Running the Code

To run this project, follow these steps:
1. Clone the repository to your computer.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the `main.ipynb` script to train the models and evaluate their performance.
