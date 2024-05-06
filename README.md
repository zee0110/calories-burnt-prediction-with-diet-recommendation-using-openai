# calories-burnt-prediction-with-diet-recommendation-using-openai

### README

#### Calories Burnt and Diet Recommendation System

This project is designed to help users estimate the number of calories burnt during exercise and provide personalized diet recommendations based on their exercise routine and body metrics. It utilizes a machine learning model to predict calorie expenditure and a natural language processing model to generate concise summaries and diet plans.

#### Prerequisites

Before running the code, make sure you have Python installed on your system. Additionally, install the required libraries by running the following command:

```
pip install numpy pandas matplotlib seaborn scikit-learn xgboost openai tkinter
```

#### Usage

1. Clone the repository or download the code files.
2. Replace `OPENAI_API_KEY` in the code with your OpenAI API key.
3. Ensure the presence of the following data files in the same directory as the code:
   - `calories.csv`: Contains data on calorie expenditure during exercise.
   - `exercise.csv`: Contains exercise-related data such as user details, duration, heart rate, etc.
4. Run the code using a Python interpreter.
5. Enter user details such as gender, age, height, weight, exercise duration, heart rate, body temperature, and diet type.
6. Click on the "Calculate" button to generate predictions and recommendations.
7. View the BMI category, summary of results, and recommended diet plan in the GUI.

#### Features

- Predicts calorie expenditure during exercise based on user inputs.
- Determines BMI and category (Underweight, Normal, Overweight, Obese) based on user's height and weight.
- Provides personalized diet recommendations based on BMI category and diet type.
- Includes data visualization for exploring gender distribution, age distribution, calories burnt distribution, and feature correlation.

