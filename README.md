# Michiel's portfolio
One this page I will provide an overview of my Analytics and Data Science related projects. I currently only have one project worth opening up to the public, but more projects will be added.



# Machine learning projects
**[Loan repayment behaviour prediction](https://github.com/Dutchmick/loan_repayment_prediction)** *(In progress)* <br/>
Case study of a prediction model that can be used to evaluate loan repayment behaviour of currently excluded customers of formal financial services. The [Kaggle Home Credit Dataset](https://www.kaggle.com/c/home-credit-default-risk) was used for this project. Traditional metrics for credit scoring were excluded to create this model (e.g. credit card repayments, previous bank loans).

### I - Exploratory data analysis
Provides an overview of the available data, including visualisations and provides an understanding of the required Data Cleaning steps in preparation of the modelling.
- [EDA notebook](https://github.com/Dutchmick/loan_repayment_prediction/blob/master/notebooks/Homecred%20-%20Exploratory%20analysis.ipynb)

### II - Basic data cleaning & modelling
Data cleaning and modelling which can quickly be deployed and used to develop a benchmark predition model
- [Data cleaning notebook](https://github.com/Dutchmick/loan_repayment_prediction/blob/master/notebooks/Homecred%20-%20Data%20cleaning%20-%20Basic.ipynb)
- [Modelling notebook](https://github.com/Dutchmick/loan_repayment_prediction/blob/master/notebooks/Homecred%20-%20ML%20modelling%20-%20Basic.ipynb)

![](/Images/ROC_graph_basic.png)


### III - Advanced data cleaning & modelling
Showcase of more advanced techniques that can be applied to improve model performance. The notebook is meant to showcase some techniques, but may not necessarily apply to this project.
- [Data cleaning notebook](https://github.com/Dutchmick/loan_repayment_prediction/blob/master/notebooks/Homecred%20-%20Data%20cleaning%20-%20Advanced.ipynb)
- [Modelling notebook](https://github.com/Dutchmick/loan_repayment_prediction/blob/master/notebooks/Homecred%20-%20ML%20modelling%20-%20Advanced.ipynb)

**Examples of more advanced techniques**:
- *IQR outlier removal* - Statistical method which removes outliers falling outside the Inter Quartile Range (IQR)
- *Missing data prediction* - Estimate missing values using machine learning algorithms
- *Polynimonal feature creation* - Increase features by myltiplying features with each other
- *Multi-collineairity* - Identify features which highly correlate and can distort the final model
- *Random forest feature selection * - Use an algorithm to find the best features
- *Algorithm selection* - Compare algorithms to select the best performing one
- *Hyper Parameter Tuning* - Select the optimal combination parameters for best model performance


![](/Images/ROC_graph_advanced.png)

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>


