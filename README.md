# Bike Sharing Assignment

> Bike Sharing Assignment is a Multiple Linear Regression problem to find out which variables are significant in predicting the demand for shared bikes and how well those variables describe the bike demands for a bike sharing service (Boom Bikes).


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of date wise rider counts along with the corresponding meteorological data for a perid of 2 years (2018-2019)
- The notebook on the assignment includes data understanding, exploratory data analysis, data splitting for tarining and test, feature scaling, feature selection using RFE, model building, model evaluation including validation of assumptions of linear regression


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model's R-squared and Adj. R-squared scores during Traing and Testing Stages respectively are comparable. So there is no underfitting or overfitting.
- Hence it can be concluded as a good machine learning model with generalization.
- Prob (F-statistic) is very small, hence the R^2 value is significant and not by chance
- The predictors in the final model equation can explain approx 78% of the variation in any unseen data
- All VIFs < 5, so level of multicollinearity is acceptable
- All p-values < 0.05, therefore all coefficients are significant

### Top 3 Predictors
- temp_feels_like (temperature feels like) positively affects the bike demand. Bike demand is likely to increase by 0.54 units for unit increase in temperature (temp_feels_like), provided other features remain unchanged
- bad weather (snow or heavy snow) negatively affects the bike demand. Bike demand is likely to decrease by 0.28 units on snowy weather, provided other features remain unchanged
- year positively affects the bike demand. Bike demand is likely to increase by 0.23 units every year, provided other features remain unchanged

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

#### Programming Language & Environment
- Python           - version 3.9.13
- Jupyter Notebook - version 6.4.12

#### Libraries
- numpy            - version 1.23.2  for array manipulation
- pandas           - version 1.4.3   for data manipulation
- matplotlib       - version 3.5.3   for plotting
- seaborn          - version 0.11.2  for plotting
- scikit-learn     - version 1.1.2   for linear regression related work
- statsmodels      - version 0.13.2  for linear regression, VIF computation

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}


## Contact
Created by [@dpahadsing-aiml] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->