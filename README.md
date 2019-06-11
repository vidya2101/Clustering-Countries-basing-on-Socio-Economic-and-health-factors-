# Clustering-Countries-basing-on-Socio-Economic-and-health-factors-
A detailed exercise for beginners in ML. This will comprehend implementation of clustering along with PCA and Outlier treatment extensively. The entire step by step procedure to solve this problem was in python notebook with detailed documentation. One can also refer to pdf presentation attached here for quick results and procedures. 

We will write a detailed problem statement in here

## Preface

HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. It runs a lot of operational projects from time to time along with advocacy drives to raise awareness as well as for funding purposes.
 
After the recent funding programmes, they have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. The significant issues that come while making this decision are mostly related to choosing the countries that are in the direst need of aid. 
 
And this is where you come in as a data analyst. Your job is to categorise the countries using some socio-economic and health factors that determine the overall development of the country. Then you need to suggest the countries which the CEO needs to focus on the most.  The datasets containing those socio-economic factors and the corresponding data dictionary are provided below.

## Objectives
Your main task is to cluster the countries by the factors mentioned above and then present your solution and recommendations to the CEO using a PPT.  The following approach is suggested here:
 
Perform PCA on the dataset and obtain the new dataset with the Principal Components. Choose the appropriate number of components k. You need to perform your clustering activity on this new dataset, i.e. the PCA modified dataset with the k components.
Try both K-means and Hierarchical clustering on this dataset and create clusters.
Analyse the clusters and identify the ones which are in dire need of aid. You can analyse the clusters by comparing how the original variables ( gdpp, child_mort, etc.) vary for each cluster of countries to recognise and differentiate the clusters of developed countries from the clusters of under-developed countries. Note that you perform clustering on the PCA modified dataset and the clusters that are formed are being analysed now using the original variables to identify the countries which you finally want to select.
Also, you need to perform visualisations on the clusters that have been formed.  You can do this by choosing the first two Principal Components (on the X-Y axes) and plotting a scatter plot of all the countries and differentiating the clusters. You should also do the same visualisation using any two of the original variables (like gdpp, child_mort, etc.) on the X-Y axes as well. You can also choose other types of plots as well.
The final list of countries depends on the number of components that you choose and the number of clusters that you finally form. Also, both K-means and Hierarchical may give different results. Hence, there might be some subjectivity in the final number of countries that you think should be reported back to the CEO. Here, make sure that you report back at least 5 countries which are in direst need of aid from the analysis work that you perform.
 
## Results  Expected
A well-commented Jupyter notebook containing the Clustering Models(both K-means and Hierarchical Clustering) and the final list of countries. The clusters must be visualised on both the Principal Components and some of the original variables.  
Present the overall approach of the analysis in a presentation 
Mention the problem statement and the analysis approach.
Explain the results of Principal Component Analysis and Clustering briefly.
Include visualisations and summarise the most important results in the presentation.
Make sure that you mention the final list of countries here ( Don't just mention the cluster id or cluster name here. Mention the names of all the countries.)

