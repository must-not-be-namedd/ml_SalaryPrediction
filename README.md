# Salary Prediction Project

This project aims to predict software developer salaries based on factors like country, education level, and years of experience.

## Project Structure

* `app.py`: Main Streamlit application file.
* `predict_page.py`: Contains the code for the salary prediction page.
* `explore_page.py`: Contains the code for the data exploration page.
* `saved_steps.pkl`: Pickle file containing the trained model and label encoders.
* `README.md`: This file.

## Data

The project uses a dataset of software developer salaries.

## Model

The salary prediction model is a linear regression model trained on the provided dataset.

## Usage

1.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
2.  **Run the Streamlit App:**
    ```bash
    streamlit run app.py
    ```

## Features

* Predicts software developer salaries based on country, education, and experience.


