# Electric Vehicle Market Segmentation 
<img src="https://github.com/abhishek-sriram/Feynn-Labs-Internship-2024/blob/main/Task%20-%20EV%20Market%20Segmentation/EV%20market.png" width="400" height="250">

## Introduction 
As a part of the extensive market segmentation analysis, that my team and I carried out, we implemented market segmentaion strategies focusing only on the Electric Vehicle(EV) market in India using unsupervised machine learning algorithms in Python. 

## Market Segmentation Analysis
Market segmentation is one of the key building blocks of strategic marketing. Market segmentation is essential
for marketing success: the most successful firms drive their businesses based on segmentation.[1]

## Problem Statement
The following problem statement was assigned to us by our mentor: 

##### You are a team working under an Electric Vehicle Startup. The Startup is still deciding in which vehicle/customer space it will be develop its EVs.

##### You have to analyse the Electric Vehicle market in India using Segmentation analysis and come up with a  feasible strategy to enter the market, targeting the segments most likely to use Electric vehicles.

##### (CUSTOMER/VEHICLE/B2B) SEGMENTS: Apart from Geographic, Demographic, Psychographic, Behavioral segments,  teams can consider different CATEGORY of Segments for the Segmentation Tasks, based on AVAILABILITY OF DATA. Market Segmentation comes with wide scope of possibility and Segments created can change based on different datasets collected. "

## Procedure
We gathered multiple datasets from various popular sources including Kaggle. These datasets covered diverse information of not only the consumers and customers of Indian EV market across different states in the country but also of the EV products launched today and in the past few years. 

To capture maximum information, each of the team members carried out their research to understand this business problem and presented their own set of questions to investigate into. These questions covered details of different EV market aspects with regards to it's costumers' information and products information. One or more datasets were assigned to each team member to perform EDA and extract information, by applying unsupervised methods such that they could answer the proposed  questions. This step of code implementation was individually performed. Our final results of analysis were compiled together. 

## Datasets
After laying down the business questions, we sought datasets that could closely answer all our questions. The following datasets were collected:

[EV Charging Stations](https://github.com/abhishek-sriram/Feynn-Labs-Internship-2024/blob/main/Task%20-%20EV%20Market%20Segmentation/Datasets/RS_Session_257_AU_2368_B_3.csv)

[EV Cars India](https://github.com/abhishek-sriram/Feynn-Labs-Internship-2024/blob/main/Task%20-%20EV%20Market%20Segmentation/Datasets/EV_Cars_India.csv)


[Car Data](https://github.com/abhishek-sriram/Feynn-Labs-Internship-2024/blob/main/Task%20-%20EV%20Market%20Segmentation/Datasets/car_data.csv)

[Geo Map Data](https://github.com/abhishek-sriram/Feynn-Labs-Internship-2024/blob/main/Task%20-%20EV%20Market%20Segmentation/Datasets/geoMap.csv)

These datasets provided valuable insights into both consumer behavior and the performance of various EV products in the Indian market.

## Algorithms Used
We implemented the following algorithms for our segmentation analysis:

- **Principal Component Analysis (PCA)**: PCA was used to reduce the dimensionality of our dataset, enabling us to capture the most important features while minimizing noise. This step allowed us to focus on the most relevant factors in the EV market.
  
- **K-Means Clustering**: After applying PCA, we used K-Means to partition the dataset into clusters, where each data point belongs to the cluster with the nearest mean. This method helped us identify distinct consumer and product clusters based on their shared characteristics.

These techniques enabled us to explore clusters within the EV market, providing actionable insights into product categories and customer segments.

## Conclusion
Our analysis revealed distinct market segments that could help the EV startup make informed decisions about which customer groups and vehicle types to target. By leveraging PCA for dimensionality reduction and K-Means for clustering, we were able to propose a strategy that aligns with the unique dynamics of the Indian EV market.

## References
1. [Market Segmentation Analysis](https://www.researchgate.net/publication/326524789_Market_Segmentation_Analysis_Understanding_It_Doing_It_and_Making_It_Useful)
