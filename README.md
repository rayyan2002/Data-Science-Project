# Data Science Capstone Project

This repository contains all the artifacts and outcomes of the Data Science Capstone Project. The project demonstrates end-to-end application of data science techniques, including data collection, cleaning, exploratory analysis, visualization, and predictive modeling.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Methodologies](#methodologies)
4. [Key Results](#key-results)
5. [Technologies Used](#technologies-used)
6. [Repository Structure](#repository-structure)
7. [How to Use](#how-to-use)

---

## Project Overview
The objective of this project is to analyze SpaceX's mission data to uncover key insights, build interactive visualizations, and develop predictive models. The insights generated from this project can be used to improve SpaceX's operations and decision-making processes.

## Dataset Description
We used publicly available SpaceX mission data, collected through:
- SpaceX REST API
- Web scraping techniques

The data includes information on launch sites, payload masses, booster versions, success outcomes, and more.

## Methodologies

### 1. Data Collection
- **REST API Calls**: Extracted launch data using SpaceX API.
- **Web Scraping**: Retrieved supplementary data from SpaceX's official website.

### 2. Data Wrangling
- Cleaned and formatted data for consistency.
- Merged API and scraped datasets.

### 3. Exploratory Data Analysis (EDA)
- Conducted descriptive analysis using Python libraries.
- Visualized trends and relationships using Matplotlib and Seaborn.
- Utilized SQL queries for deeper analysis.

### 4. Interactive Visualizations
- **Folium Maps**: Created interactive maps highlighting launch sites and outcomes.
- **Plotly Dashboards**: Developed dynamic dashboards with interactivity.

### 5. Predictive Analysis
- Built classification models to predict mission outcomes.
- Tuned and evaluated models to identify the best performer.

## Key Results
- **EDA Insights**: Identified key factors influencing mission success.
- **Interactive Tools**:
  - Folium maps showing launch locations and outcomes.
  - Dashboards presenting mission trends and KPIs.
- **Model Performance**:
  - Achieved high classification accuracy with tuned models.
  - Visualized confusion matrix for performance evaluation.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, Numpy, Matplotlib, Seaborn, Plotly, Dash, Folium
- **Tools**: Jupyter Notebook, SQL, Git, Tableau

## Repository Structure
```
|-- data/                 # Raw and processed datasets
|-- notebooks/            # Jupyter notebooks for analysis
|-- visuals/              # Screenshots and visual outputs
|-- scripts/              # Python scripts
|-- presentation/         # Final project presentation (PDF & PPTX)
|-- README.md             # Project README file
```

## How to Use

1. **Clone Repository**:
   ```bash
   git clone <repository_url>
   ```

2. **Install Dependencies**:
   Ensure you have Python installed, then install necessary libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Explore Notebooks**:
   Open the Jupyter notebooks in the `notebooks/` directory to review the analysis and results.

4. **Run Dashboards**:
   Navigate to the `scripts/` directory and run the Plotly Dash app:
   ```bash
   python spacex_dash_app.py
   ```

5. **Review Outputs**:
   Check `presentation/` for the final project presentation.

---

## Acknowledgments
- SpaceX for providing the data.
- Coursera and IBM for the capstone project framework.
- Fellow data scientists for valuable peer reviews.

Feel free to contribute by submitting a pull request or opening an issue for suggestions!
