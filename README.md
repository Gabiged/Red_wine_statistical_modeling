# Red_wine_statistical_modeling
Statistical Modeling Red Wine Quality Provided dataset: https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009 Objectives for this Part:

Practice working with CSV files. Practice performing EDA. Practice applying statistical inference procedures. Practice using linear machine learning models. Practice visualizing data with Matplotlib & Seaborn. Practice creating dashboards with Google Data Studio. Practice reading data, performing queries and filtering data using Pandas.

Used libraries: pandas; matplotlib.pyplot; seaborn; numpy; sklearn.model_selection; sklearn.linear_model; sklearn.preprocessing; sklearn.ensemble; sklearn.metrics; statsmodels.api

Given dataset has these features:

fixed acidity: :most acids involved with wine or fixed or nonvolatile (do not evaporate readily).

volatile acidity: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste.

citric acid: found in small quantities, citric acid can add 'freshness' and flavor to wines.

residual sugar: the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet.

chlorides: the amount of salt in the wine.

free sulfur dioxide: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine.

total sulfur dioxide: amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine.

density: the density of wine is close to that of water depending on the percent alcohol and sugar content.

pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale.

sulphates: a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant.

alcohol: the percent alcohol content of the wine.

quality: output variable (based on sensory data, score between 0 and 10).

Conclusions: The available data table is not large, so a data transformation was necessary to analyse and use the data. From the available data we can conclude that the vast majority of wines are in the medium class (ratings 5-6). The quality of the wine is determined by the alcohol content (highest correlation percentage). The hypothesis that the alcohol content of a red wine should be 12 per cent was rejected because the average content of the whole sample is 10.42, while the alcohol content of the best-quality wine alone is 11.52 per cent. The same was confirmed by the confidence intervals obtained (11.385; 11.651) with 95% confidence. Sulphates and citric acid seem to belong to higher quality wines while higher values of volatile acity are present in lower quality wines.
