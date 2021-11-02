## Customer-Segmentation-using-different-Clustering
Using various clustering methods, find customer's expenses based on their annual income. The dataset is downloaded from Kaggle.com.  The dataset has 200 entries and 5 features.

### INDEX

* Import Libraries
* Data Overview
* Data Analysing
* KMEANS Clustering
* Hierarchical Agglomerative Clustering
* DBSCAN
* MiniBatch KMeans
* Mean Shift
* Conclusion

### CONCLUSION:
​
Clustering is an unsupervised problem of finding natural groups in the feature space of input data. There are many different clustering algorithms, and no single best method for all datasets. 
​
In this case, reasonable grouping was found using **KMeans**. However, **MiniBatchKMeans** gave equivalent result to that of standard KMeans.
​
**Hierarchical Agglomerative Clustering** gave somewhat similar result to KMeans.
​
**DBSCAN** does not give proper grouping in this case and some tuning is required.
​
Using **Mean Shift**, could not achieve a reasonable result on this dataset.
