
# Sumon Kanti Dey (sdey26@emory.edu)
## HW 3: Model-based Bias Removal in Machine Learning using Syn- thetic Blood Pressure Data
###  Key insights:
- SBP generally increases with age and levels off; DBP peaks in middle age and then declines.
- Balanced datasets are crucial in healthcare to avoid biases that could lead to unfair predictions.
- Class imbalance affects model performance, leading to over-prediction of the majority class.

### Comparative Model Performance:
- Polynomial model performed well in capturing SBP and DBP trends; sigmoidal-Gaussian model struggled with realistic physiological trends.
- Logistic regression classification showed better reliability with balanced data, achieving moderate performance in distinguishing sexes.

<p align="center">
  <img src="https://github.com/SumonKantiDey/BMI500_Week11/blob/main/images/SBP_DBP_vs_Age.png" width="50%">
  <img src="https://github.com/SumonKantiDey/BMI500_Week11/blob/main/images/ROC.png" width="50%">
</p>

### Relevance to model-based machine learning:
- In healthcare, model performance and fairness are influenced by data distribution and biases.
- Techniques like class-weighted loss functions or resampling are effective for mitigating class imbalance, improving fairness and robustness.

### Suggestions for future modeling improvements.
- Explore advanced models (e.g., neural networks with balanced class weights).
- Include additional demographics to enhance model insights.
- Apply resampling or data augmentation for better minority class representation.
- Incorporate physiological knowledge into model design to improve prediction accuracy.

## Disclaimer

Available ChatGPT was used partially to complete HW#3.A to understand the mathematical models for Systolic Blood Pressure (SBP) and Diastolic Blood Pressure (DBP). Additionally, I researched strategies for implementing these models in Python. The insights provided by ChatGPT were instrumental in guiding the approach to data modeling.

