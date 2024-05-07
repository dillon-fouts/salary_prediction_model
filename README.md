# Salary Prediction Model

![Python badge](https://img.shields.io/static/v1?message=python&logo=python&labelColor=5c5c5c&color=3776AB&logoColor=white&label=%20&style=for-the-badge)

This application uses an interactive Python notebook to import data, clean the data, build a random forest regression model, test the model, and export the model to a file.

This project is a continuation of the work done by my professor, utilizing the [2022 Kaggle Machine Learning & Data Science Survey](https://www.kaggle.com/c/kaggle-survey-2022/data) as a foundation. Modifications were made to adjust the model and enhance the prediction capabilities. Salaries in our version are generated within specified bounds to provide a realistic yet controlled environment for testing the model's effectiveness.

The concept for this application was inspired by the work done in the [Predicting Year of Marriage - End to End Machine Learning Deployment with FLASK and AWS -PART 1](https://www.youtube.com/watch?v=sm5xeKal72I) video. This has been adapted into a data science salary prediction model utilizing both Microsoft Azure and local deployment for demonstration purposes.

### To Run This Application

---

1. Clone this repository to your local computer.

2. Create a new virtual environment:

   - Windows: `python -m venv ./venv`
   - Mac/Linux: `python3 -m venv ./venv`

3. Activate the new virtual environment:

   - Windows: `.\venv\Scripts\activate`
   - Mac/Linux: `source ./venv/bin/activate`

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt
