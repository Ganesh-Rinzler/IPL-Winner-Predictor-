# IPL-Winner-Predictor-
This project predicts the win probability of IPL matches using machine learning techniques.By analyzing ball-by-ball data (deliveries.csv) and match-level data (matches.csv), the model estimates the winning chances of the batting team during a chase.

Key Features:-
Exploratory Data Analysis (EDA): Insights into runs, wickets, and match outcomes.
Feature Engineering: Created features such as current_score, runs_left, balls_left, wickets_left, CRR (Current Run Rate), and RRR (Required Run Rate).

Model Development:
Logistic Regression used as the primary model.
Accuracy: ~80%.
Encoded categorical features (batting_team, bowling_team, city) using OneHotEncoder + ColumnTransformer.

Web Application:
Built with Streamlit.
Users input match details (teams, venue, target, score, overs, wickets).
Model outputs real-time win probability.

Tech Stack:
Python
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
Web App: Streamlit
Model Deployment: Pickle (pipe.pkl)

