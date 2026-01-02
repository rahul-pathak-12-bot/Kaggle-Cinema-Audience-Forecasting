
# **Cinema Audience Forecasting – Machine Learning Project**
**Problem Statement**

Predict daily theatre audience counts across multiple locations using historical booking and POS data.
The challenge involves large-scale time-series forecasting with real-world noise, missing values, and zero-demand days.

**Dataset**

8 datasets including POS bookings, online bookings, theatre metadata, calendar information

2M+ rows of anonymized transactional and time-series data

**Approach**

Comprehensive Exploratory Data Analysis (EDA) to identify:

Weekly & seasonal trends

Holiday and weekend effects

Theatre-level demand patterns

Feature Engineering:

Temporal features (day, week, holiday indicators)

Aggregated booking trends

Theatre-specific behavioural features

Model training & evaluation using multiple ML algorithms

Hyperparameter tuning and model comparison to select the best-performing model

**Results**

Kaggle Score: 0.34779

Rank: 642 / 2632

Grade: A

**Tech Stack**

Python, Pandas, NumPy

Scikit-learn, XGBoost / LightGBM / RandomForest

Matplotlib, Seaborn

**Key Takeaways**

Feature engineering plays a critical role in large-scale forecasting problems

Proper EDA directly improves model decisions
