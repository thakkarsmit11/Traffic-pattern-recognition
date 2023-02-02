# Traffic-pattern-recognition
Mining patterns in large transport-related data benefits many transport
applications, such as long-term strategic planning and short-term traffic
control and management. This project provides a new systematic
framework to cluster time series data considering distribution and
geometric distance. For this, a novel distribution distance measure that
captures the similarity/dissimilarity across time series data which is
symmetric and satisfies the triangle inequality conditions is proposed. A
cluster evaluation indicator called Cluster Heterogeneity Index (CHI) is
defined to cluster the time series. As proof of the concept, the
framework is applied to real data from a Brisbane arterial corridor, and it
shows promising results.

The overall framework to reveal traffic patterns is as shown in figure below:

![2](https://user-images.githubusercontent.com/64182050/216213099-c973733a-fe46-47a8-931b-017ada22eab1.png)

The patterns revealed using the proposed approch can be well identified and understood using the below heatmaps:

<img width="642" alt="1" src="https://user-images.githubusercontent.com/64182050/216212933-6d9ad155-0e32-49de-9a72-8c793ac0ceb0.PNG">

<img width="707" alt="3" src="https://user-images.githubusercontent.com/64182050/216213197-58e0c17a-7096-4a8d-a4ae-ead3894a7297.PNG">


# How to use?

The python scrip "Optimal_Clusters.ipynb" is the main script that uses the travel time data from "TT_all_day_morning.csv" to reveal the traffic patterns and produce output files such as heatmaps, log files, optimal cluster plot, cluster quality plots, distance matrix (a csv) and a few other plots including a dendrogram from the cluster analysis. 

The entire script is automised and only file paths needs to be provided by the user. 

Other scipts such as "KDE_&_Profile_Plots.ipynb", "Structural_Similarity_Plots.ipynb", and "Deno.ipynb" are provided for the user to produce and understand various parts of the main script i.e., "Optimal_Clusters.ipynb"

For more details on the method, refer to the slide deck "Pattern_Recognition.pptm".
