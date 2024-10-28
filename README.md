# Disease Prediction Project

## Overview

This project leverages machine learning techniques to predict various diseases using clinical data. By training and evaluating multiple models, it aims to identify the most effective algorithms for disease prediction and determine the most important features contributing to each condition. The ultimate goal is to provide a robust tool that can assist healthcare professionals in early diagnosis and personalized treatment planning.

## Project Structure

The project is structured as follows:
Use code with caution.
```bash
disease-prediction-project/
├── test_data.csv
├── Train_data.csv
└── disease_prediction.ipynb
```
## Installation

To run this project, you need to have the following libraries installed:

- Python 3.7 or higher
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

You can install these libraries using the following command:
Use code with caution.
pip install pandas scikit-learn matplotlib seaborn

## Usage

To run the project, open the Jupyter notebook `disease_prediction.ipynb` and run all cells. The notebook contains a detailed walkthrough of the project, including data loading, exploratory data analysis, model training and evaluation, feature importance analysis, and final predictions on the test set. 


## Files

- `Train_data.csv`: The dataset used to train the models.
- `test_data.csv`: The dataset used to test the models.
- `disease_prediction.ipynb`: The Jupyter notebook containing the project code.

## Results

The project achieved the following results:

- The best performing model for disease prediction was `Gradient Boosting`, with an accuracy of `98 %`.

## Conclusion

This project successfully demonstrates the application of machine learning in disease prediction, showcasing the potential of models like Random Forest and Gradient Boosting in achieving high accuracy and reliability. Through detailed exploratory data analysis and feature importance identification, it provides insights into critical factors influencing various diseases. The findings highlight the importance of data-driven approaches in healthcare, paving the way for enhanced diagnostic tools and personalized treatment strategies. Moving forward, further refinement of these models and the incorporation of larger, more diverse datasets will be essential to improving their generalizability and impact on real-world clinical practice.
