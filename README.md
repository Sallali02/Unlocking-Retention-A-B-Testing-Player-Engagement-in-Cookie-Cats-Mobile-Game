# 🎮 Unlocking-Retention-A-B-Testing-Player-Engagement-in-Cookie-Cats-Mobile-Game 
This project analyzes real-world A/B test data from the mobile game Cookie Cats, where players were randomly assigned to experience a gate at level 30 or level 40. Using R, I applied statistical testing, causal inference, survival analysis, and logistic regression to understand how gate placement affects short- and long-term player retention.

# 🎯 Goal 
This project analyzes real-world A/B testing data from the mobile game Cookie Cats, where developers tested the impact of moving the first in-game gate from level 30 (control group) to level 40 (test group). The goal is to evaluate how this design change affects short-term (1-day) and long-term (7-day) player retention.

# 📊 Data
The dataset includes over 90,000 users and tracks their gameplay activity and retention after installing the game. Each player was randomly assigned to a test or control group. Key features include sum_gamerounds, version, and binary indicators for 1-day and 7-day retention.

# 📈 Methods
The workflow began with preliminary analysis and data cleaning (removing outliers, converting variables). Then, multiple techniques were applied:

- Exploratory visualizations and group statistics

- Classical hypothesis testing (Welch t-test)

- Survival analysis to study engagement patterns

- Causal inference via propensity score matching and inverse probability weighting

- Bayesian A/B testing

- Predictive modeling using logistic regression and ROC/AUC evaluation

# 🏆Results
Players in the gate_30 group showed slightly higher retention at both 1 and 7 days. The differences, while small, were consistent and statistically significant. The predictive model achieved an AUC of 0.89, indicating strong performance in forecasting retention.

# 📝 Conclusion
From a business perspective, placing the gate at level 30 appears to result in better user retention. Since player engagement is a key driver for in-game purchases and long-term monetization, the results suggest keeping the gate earlier may be the more effective strategy.
