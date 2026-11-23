============================================================
EMPLOYEE ATTRITION ANALYSIS AND INSIGHT GENERATION DASHBOARD
============================================================

This project is a data analytics dashboard built to analyze the IBM HR Employee Attrition dataset. It includes Exploratory Data Analysis (EDA), Statistical Testing (T-Tests & Chi-Square), Machine Learning (Logistic Regression), and an Automated Insight Generation Engine.

It uses a Streamlit dashboard to allow users to interact with the findings and automatically generate a professional PDF report.

-----------------------------------------
HOW TO RUN THE PROJECT ON YOUR COMPUTER
-----------------------------------------

PREREQUISITES:
- Python 3.9 or higher installed on your system.

STEP 1: OPEN A TERMINAL
Open Command Prompt or PowerShell, and navigate to the folder where you extracted this project:
> cd path\to\Empolyee_Attrition_Project_FDA

STEP 2: CREATE A VIRTUAL ENVIRONMENT
It is highly recommended to create a virtual environment to isolate the project's dependencies:
> python -m venv venv

STEP 3: ACTIVATE THE VIRTUAL ENVIRONMENT
Activate the environment so that packages are installed locally:
- On Windows:
  > .\venv\Scripts\activate
- On Mac/Linux:
  > source venv/bin/activate

STEP 4: INSTALL DEPENDENCIES
Install all the required Python libraries using the provided requirements.txt file:
> pip install -r requirements.txt

STEP 5: RUN THE DASHBOARD
Once everything is installed, launch the Streamlit dashboard:
> streamlit run app.py

A browser window should automatically open pointing to http://localhost:8501. 

-----------------------------------------
PROJECT STRUCTURE
-----------------------------------------
- app.py                  : Main Streamlit dashboard application
- requirements.txt        : List of required Python packages
- data/                   : Folder containing the CSV dataset
- src/preprocessing.py    : Handles data cleaning and encoding
- src/eda.py              : Generates Matplotlib and Seaborn visualizations
- src/statistics.py       : Calculates T-Tests and Chi-Square tests
- src/ml_model.py         : Trains a Logistic Regression model
- src/insight_engine.py   : Generates human-readable business insights
- src/report_generator.py : Compiles the findings into a PDF report using ReportLab

Enjoy!
