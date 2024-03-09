# Intuit Workbook Upgrade

This is an interest project on choosing the best model for selecting customers to send e-mail marketing content. We used a new package named [pyrsm](https://github.com/vnijs/pyrsm/tree/main/pyrsm/model), a package developed by Rady School of Management for teaching purpose, to simplify and accelerate model selection.

The purpose of this exercise is to gain experience modeling the response to an upsell campaign. The intuit75.parquet file contains data on 75,000 (small) businesses selected randomly from the 801,821 that 
were sent the wave-1 mailing. Using the available data, we predicted which businesses that did not respond to the wave-1 mailing are most likely to respond to the wave-2 mailing.

After a comparing various models, including Logistic Regression, Neural Network, and XG Boost, we picked a model to determine the name list of wave-2 marketing. Our model evaluation includes:
- Prediction plot to measure the individual effects of each features.
- Inspecting overfitting issue using plots.
