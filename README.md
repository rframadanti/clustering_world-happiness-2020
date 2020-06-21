# clustering_world-happiness-2020
K-Means Clustering of World Happiness Report (WHR) 2020

K-Means Clustering is an unsupervised machine learning algorithm. Here, we're aiming to apply clustering analysis of world happiness report 2020 using 6 variables as the input to eventually compare the clusters generated with the happiness score assigned from the report.

Analysis includes:
- Pre-processing to filter columns as variables
- Applying silhouette analysis to K-Means Clustering model to help finding optimal k
- Applying elbow method to help finding optimal k
- Building the final K-Means Clustering with the chosen k

The result is available to explore at my Tableau public:
https://public.tableau.com/profile/ristanti.ramadanti#!/vizhome/WorldHappinessReport_15919886768830/World_Happiness
6 clusters were derived and this Tableau dashboard shows interactive #datavisualization of the cluster profile.
You can play around by changing the x and y axis to see visualization of different pairings of the variables! 

The Python code is available as WHR20-class.ipynb where the steps are built as functions in a Clustering class which are reproducible for other data, while the code in WHR20.ipynb shows step-by-step code specifically for WHR 2020 data.

Data is from World Happiness Report
Original Source: World Happiness Report 2020 https://happiness-report.s3.amazonaws.com/2020/WHR20.pdf
Statistical appendix: https://happiness-report.s3.amazonaws.com/2020/WHR20_Ch2_Statistical_Appendix.pdf
Original Authors: Editors: John Helliwell, Richard Layard, Jeffrey D. Sachs, and Jan Emmanuel De Neve, Co-Editors; Lara Aknin, Haifang Huang and Shun Wang, Associate Editors; and Sharon Paculor, Production Editor
Citation: Helliwell, John F., Richard Layard, Jeffrey Sachs, and Jan-Emmanuel De Neve, eds. 2020. World Happiness Report 2020. New York: Sustainable Development Solutions Network
Data compiled by Michael Londeen, available at: https://www.kaggle.com/londeen/world-happiness-report-2020

Reference for code:
https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html
https://medium.com/pursuitnotes/k-means-clustering-model-in-6-steps-with-python-35b532cfa8ad
