# WiDS24_Challenges

### Overview of Challenge
(taken from Kaggle page)

_Gilead Sciences is the sponsor for this year’s WiDS Datathon. They provided a rich, real-world dataset which contains information about demographics, diagnosis and treatment options, and insurance provided about patients who were diagnosed with breast cancer from 2015-2018. The dataset originated from Health Verity, one of the largest healthcare data ecosystems in the US. It was enriched with third party geo-demographic data to provide views into the socio economic aspects that may contribute to health equity. For this challenge, the dataset was then further enriched with zip code level toxicology data NASA/Columbia University._

### Challenge 1: Predicting if the patients received metastatic cancer diagnosis within 90 days of screening
- Model performance evaluated using ROC-AUC score
- For my first notebook, I did not touch on NLP analysis. I used XGBoost model with tuned hyperparameters using Optuna algorithm and the ROC-AUC score on test data (score provided by the system) is 0.801. 
- 
