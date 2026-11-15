
# Crop Yield Prediction in India 🌾

## About the Project
Agriculture is one of the important parts of India's economy. Different crops are grown in different states, and their yield changes from year to year.

In this project, I developed a Crop Yield Prediction system using Python. It uses historical agricultural data to estimate the yield of four crops: Rice, Wheat, Maize and Sugarcane.

The main idea is to allow users to enter a state, crop name and year, and get an estimated crop yield as the output.

## Problem Statement
Crop yield is not the same in every state or every year. Understanding past crop yield data can help us estimate future production levels.

This project aims to analyze historical crop yield data from Indian states and predict the yield of selected crops using regression algorithms.

## Crops Included
- Rice
- Wheat
- Maize
- Sugarcane

## Tools and Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab

## Algorithms Used
I used two regression algorithms in this project:
1. Linear Regression
2. Polynomial Regression

Both algorithms are implemented using NumPy without using the Scikit-learn library.

## Dataset
The dataset contains historical agricultural information from different Indian states and Union Territories.

It includes details such as crop name, state, year, area, production and yield.

The original dataset is cleaned and filtered to select the required crop yield information.

## How the Project Works
1. Load the agricultural dataset.
2. Clean the data and remove unnecessary records.
3. Select the four required crops.
4. Analyze the data using graphs.
5. Train Linear Regression and Polynomial Regression models.
6. Compare the models using evaluation metrics.
7. Select the model with the lower RMSE.
8. Get crop yield predictions based on user input.

## How to Run
First, install the required libraries:

```bash
pip install pandas numpy matplotlib
```

Keep the Python file and dataset in the same folder.

Run the following command:

```bash
python crop_yield_prediction.py
```

Enter the following details when the program asks:

- State name
- Crop name
- Year

The predicted crop yield will be displayed in kg/hectare and tonnes/hectare.

## Model Evaluation
The models are compared using:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

The evaluation results are saved in `model_evaluation.csv`.

## Project Files
- `crop_yield_prediction.py` – Main Python program
- `facts.csv` – Original agricultural dataset
- `cleaned_crop_yield.csv` – Processed dataset
- `model_evaluation.csv` – Model performance results

## Conclusion
Through this project, I learned how to work with a real-world agricultural dataset, perform data cleaning, visualize information and implement regression algorithms.

This project helped me understand how machine learning techniques can be applied to agricultural data to estimate crop yield.

## Future Improvements
- Include weather and rainfall information.
- Add more crops to the prediction system.
- Include soil and fertilizer details.
- Develop a simple website for users to access the prediction system.
