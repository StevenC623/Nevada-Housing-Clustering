# Clustering Analysis of Home Loan Applicants in the State of Nevada

This project applied different clustering methods to conduct clustering analysis on home loan applicants based on their quantitative and qualitative features, in order to help mortgage specialist to make their decision on loan applications.

First, we applied the clustering methods [KMeans](https://github.com/StevenC623/Nevada-Housing-Clustering/blob/main/kmean.R) and [KMedoid](https://github.com/StevenC623/Nevada-Housing-Clustering/blob/main/kmedoid.R) on quantitative features only, and then implemented [DBSCAN](https://github.com/StevenC623/Nevada-Housing-Clustering/blob/main/DBSCAN.R) and [Hierarchy](https://github.com/StevenC623/Nevada-Housing-Clustering/blob/main/Hierarchy.R) clustering methods on all featured. 

Next, we compared all different approaches and come to a conclusion.

For the mortgage specialists, they can probably look into qualitative criteria before evaluating the applicant’s ability to repay, such as loan type, principal residence, and other criteria such as gender, race, age. We could apply the hierarchical clustering until all qualitative variables are well-split, then apply partition clustering within each cluster. In this way, we might see different selection criteria for repayment ability for different types of mortgage.

See details in report: [Report](https://github.com/StevenC623/Nevada-Housing-Clustering/blob/main/Report.pdf)

# Original DataSet

original data set can be downloaded [HERE](https://files.consumerfinance.gov/hmda-historic-loan-data/hmda_2017_nv_all-records_labels.zip)

The data set contains home loan information for the state of Nevada in 2017


