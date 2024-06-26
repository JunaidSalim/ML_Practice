We have to select the model for our Dataset, so we are applying all Regression Models on our Dataset and then selecting the best regression model for our dataset on the basis of the r_squared coefficient. The best model will have an r_squared coefficient closest to one.

`Data.csv` is the dataset for model selection. This dataset is cleaned and numeric, so we don't have to pre-process it.

The r_squared coefficients of All Regression Models are given below:

- **Multiple Linear Regression**:  0.6261395942654089
- **Polynomial Regression**:       -6.578577187538827
- **Support Vector Regression**:   0.7450019881733005
- **Decision Tree Regression**:    0.6164510413712425
- **Random Forest Regression**:    0.8101939940507101

Hence, according to the r_squared coefficient: **Random Forest Regression** is the best regression model for this dataset `Data.csv`.