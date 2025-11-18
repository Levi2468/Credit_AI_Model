# Interpretable Machine Learning for Credit Risk Assessment using SHAP Values
Financial institutions must evaluate credit applications accurately while ensuring that lending decisions remain transparent and explainable to customers and regulators. The objective of this project is to develop an interpretable machine learning model for credit default prediction using the OpenML Credit Risk dataset (ID: 43454). The dataset contains applicant-level financial and demographic attributes, along with a target label indicating whether the applicant is considered default or not-default credit risk.

The project uses XGBoost, a gradient-boosted tree algorithm, to model default risk. To overcome the inherent opacity of tree-ensemble methods, we integrate SHAP (Shapley Additive Explanations) to provide:
Global explanations: identifying which features consistently influence default risk across the population.
Local explanations: showing why an individual applicant is classified as high, low, or borderline risk.
This combination supports risk transparency, bias assessment, and regulatory model governance, enabling responsible deployment of credit scoring models in real-world lending environments.
