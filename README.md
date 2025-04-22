This commit includes the complete R Markdown (.Rmd) file for the “Clustering NYC Taxi Trips” project. The analysis applies unsupervised learning techniques, primarily K-Means, to uncover travel demand patterns and customer segmentation using the NYC Taxi & Limousine Commission 2016 dataset. 



Key components include:
Robust data cleaning and outlier filtering based on real-world geographic and fare constraints
Dimensionality reduction using PCA to enhance clustering performance
Clustering tendency assessment using Hopkins statistic and distance matrix visualization
Cluster validation using internal (Silhouette, DBI, CH Index), external (Adjusted Rand Index, VI), and stability metrics (APN, ADM, FOM)
Final model selection favoring K-Means (k=4), which revealed distinct temporal, spatial, and economic trip clusters, including high-demand zones like JFK Airport and Midtown Manhattan



Tools used: R, R Markdown, factoextra, cluster, fpc, dplyr, ggplot2
This file supports reproducibility and serves as the analytical core for understanding urban mobility through clustering.
