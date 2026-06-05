# Netflix Content Analysis & Content Type Prediction

## Project Overview

Netflix is one of the world's largest streaming platforms, offering thousands of movies and TV shows across different genres, ratings, and countries. This project analyzes Netflix content data to uncover trends in content growth, ratings, content distribution, and geographic contributions. Additionally, machine learning models are developed to classify content as either a Movie or a TV Show based on various content attributes.

---

## Objectives

- Analyze Netflix content distribution and growth trends.
- Study rating patterns across the platform.
- Identify the top content-producing countries.
- Compare Movies and TV Shows available on Netflix.
- Perform exploratory data analysis (EDA).
- Build machine learning models to classify content types.
- Evaluate and compare model performance.

---

## Dataset

The dataset contains Netflix movies and TV shows along with their metadata.

### Features Include

- Title
- Type
- Director
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre (Listed In)
- Description

### Target Variable

- Type (Movie / TV Show)

---

## Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records.
- Converted Date Added into datetime format.
- Handled missing values in Director and Country columns.
- Extracted Year Added and Month Added features.
- Extracted numerical duration values from the Duration column.
- Encoded categorical features using Label Encoding.
- Prepared data for machine learning modeling.

---

## Exploratory Data Analysis (EDA)

### Key Insights

- TV-MA is the most common content rating on Netflix.
- Netflix experienced significant content growth between 2016 and 2019.
- Movies account for approximately 70% of the content library.
- TV Shows represent about 30% of the platform's content.
- The United States contributes the highest number of titles, followed by India and the United Kingdom.

### Visualizations Performed

- Rating Distribution
- Netflix Content Growth Over Years
- Distribution of Movies vs TV Shows
- Top 10 Countries by Content Count
- Content Trend Analysis
- Model Evaluation Results

---

## Machine Learning Approach

### Models Implemented

- Logistic Regression
- Random Forest Classifier

### Key Techniques

- Label Encoding
- Train-Test Split
- Classification Modeling
- Model Comparison
- Prediction on New Content Samples

---

## Model Evaluation

The models were evaluated using:

- Accuracy Score
- Classification Report
- Precision
- Recall
- F1 Score

### Performance Summary

- Logistic Regression Accuracy: 99.66%
- Random Forest Accuracy: 99.77%

Random Forest achieved the highest performance and delivered near-perfect classification results.

---

## Feature Importance

Important factors influencing content type prediction include:

- Release Year
- Duration
- Rating
- Genre
- Country
- Year Added
- Month Added

These features effectively distinguish Movies from TV Shows.

---

## Applications

This project can help:

- Streaming Platforms
- Content Managers
- Media Analysts
- Recommendation System Developers
- Entertainment Industry Researchers

Potential applications include:

- Automated Content Classification
- Content Library Management
- Recommendation Systems
- Trend Analysis
- Content Strategy Planning

---

## Limitations

- Dataset represents Netflix content available during a specific period.
- Viewer engagement and watch-time data are not included.
- Content popularity metrics are unavailable.
- Prediction performance depends on available metadata.
- Results should be interpreted as analytical insights rather than business forecasts.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Jupyter Notebook

---

## Repository Contents

- netflix(s).ipynb → Complete analysis and machine learning workflow
- netflix1.csv → Dataset
- README.md → Project documentation

---

## Author

**Sarika T A**  
Aspiring Data Analyst / Data Scientist

---

## Conclusion

This project successfully analyzed Netflix content data using exploratory data analysis and machine learning techniques. The analysis revealed important insights regarding content ratings, content growth trends, content type distribution, and country-wise contributions. Netflix's content library is dominated by Movies, while TV-MA emerged as the most common content rating. The platform also experienced rapid content expansion between 2016 and 2019.

Machine learning models including Logistic Regression and Random Forest were developed to classify content as either a Movie or a TV Show. Both models achieved exceptionally high accuracy, with Random Forest achieving the best performance at 99.77%. These results demonstrate that content attributes such as duration, release year, rating, genre, and country are highly effective for content classification.

Overall, the project highlights how data analytics and machine learning can support content management, recommendation systems, and strategic decision-making in the streaming industry.

---

## Future Improvements

- Incorporate viewer ratings and watch-time data.
- Include content popularity and engagement metrics.
- Apply advanced machine learning models such as XGBoost and LightGBM.
- Develop recommendation systems based on user preferences.
- Build interactive dashboards using Power BI or Tableau.
- Integrate real-time streaming data.
- Perform sentiment analysis on content descriptions and reviews.
- Expand the analysis using data from multiple streaming platforms.

---
