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

12)  Feature Importance using a Machine Learning Model

![image](https://github.com/user-attachments/assets/fc5871c6-77ac-45ec-9e19-88e4ab5ed105)

Memory is the most important feature, with a significantly higher importance score compared to others.

Battery and RAM are the second and third most important features, respectively. Mobile Height also shows a notable contribution.

The features related to camera specifications, including Front Camera_0MP, Front Camera_5MP, Front Camera_12MP, Front Camera_16MP, and Rear Camera_50MP, have varying degrees of importance, but generally lower than Memory, Battery, and RAM.

Processor (Dimensity 1080, Octa Core) has the least importance among the top 10 features.

13) Dimensionality Reduction Using PCA

![image](https://github.com/user-attachments/assets/86336b4f-313d-4187-b93c-235b145d60a7)

The plot shows a line with points indicating that the explained variance increases as more principal components are added.

The relationship appears to be linear, suggesting that each additional principal component contributes a similar amount of variance.

14) Random Forest Datavisualization

![image](https://github.com/user-attachments/assets/a5ecca30-def5-43ea-91a6-142f4fc4dd39)

15) Decision tree data visualization

![image](https://github.com/user-attachments/assets/015010ca-8b74-4d40-99e4-035115fb4314)

16) Linear Regression data visualization

![image](https://github.com/user-attachments/assets/f57e1c11-3639-4c15-8023-3f9efeaf019e)

Analysis:
Among the three models, the Random Forest model has the highest R2 score (0.9152), indicating that it explains the variance in the data the best. Both the Decision Tree and Random Forest models have significantly higher R2 scores compared to the Linear Regression model, suggesting they fit the data better in terms of explaining its variability.

In terms of the mean absolute error (MAE) and root mean squared error (RMSE), lower values indicate better performance. Here, the Decision Tree model has the lowest MAE (987.55) and RMSE (2359.13), which means it has the least average error and deviation from the actual values among the three models.

Conclusion
Best Fit Model: Random Forest
The higher R² score and lower RMSE indicate that the Random Forest model generally performs better in terms of explaining variance and overall prediction accuracy, even though its MAE is higher.


