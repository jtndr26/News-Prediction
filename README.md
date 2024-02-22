
# Online News Popularity Prediction
 - Predictive Analysis




## Authors

- [Jeetendra Sarpe](https://github.com/jtndr26)


### Business Context:
The surge in online news consumption, propelled by smartphone usage and social media prevalence, presents a lucrative opportunity for content creators and publishers. With easily produced, compact, and cost-effective news articles gaining traction on social sharing platforms, understanding their popularity and longevity becomes crucial. Analyzing online news content allows businesses to predict article recognition and assess the decay of interest over time, enabling them to tailor their content strategies for maximum impact and audience engagement.

### Project Description:
The consumption of online news is expediting day by day due to the extensive adoption of smartphones and the rise of social networks. Online news content includes various key properties like it is easily produced, it is small in size, its lifespan is short and the cost is low. Such qualities make news content more effective to be consumed on social sharing platforms. More interestingly, such content can capture the eye of a signiﬁcant amount of internet users within a brief period of time. As a result, the main target on the analysis of online news content, like predicting the recognition of story articles and demonstrating their decay of interest over time, has significantly increased since it has so many practical meanings.

### Data Overview

<img width="998" alt="features" src="https://github.com/jtndr26/News-Prediction/assets/78334379/8ea8758f-a55d-45c0-b280-41789ce57e99">
Data dictionary:
https://drive.google.com/file/d/1hb5aoKteX25tDh5NQpW_Vx7uw6VetFIi/view?usp=sharing



**Colab Notebook**:
https://drive.google.com/file/d/1LvVjl31BY_OzkUYPDsTam_9vQdWhSe8y/view?usp=sharing


## Approach

1. **Data Preprocessing:** Clean and prepare the dataset by handling missing values, encoding categorical variables, and scaling numerical features.
2. **Principal Component Analysis (PCA):** Apply PCA to reduce the dimensionality of the dataset while preserving as much variance as possible. This helps in simplifying the data and speeding up subsequent regression algorithms.
3. **Linear Regression:** Utilize linear regression to build a baseline model for predicting the popularity of online news articles. Evaluate the model's performance using appropriate metrics such as mean squared error or R-squared.
4. **Lasso Regression:** Implement Lasso regression to perform feature selection and regularization, effectively shrinking the coefficients of less important features to zero. This helps in identifying the most influential predictors of article popularity.
5. **Ridge Regression:** Employ Ridge regression to mitigate multicollinearity and improve the robustness of the model by penalizing large coefficient values. Compare the performance of Ridge regression with linear regression and Lasso regression to determine the optimal regularization technique.
6. **Model Evaluation:** Evaluate the performance of all regression models using cross-validation techniques and assess their predictive accuracy and generalization capabilities.
7. **Model Optimization:** Fine-tune hyperparameters of the regression models using grid search or randomized search to further enhance their performance and achieve optimal results.
8. **Final Model Selection:** Select the regression model with the highest predictive performance and interpretability for predicting the popularity of online news articles based on the chosen features.

![image](https://github.com/jtndr26/News-Prediction/assets/78334379/5905652e-d7de-4c7f-b161-fecfb9f97cbe)


## **Result**: 

Based on the analysis, the Lasso Regression model emerges as the most suitable solution for predicting the popularity of online news articles. Its superior performance in terms of R-squared score, Residual Sum of Squares (RSS), and Root Mean Squared Error (RMSE) on both training and testing datasets indicates its effectiveness in accurately forecasting article popularity. Therefore, leveraging the Lasso Regression model can provide valuable insights to online news platforms, enabling them to optimize content creation strategies, tailor marketing efforts, and enhance user engagement, ultimately leading to increased readership and revenue generation.

## **Conclusion**:
Based on the business context of the growing consumption of online news content and the need to predict article popularity and interest decay over time, the analysis of regression models reveals that Lasso Regression offers the most promising solution for predicting the popularity of online news articles. Leveraging Lasso Regression allows online news platforms to optimize content strategies, enhance user engagement, and adapt to evolving consumer preferences effectively. While the improvement in predictive accuracy is moderate, the insights gained from Lasso Regression can significantly contribute to achieving business goals and maintaining competitiveness in the online news industry.
