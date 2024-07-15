1) Description :- 
The Mobile Phone Pricing Model aims to develop a predictive model that estimates phone prices based on various features. Our project involves identifying the key features that significantly influence mobile phone prices through feature extraction and analysis.

2) Key Features:-
 Our model uses the following key features to predict phone prices:
- Screen size
- RAM
- Storage
- Model color
- Processor speed
- Operating system
- Release date

3) Objectives :-
- Our objectives are to: Develop a predictive model that accurately estimates phone prices. 
- Identify the most influential features that affect phone prices. 
- Provide strategic recommendations to the organization for refining pricing strategies and marketing decisions.

4) Methodology :-
   
 Our methodology involves the following key steps:
- Data Exploration
- Loaded and examined the dataset to understand its structure, data types, and value ranges
- Data Preprocessing under measure the  Addressed missing values, outliers, and inconsistencies
- Converted categorical variables into numerical formats using one-hot encoding
- Feature Extraction: Identified the most relevant features using: Statistical methods (correlation analysis),Visualizations,Feature importance techniques (feature selection, dimensionality reduction)
  
5) Model Building :-
  
- Split the dataset into training and testing sets
- Developed predictive models using machine learning algorithms: Linear regression, Decision trees, Random forests, Gradient boosting
- Evaluated model performance using metrics: Mean absolute error (MAE), Root mean squared error (RMSE)
- Feature Importance Analysis: Confirmed the significance of identified features through model feature importance scores

6) Report and Visualization: Created a comprehensive report or presentation summarizing findings + Including visualizations and insights related to feature importance and their impact on price prediction

7) Recommendations  Provided strategic recommendations to the organization based on the identified influential features, aiding in refining pricing strategies and marketing decisions

8) Data Visualization
    Highly correlated Heatmap Visualization
 ![image](https://github.com/user-attachments/assets/872d0138-1b4b-4cbb-b32b-4e7116fa30a6)

9) Multivariate Analysis :
![image](https://github.com/user-attachments/assets/4df2db07-9c7c-48f3-97d9-63df9aeb3e45)

  In summary, the chart suggests that memory and RAM are the most important features affecting the sale price of mobile phones. Other features like battery capacity, AI lens, and mobile height have much less influence on the price. This information can be useful for feature selection in the model building process, focusing more on memory and RAM for price prediction.

10) show relation between RAM vs. mobile SalePrice

![image](https://github.com/user-attachments/assets/c5698936-11ab-400c-824f-183800eb6b25)

Distribution:
There is a noticeable clustering of phones with 2GB, 3GB, 4GB, 6GB, and 8GB of RAM.
Phones with lower RAM (2GB to 4GB) tend to have sale prices concentrated between 5,000 and 15,000.
Phones with higher RAM (6GB and 8GB) have sale prices that spread across a wider range, from around 10,000 to 30,000

11) Number of mobile phone Memory vs. mobile phones SalePrice

![image](https://github.com/user-attachments/assets/faf3e61e-6ca2-4f2b-adc7-3a19f2821aef)

Distribution:
There is a clustering of phones with memory sizes at 32GB, 64GB, 128GB, 256GB, etc.
Phones with lower memory (32GB and 64GB) tend to have sale prices concentrated between 5,000 and 20,000.
Phones with higher memory (128GB and above) have sale prices that spread across a wider range, from around 10,000 to 30,000.

