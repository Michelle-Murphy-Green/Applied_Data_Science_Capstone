# Applied Data Science Capstone Project

Overview

This project evaluated factors associated with the successful landing of the SpaceX Falcon 9 first stage. Because SpaceX reduces launch costs by reusing the first stage, predicting landing success may help estimate launch costs and inform competitive bids from other launch providers.

Objectives and Methods

Historical Falcon 9 launch data were collected from the SpaceX API and Wikipedia using Python, Requests, and BeautifulSoup. The data were cleaned, formatted, and organized in pandas DataFrames for analysis.

Exploratory data analysis was performed using SQL, Matplotlib, and Seaborn to identify patterns associated with landing success. Feature engineering and data standardization were completed before dividing the data into training and test sets.

Interactive maps created with Folium were used to examine launch-site locations and geographical patterns in landing outcomes. A Plotly Dash application was also developed to allow users to explore launch success rates by launch site, payload range, and booster version.

Logistic regression, support vector machine, decision tree, and k-nearest neighbors models were optimized using GridSearchCV and evaluated on the test dataset.

Results

The decision tree classifier achieved the highest test accuracy at 94.44%. The support vector machine and k-nearest neighbors models each achieved a test accuracy of 83.33%.

Conclusion

The decision tree classifier was the best-performing model for predicting Falcon 9 first-stage landing success. The analysis also identified relationships among launch characteristics, launch sites, and landing outcomes that may help inform launch-cost estimates.
