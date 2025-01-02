Name: Rehan Majid

Company: Prodigy InfoTech

CIN: PIT/JUN24/03902

Domain: DATA SCIENCE

Duration: 1st December2024 to 31st December2024

Project Overview: Predicting Customer Purchases Using a Decision Tree Classifier

This project explores the use of machine learning, specifically a Decision Tree Classifier, to predict whether a customer will purchase a product or service based on historical, demographic, and behavioral data from the Bank Marketing Dataset. The ultimate goal is to derive actionable insights that can improve the efficiency and targeting of marketing campaigns, thereby increasing the likelihood of customer engagement.

Detailed Steps:

Dataset Overview and Problem Understanding The dataset includes information on over 40,000 marketing efforts, each detailing customer attributes and the outcome of the marketing campaigns. The key objective is to classify whether a customer will subscribe to a term deposit (subscribed_deposit: yes/no).
Data Attributes: Customer Demographics: Age, job, marital status, education, etc. Behavioral Data: Previous campaign outcomes, call durations, and contact counts. Economic Indicators: Employment variation rates, consumer price index, consumer confidence index, etc. Target Variable: Whether the customer subscribed to the deposit (yes or no). This diverse set of features makes it possible to capture complex patterns that influence customer decisions.

Data Cleaning and Preparation A thorough cleaning process ensured the dataset was ready for analysis:
Duplicate Records: Identified and removed duplicates to prevent biased model training. Handling Outliers: Applied the IQR method to remove extreme values from critical numerical columns like age, campaign, and duration. Irrelevant Feature Removal: Dropped highly correlated features such as emp.var.rate and euribor3m, which could introduce noise or redundancy in the model. Label Encoding: Transformed categorical variables (e.g., job, marital, poutcome) into numeric values using Label Encoding for machine learning compatibility. 3. Exploratory Data Analysis (EDA) EDA was performed to uncover trends and relationships within the data:

Feature Distributions: Histograms for numerical variables revealed patterns such as age distribution and duration spread. Category Analysis: Count plots of categorical variables like job, education, and poutcome highlighted class imbalances and customer characteristics. Correlation Heatmap: Analyzed relationships among numerical variables to identify potential multicollinearity issues and significant predictors for the target variable. Box Plots: Visualized the impact of features like balance and duration on the target variable to highlight critical trends. 4. Model Implementation A Decision Tree Classifier was built using the cleaned and preprocessed dataset:

Model Configuration:

Criterion: Both Gini Index and Entropy were used to compare impurity measures. Tree Depth: Limited to prevent overfitting while maintaining adequate model complexity. Min Samples Split: Controlled how the tree split further to balance accuracy and generalizability. Training: The model was trained using a split dataset (70% training, 30% testing) to ensure robust evaluation. Key Features: Variables like duration (call duration), previous (number of prior contacts), and poutcome (outcome of the previous campaign) were observed to heavily influence the predictions. 5. Model Evaluation and Performance The Decision Tree model was rigorously tested to evaluate its effectiveness:

Performance Metrics: Accuracy Score: Measured the overall correctness of predictions, showing the model’s effectiveness in distinguishing between subscribed and non-subscribed customers. Confusion Matrix: Evaluated how well the model balanced between false positives and false negatives. Precision, Recall, and F1-Score: Provided a deeper understanding of model performance on each class (yes and no). Results: Training accuracy: ~90% Testing accuracy: ~85-87% (showing minimal overfitting). High recall for the yes class, ensuring fewer missed predictions of potential subscribers. 6. Decision Tree Visualization The decision tree was visualized, offering interpretable insights into the decision-making process:

Structure: The tree structure provided clear, actionable rules, such as: If duration > X and poutcome is success, predict yes. If duration <= Y and campaign > Z, predict no. Feature Importance: Highlighted how features contributed to predictions, enabling the bank to prioritize key influencing factors in their marketing strategy. 7. Advanced Insights Targeting Strategies: Focus on customers with a history of successful interactions (positive poutcome values). Increase engagement with customers contacted for longer durations (duration > threshold). Improve campaigns by avoiding over-contacting (campaign feature). Feature Impact: Economic indicators like euribor3m and emp.var.rate were less relevant, justifying their exclusion in the final model. Class Imbalance Handling: The dataset's natural imbalance was tackled during evaluation, ensuring fair performance metrics. Conclusion and Business Implications The Decision Tree Classifier proved to be an effective tool for predicting customer behavior:

Business Value: Improved targeting of marketing efforts, saving resources by focusing on high-potential leads. Enhanced understanding of customer preferences and behavior patterns. Insights into campaign success factors, allowing for iterative improvements. Next Steps: Experiment with ensemble models (Random Forest, Gradient Boosting) to further boost performance. Use advanced techniques like SMOTE to address class imbalance. Deploy the model in real-world scenarios for live campaign targeting. This project underscores the power of machine learning in data-driven decision-making and its ability to transform marketing strategies into efficient, customer-centric processes.
![image](https://github.com/user-attachments/assets/40f2375a-3109-41e6-ac78-b2fc5ebb10c1)
![image](https://github.com/user-attachments/assets/6eb48548-826b-4551-a9ea-ba35e7d05cf0)
![image](https://github.com/user-attachments/assets/7083d604-59f9-4950-ba16-75f01eea68ed)
![image](https://github.com/user-attachments/assets/cb6740da-973f-4bf8-a1cd-a8bf9a794141)
![image](https://github.com/user-attachments/assets/991a2cd8-3e11-49c4-bffe-08b4917a6d42)
![image](https://github.com/user-attachments/assets/42596013-e9f3-478b-8fde-e0e801aea80a)
![image](https://github.com/user-attachments/assets/7d36422d-1966-4857-a8f7-5c1063e86d1b)
![image](https://github.com/user-attachments/assets/bf229cb9-327f-43a8-986f-c2bf9b2d754f)
![image](https://github.com/user-attachments/assets/bcdcce83-c5cb-4372-8e14-a9dc69c9c376)
![image](https://github.com/user-attachments/assets/9896970e-d5bb-4058-897d-ee8590509fd4)
![image](https://github.com/user-attachments/assets/31d356ab-60dd-4add-9657-db166c054fbb)
![image](https://github.com/user-attachments/assets/e0e37348-0db1-4159-b7a3-1575e853534e)
![image](https://github.com/user-attachments/assets/9322cf68-d4d2-4d38-97da-afe68f53f88d)
![image](https://github.com/user-attachments/assets/a55b51ab-14ae-407f-a622-e4f24fdfc95a)
![image](https://github.com/user-attachments/assets/a879b879-8df8-47bf-88cb-70e6809f20dc)
![image](https://github.com/user-attachments/assets/1c4aa93d-06c3-4970-b496-bf485e63894b)
![image](https://github.com/user-attachments/assets/cd9f995d-9a1f-462d-a825-8f99d9a6f6bf)
![image](https://github.com/user-attachments/assets/5298c11b-1b74-4319-9a94-bbd3c859e4b1)
![image](https://github.com/user-attachments/assets/3e8f33a6-557e-44cf-9eb9-6c3feeaf4570)
![image](https://github.com/user-attachments/assets/b664b31c-3659-4aa9-9013-863a56bda9ce)
![image](https://github.com/user-attachments/assets/15526193-577e-40ba-a2cb-695075cdf6f1)
![image](https://github.com/user-attachments/assets/70586c6a-c801-476f-8c8a-392f814dba34)
![image](https://github.com/user-attachments/assets/1e247fa3-1ba3-4c07-8778-207045706f2a)
![image](https://github.com/user-attachments/assets/b38e47d3-a3de-4b50-bb0f-f7bff4d6b199)
![image](https://github.com/user-attachments/assets/a5b413c8-5536-4f3e-bc37-c93a5f162297)
![image](https://github.com/user-attachments/assets/01898ecb-c562-4bc1-85d9-9fe1c7c04a5c)
![image](https://github.com/user-attachments/assets/402e7a9d-ea14-4d3f-b1b5-358df78616a7)
![image](https://github.com/user-attachments/assets/52edd5fe-dc07-418f-856f-9070c5bbf803)
