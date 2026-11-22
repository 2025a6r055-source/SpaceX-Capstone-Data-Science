# Winning Space Race with Data Science

## Project Overview

This capstone project uses data science to explore and predict the
successful landing of SpaceX Falcon 9 first-stage boosters. Since the
first stage can be reused when it lands successfully, predicting landing
outcomes can help estimate launch costs and support competitive
launch-cost analysis.

## Problem Statement

Predict whether the first stage of a SpaceX Falcon 9 launch will land
successfully.

## Project Objectives

-   Collect publicly available SpaceX launch data.
-   Retrieve and combine information from SpaceX API endpoints.
-   Scrape Falcon 9 launch information from Wikipedia.
-   Clean and prepare the collected data for analysis.
-   Explore launch data using SQL and visualizations.
-   Build interactive visual analytics using Folium and Plotly Dash.
-   Train and evaluate machine-learning classification models to predict
    landing outcomes.

## Methodology

### 1. Data Collection

-   Retrieve launch information from the SpaceX API.
-   Enrich launch records with rocket, launchpad, payload, and core
    information.
-   Scrape tabular launch data from Wikipedia.

### 2. Data Wrangling

-   Inspect missing values and data types.
-   Extract relevant records and flatten nested fields.
-   Prepare a binary outcome label for successful and unsuccessful
    landing outcomes.

### 3. Exploratory Data Analysis

-   Analyze relationships involving flight number, launch site, payload
    mass, orbit, and launch outcome.
-   Use SQL queries to investigate launch records and outcomes.
-   Visualize patterns and yearly success rates.

### 4. Interactive Visual Analytics

-   Use Folium to map launch sites and launch outcomes.
-   Use Plotly Dash to create an interactive dashboard with launch-site
    selection and payload-mass filtering.

### 5. Predictive Analysis

-   Prepare features and target labels.
-   Split the data into training and testing sets.
-   Evaluate classification approaches, including:
    -   Logistic Regression
    -   Support Vector Classifier (SVC)
    -   Decision Tree Classifier
    -   K-Neighbors Classifier
-   Compare model performance to identify a suitable predictive model.

## Key Findings

The project presentation reports the following findings:

-   Falcon 9 first-stage landing success rates improved over time.
-   KSC LC-39A showed the highest success rate among the launch sites
    examined.
-   ES-L1, SSO, HEO, and GEO were among the orbit types with the highest
    observed success rates.
-   Heavier payloads had a higher failure rate in earlier launches, with
    improvement over time.
-   The Decision Tree Classifier was reported as highly accurate in
    predicting landing outcomes.

## Tools and Technologies

-   Python
-   Jupyter Notebook
-   Pandas
-   SQL
-   BeautifulSoup
-   Folium
-   Plotly Dash
-   Scikit-learn
-   Matplotlib / Seaborn (where used in the notebooks)

## Repository Contents

Upload your completed project notebooks and Python files to this
repository. A suggested organization is:

``` text
SpaceX-Capstone-Data-Science/
├── README.md
├── notebooks/
│   ├── data-collection-api.ipynb
│   ├── web-scraping.ipynb
│   ├── data-wrangling.ipynb
│   ├── exploratory-data-analysis.ipynb
│   ├── sql-analysis.ipynb
│   ├── folium-map.ipynb
│   ├── plotly-dash-dashboard.ipynb
│   └── machine-learning-prediction.ipynb
├── scripts/
│   └── [add your completed Python files here]
└── presentation/
    └── [add your final presentation PDF here]
```

The folder and file names above are a suggested structure. Replace them
with the actual names of the files you completed and upload. Do not
leave placeholder files in place of your assignment work.

## How to Use

1.  Open the notebooks in the `notebooks/` folder using Jupyter
    Notebook, JupyterLab, or Google Colab.
2.  Follow the notebook cells in order.
3.  Install any required Python packages if prompted.
4.  Review the final presentation PDF in the `presentation/` folder.

## Project Presentation

Add the completed capstone presentation as a PDF in the `presentation/`
folder before submitting the repository to Coursera.

## Author

**Nuha Fatima**\
B.Tech -- Computer Science and Engineering (AI & ML)

------------------------------------------------------------------------

*This repository contains coursework for the IBM Data Science Capstone
project, "Winning Space Race with Data Science."*
