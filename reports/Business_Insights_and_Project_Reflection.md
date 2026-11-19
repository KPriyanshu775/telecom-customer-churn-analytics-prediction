# Telecom Customer Churn Capstone

## Key Business Findings

- Overall churn rate: 26.54%
- Highest churn contract: Month-to-month (42.71%)
- Highest churn payment method: Electronic check (45.29%)
- Highest churn internet category: Fiber optic (41.89%)
- Highest churn tenure group: 0-12 months (47.44%)

## Business Recommendations

### 1. Focus on Early Customer Retention

The 0-12 months tenure group has the highest observed churn rate of 47.44%. The company should strengthen onboarding, early customer support and follow-up communication for new customers.

### 2. Encourage Longer-Term Contracts

The Month-to-month contract category has the highest observed churn rate of 42.71%. The company can test suitable discounts, loyalty benefits and transparent annual or long-term contract options.

### 3. Review Payment Experience

Customers using Electronic check have the highest observed payment-method category churn rate of 45.29%. The company should investigate billing complaints and provide convenient alternative payment options.

### 4. Improve Internet Service Experience

The Fiber optic internet-service category has the highest observed churn rate of 41.89%. The company should review service quality, connectivity issues and customer support for this category.

### 5. Use Predictive Churn Monitoring

The selected model is Logistic Regression, with a test ROC-AUC of 0.8416. The company can use predicted churn probabilities to prioritize customers for retention campaigns after appropriate business validation.

### 6. Apply Customer-Specific Retention Strategies

Use customer segmentation results to develop different retention strategies for groups with different tenure, charges and churn patterns.

## Project Limitations

1. The analysis uses one publicly available telecom customer dataset. Its findings may not represent every telecom company or market.

2. The dataset contains customer-level records rather than a complete time-series history of customer behaviour.

3. The clustering model uses a limited set of numerical customer features. Other categorical service characteristics could provide additional segmentation information.

4. K-Means clustering depends on the selected features, scaling method and distance-based cluster assumptions.

5. Customer churn classes are imbalanced. Class weighting was used in the classification models, but further threshold analysis may be useful.

6. Model predictions identify statistical associations and risks. They do not establish that a particular service or billing factor directly causes customer churn.

7. The model has been evaluated on a held-out test sample from the same dataset. Performance should be validated on new real-world customer data.

## Reflective Discussion


During this capstone project, I developed an end-to-end telecom customer
churn analytics and prediction workflow. I worked with customer data,
performed data cleaning, investigated missing and blank values, and
conducted exploratory data analysis to understand customer behaviour.

I applied K-Means clustering to identify customer segments and developed
Logistic Regression and Random Forest models to predict customer churn.
The selected model was Logistic Regression, which achieved a test ROC-AUC
of 0.8416.

The project helped me understand the importance of data preprocessing,
feature selection, class imbalance, model evaluation and interpretation.
It also showed how analytical findings can be translated into practical
business recommendations.

One important learning was that a model with good overall accuracy is
not necessarily sufficient for a customer retention problem. Recall,
precision, F1-score and ROC-AUC must also be considered when identifying
customers who may leave.

Further improvements could include testing additional models, tuning
classification thresholds, evaluating more customer features and
validating the model on newer customer records.
