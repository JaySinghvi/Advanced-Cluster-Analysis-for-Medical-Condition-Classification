# Clustering Medical Data with K-means and GMM
1. Performed clustering on a medical dataset, utilizing both K-means and Gaussian Mixture Models (GMM) via the Mclust library to determine optimal cluster structures.
2. Utilized the NbClust function to identify the optimal number of clusters for K-means, resulting in three clusters as the most suitable configuration based on majority rule.
3. Conducted extensive analysis of cluster assignments, evaluating the purity of clusters, and their correlation with medical conditions ("Normal", "Prediabetic", "Diabetic"), achieving high purity rates in both clustering methods.
4. Employed Chi-square and Fisher’s exact tests to validate the significant relationship between cluster memberships and the test variable, ensuring robust statistical support for the clustering results.
5. Generated comprehensive visualizations including BIC plots for model comparison, and contour plots for dimension reduction, concluding that model-based clustering (GMM) offered superior purity compared to K-means.
