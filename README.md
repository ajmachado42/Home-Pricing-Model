# Predicting Home Pricing
## by Adriana Machado

This project is focused on model deployment and dashboarding, not so much model performance. 

Using the popular [Ames, Iowa Housing Dataset](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt), a model is created and then put into production with a dashboard. Much of the data cleaning was adapted from my GA bootcamp peer, [Joe Serigano](https://github.com/jserigano4/predicting_home_prices_Ames_IA/blob/main/01-Data_Cleaning_EDA.ipynb), who used the same dataset for a class project involving a Kaggle competition. 

The previous model had 265 variables. For the sake of this project and the model deployment, we will narrow variables down to the top 10 features (by coefficient), and then create the new model to manipulate and explain using [Explainer Dashboard](https://github.com/oegedijk/explainerdashboard) and Streamlit. 

More to come. Stay tuned...