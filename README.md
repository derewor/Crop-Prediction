# Crop-Prediction
Machine learning modelling for crop prediction

## Objective
To generate a model that predicts an appropriate crop type based on macro nutrient content of sois and its pH.

## Applicability
* This model can be used to determine which crop type would be more productive on soils with defined content of N, K, P as well as pH level.
* The prediction can be improved by adding more parameters such as soil moisture, micronutrients and temperature etc to the model. 

## Tools
googlecolab, pandas, sklearn 

## Results
* By training each feature separetly, K has the highest predicting power of 0.32 as shown from the F1 score. However, this score alone is small to predict the appropriate crop type for the soil.
* By combining all four features (N, P, K, ph), the model achieves an F1 score of 0.81. This indicates a strong ability to accurately classify the outcome, with a good balance between detecting true classes and avoiding false ones. Unlike using individual features alone, which performed poorly (F1 < 0.32), this result confirms that the target variable is best explained by the interaction of multiple features.”

## Author
Dereje W. Mekonnen

email: derewor@gmail.com

LinkedIn: https://www.linkedin.com/in/dereje-worku-mekonnen-a8345217/


