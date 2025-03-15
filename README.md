# Predict if Spacex Falcon 9 first stage rocket will-land-successfully
we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

# SpaceX Falcon 9 First Stage Landing Prediction

## Overview
This project aims to predict the success of the SpaceX Falcon 9 first stage landing. SpaceX significantly reduces costs by reusing the Falcon 9 first stage, which makes successful landings crucial. Predicting these outcomes can provide valuable insights, especially for companies seeking to compete with SpaceX in rocket launches.

This supervised classification project was completed as part of the IBM Data Science Professional Certificate and involves comprehensive data collection, exploration, visualization, and machine learning techniques.

## Project Structure

### 1. Data Collection
- Utilized the **SpaceX API** to gather launch data.
- Cleaned and formatted the data to ensure consistency and accuracy.
- **Jupyter Notebook:** `SpaceX Data Collection.ipynb`

### 2. Data Wrangling
- Conducted **Exploratory Data Analysis (EDA)** to identify patterns and trends.
- Determined the appropriate labels for supervised machine learning models.
- **Jupyter Notebook:** `SpaceX Data Wrangling.ipynb`

### 3. Web Scraping
- Extracted historical Falcon 9 and Falcon Heavy launch data from Wikipedia using **BeautifulSoup**.
- **Jupyter Notebook:** `Falcon9 webscraping.ipynb`

### 4. EDA and SQL Analysis
- Loaded the dataset into a **Db2 database**.
- Executed SQL queries to answer key assignment questions.
- **Jupyter Notebook:** `EDA - Understanding Dataset.ipynb`

### 5. Data Visualization
- Used **Pandas**, **Matplotlib**, and **Seaborn** for visual exploration and feature engineering.
- Focused on payload mass, launch site success rates, and other key factors.
- **Jupyter Notebook:** `EDA - Data Visualization.ipynb`

### 6. Dashboard Visualization
- Developed an interactive **Plotly Dash** dashboard for:
  - Launch site success rates.
  - Payload success visualizations.
  - Interactive components like dropdowns and range sliders.
- **Jupyter Notebook:** `Dashboard.ipynb`

### 7. Launch Site Analysis with Folium
- Used **Folium** for interactive mapping and geospatial analysis to understand the influence of launch site locations.
- **Jupyter Notebook:** `Launch Sites - Interactive Notebook with Folium.ipynb`

### 8. Machine Learning Model Implementation
- Implemented classification algorithms:
  - **K-Nearest Neighbors (KNN)**
  - **Decision Tree**
  - **Support Vector Machine (SVM)**
  - **Logistic Regression**
- Applied **hyperparameter tuning** for improved performance.
- **Jupyter Notebook:** `Machine Learning - Jupyter Notebook.ipynb`

## Results
The project highlights key insights into the factors influencing successful Falcon 9 first-stage landings. The findings can aid stakeholders in understanding launch dynamics, improving predictions, and making data-driven decisions in the space industry.

## How to Run
1. Clone this repository.
2. Install the required dependencies from `requirements.txt`.
3. Run individual notebooks for data collection, analysis, and model prediction.
4. For the interactive dashboard and Folium visualizations, download the notebook and run it locally or via Google Colab.

## Acknowledgments
- Special thanks to IBM for providing the learning resources and guidance throughout the project.
- Data sourced from **SpaceX API** and **Wikipedia**.

