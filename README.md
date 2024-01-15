# WORLD-DEVELOPMENT-MEASUREMENT

Objective:
To analyse and create clusters on the dataset  which contains data on significant economic  and development measures pretaining to  various nations worldwide.

> Check for Null Values and Dulpicates-  We found that there are 18.7% non-null values and 81.3% null values.
> Data Type Validation - Before handling null values, we need  to make sure that data types are  validated.
Convert non numeric columns  ‘Business Tax Rate’, ‘Country’, ‘GDP’,  ‘Health Exp/Capita’, ‘Tourism  Inbound’ and ‘Tourism Outbound’ into  numeric.
> Handling the Null Values - Check for the skewness and use  KNN Imputer if not highly skewed and  doesnot have outlier.
Fill with the median if there is any  outlier.
> Handling the Outliers -  We tried to cap the outliers using the  quantile infomation of the data.
> Modeling - We used ML Packages like Scikit-learn and Catboost to build Machine  Learning Classification Models.
> Clustering algorithms used are: Hierarchical Cluster,K-Means Cluster,DBSCAN Cluster,HDBSCAN Cluster.
> Classification algorithms used are: Random forest,Linear SVC ,KNN,Adaboost,Catboost  SGD
> For the Deployment we used Streamlit which gives us simple, easy-to-write  script to construct a minimal web page.









