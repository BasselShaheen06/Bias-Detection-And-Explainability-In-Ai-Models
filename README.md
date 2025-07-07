# Uncovering Bias and Explaining Decisions in a Text-Based Job Screening Model

This project is about exploring bias in machine learning models used for screening job candidates. Even if gender isn’t directly included, bias can show up through other features.

Here, I:

- Trained a logistic regression model to predict hiring decisions
- Checked for gender bias using fairness metrics
- Used SHAP to explain what features drive the model’s decisions
- Tried to reduce bias by reweighting the training data

The dataset has 1501 samples with features like age, experience, skills, and interview scores. Gender is the sensitive attribute I tested for bias.

Key takeaway: excluding sensitive features isn’t enough—models can still learn biased patterns from correlated data. Fairness checks and explainability tools are essential.

All code and details are in this repo.

**Repo:** [My GitHub Project](https://github.com/BasselShaheen06/Bias-Detection-And-Explainability-In-Ai-Models)
