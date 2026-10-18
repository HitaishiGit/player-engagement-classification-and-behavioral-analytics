## Project Overview

This project analyzes player behavior and uses machine learning to classify players into three engagement levels: **Low, Medium, and High**.

It combines exploratory data analysis, machine learning model comparison, and an interactive Power BI dashboard to understand player engagement patterns and present actionable insights.

## Objectives

- Analyze player behavior and engagement patterns.
- Identify factors associated with player engagement.
- Train and compare machine learning classification models.
- Evaluate model performance using classification metrics.
- Build an interactive Power BI dashboard for data-driven insights.

## Tools and Technologies

- **Python** — Data analysis and machine learning
- **Pandas and NumPy** — Data manipulation and preprocessing
- **Matplotlib, Seaborn and Plotly** — Data visualization
- **Scikit-learn** — Model training and evaluation
- **XGBoost** — Gradient boosting classification
- **Power BI** — Interactive dashboard development

## Project Workflow

1. **Data Preparation:** Loaded and explored the player engagement dataset.
2. **Exploratory Data Analysis:** Examined player behavior, engagement distributions, and relationships between features.
3. **Data Preprocessing:** Prepared the data for machine learning.
4. **Model Training:** Trained Logistic Regression, Random Forest, and XGBoost classifiers.
5. **Model Evaluation:** Compared model performance using accuracy, precision, recall, and F1-score.
6. **Feature Importance:** Examined influential features associated with model predictions.
7. **Dashboard Development:** Created a Power BI dashboard to communicate player engagement insights and model performance.

## Machine Learning Results

The models were evaluated to identify the best-performing classifier.

| Model |              | Purpose |
| Logistic Regression | Baseline classification model |
| Random Forest | Ensemble-based classification |
| XGBoost | Gradient boosting classification |

**Best-performing model:** XGBoost

**Accuracy:** Approximately 91%

The classification report showed strong performance across all three engagement categories, with F1-scores of approximately 0.90 for High, 0.90 for Low, and 0.93 for Medium engagement.

## Key Insights

- `SessionsPerWeek` was one of the most influential features in the trained model.
- `AvgSessionDurationMinutes` was another important feature.
- The model was able to classify players into Low, Medium, and High engagement categories with approximately 91% accuracy.

*Note: Feature importance indicates how the trained model uses features for prediction; it does not establish causation.*

## Power BI Dashboard

The interactive dashboard contains three pages:

### 1. Executive Overview
Presents key performance indicators and a high-level summary of player engagement.

### 2. Player Engagement Insights
Explores engagement patterns using charts and slicers for game genre, location, and engagement level.

### 3. Model Performance
Compares classification models and presents model performance metrics.

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Machine Learning Classification
- Model Evaluation and Comparison
- Feature Importance Analysis
- Data Visualization
- Power BI Dashboard Development
- Communicating Analytical Findings

## Future Improvements

- Validate the model on unseen or new player data.
- Investigate additional behavioral features.
- Monitor model performance as player behavior changes.
- Develop a simple application for interactive predictions.

## Conclusion
This project demonstrates an end-to-end analytics workflow, combining Python-based data analysis and machine learning with Power BI visualization to explore player engagement and communicate findings.

