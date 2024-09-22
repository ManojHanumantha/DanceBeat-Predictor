# DanceBeat Predictor: Spotify Track Analysis

## Overview
DanceBeat Predictor is a machine learning project that analyzes Spotify track data to predict the danceability of songs. This project aims to enhance user experience on music streaming platforms by accurately forecasting a track's dance potential based on various audio features.

## Business Question
How can we use predictive modeling to enhance the user experience and engagement on online music streaming platforms by accurately predicting the danceability of tracks?

## Features
- Data cleaning and preprocessing of Spotify track data
- Exploratory Data Analysis (EDA) of audio features
- Implementation of multiple regression models:
  - Linear Regression
  - Decision Tree Regression
  - Random Forest Regression
  - K-Nearest Neighbors Regression
- Model evaluation and comparison
- Creation of a top 50 playlist based on predicted danceability

## Installation
To run this project, you need Python 3.x and the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly

You can install these dependencies using pip:

```
pip install pandas numpy matplotlib seaborn scikit-learn plotly
```

## Usage
1. Clone the repository
2. Ensure you have the Spotify dataset (spotify-dataset.csv) in the project directory
3. Run the Jupyter notebook or Python script to execute the analysis and model training

## Key Findings
- Random Forest Regression outperformed other models in predicting danceability
- Positive correlations were found between danceability and features like valence and loudness
- A playlist of the top 50 most danceable tracks was generated based on the model predictions

## Future Improvements
- Explore additional audio features or incorporate external data sources
- Implement hyperparameter tuning for model optimization
- Incorporate genre-specific analysis for more tailored predictions

## Contributors
- Manoj Hanumantha (Student ID: 23104580)

## Acknowledgments
- Dr Umair ul Hassan - MS5114 Advanced Programming for Business, University of Galway
- Yiyu Wang - MS5114 Advanced Programming for Business, University of Galway

## License
This project is open source and available under the [MIT License](LICENSE).
