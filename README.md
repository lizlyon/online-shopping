# online-shopping

## Objectives 
* Project uses analysis to answer 3 big picture questions:
* Which variables have the strongest impact on a successful customer transaction (Revenue column)?
* Are there any definitive clusters between the ExitRate and BounceRate columns? If so, are there any outliers? 
* Are there any methods to reduce the dimensionality of the continuous variables in your data set? If so, which method, how can you tell, and how many variables do you need to retain 80% of the original variance?

## Methods
* Logistic regression using Revenue as the binary dependant variable.
    * 80/20 TTS
    * Zscore
    * Created logit object 
    * Model evaluation metrics
    * Coefficient df 
    * Supporting plots 
* DBSCAN to analyze the clusters that are evident in the dataset. 
    * Created a subset df of the inputs used for clustering 
* PCA for dimensionality reduction to understand how many principle components are needed to retain 80% variance. 
    * Selcted min and eps
    * Scree plot 
    * 80% variance plot 
    * Silhouette score 

## Data source 
* https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset

## Source Files
* onlineshoppers.ipynb
