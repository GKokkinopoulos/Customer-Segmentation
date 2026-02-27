# Customer Segmentation - Clustering
This is a practical use case of applying FAMD as the dimension reduction method and K-Means for the clustering of a dataset of customers.
## Installation
The code uses Jupyter Notebook and the libraries which are already installed in Miniconda (simlar to Anaconda). Additionally, I installed the 'prince' library in order to import FAMD from there as the latter is not available in Scikit-Learn.
## Motivation
In this project I used a dataset of 8068 customers which contains demographic (Age, Gender, Profession etc.) and behavioural (Spending Score) data. The final goal is to create interpretable, easily communicated clusters.

The file I used for this project was retrieved by Kaggle (https://www.kaggle.com/datasets/vetrirah/customer). 

## File description
There is one Jupyter Notebook here named Customer Segmentation.ipynb. This file includes the full Python code I used for this project along with explanatory comments.

## Results

You can find a summary of the results here:
* A full exploratory analysis of the dataset was done - Main patterns were revealed, missing values were identified.
* Missing values were imputed (median for the numeric features, standalone "missing" category for the categorical ones).
* FAMD was applied for dimension reduction and the scree plot revealed that 4 Principal Components should be used.
* Elbow Method and Silhouette Analysis showed that 4 clusters should be created
* The clusters were graphically evaluated by the use of 2-D and 3-D scatter plots.
* The features that had the biggest contribution in the Principal Components were identified.
* The clusters were interpretted and described by the use of the features with the biggest contribution.      


## Licensing, Authors, Acknowledgements
The Licensing for this data as well as other relevant information (description, codes, discussion etc.) can be found in the Kaggle link here: (https://www.kaggle.com/datasets/vetrirah/customer). The dataset was initially created for a competition in Customer Segmentation in Analytics Vidhya site (link here: https://www.analyticsvidhya.com/datahack/contest/janatahack-customer-segmentation/#ProblemStatement) and it's license is CC0:Public Domain 
