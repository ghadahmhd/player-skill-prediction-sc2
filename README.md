# player-skill-prediction-sc2
Statistical analysis of StarCraft II metrics to predict player skill using linear regression.
##📊 Statistical Prediction of Player Skill in StarCraft II Using Linear Regression

This project analyzes the SkillCraft–StarCraft II Dataset to identify which gameplay and behavioral metrics best predict a player's skill level, measured through Actions Per Minute (APM). Using Multiple Linear Regression, the study examines how player dedication (TotalHours, HoursPerWeek) and reaction speed (ActionLatency) contribute to technical performance in Real-Time Strategy games.
#🚀 Project Overview

Real-Time Strategy (RTS) games like StarCraft II require fast decision-making, rapid mechanical execution, and high multitasking ability. This project applies statistical modeling to uncover which measurable factors have the largest impact on player skill.

The analysis includes:

Data preprocessing and cleaning

Descriptive statistics

Outlier detection

Histogram & scatter-plot visualization

Correlation analysis

Multiple Linear Regression (OLS)

Interpretation of coefficients and model significance


#📁 Dataset

Source: SkillCraft – StarCraft II Player Dataset (Kaggle)
Records: ~3,338 (after cleaning: ~3,310)
Features: 19 continuous gameplay metrics

#📊 Key Findings

ActionLatency (reaction time) is the strongest predictor.

Slower reaction time → significantly lower APM

HoursPerWeek shows a moderate positive influence.

TotalHours has a statistically significant but minimal effect.

Final model performance:
R² ≈ 0.54, meaning the model explains ~54% of APM variation.

#🧠 Conclusion

Competitive RTS performance is most strongly influenced by reaction speed and consistent practice.
The model supports the hypothesis that:

Faster cognitive response → higher APM

More weekly practice → improved skill

Long-term experience alone is not a strong predictor of current skill

These insights highlight the importance of both biological response time and training intensity in achieving high-level StarCraft II performance.

#📚 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Statsmodels (OLS Regression)

👩‍💻 Author

Ghada Al-Sultan
Master of Data Science – King Khalid University




