# Project 1
## Question: Option 1: Let’s say you’re a Product Data Scientist at Instagram. How would you measure the success of the Instagram TV product?

As a Product Data Scientist at Instagram, measuring the success of the Instagram TV (IGTV) product would involve a combination of quantitative and qualitative metrics to assess various aspects of its performance and user engagement. Here are some key metrics and approaches you might use:

1. # **User Engagement Metrics:**
   - **Viewership:** Monitor the number of views, view duration, and the growth of these metrics over time. This helps in understanding how many users are engaging with IGTV content.
   - **Likes, Comments, and Shares:** Track user interactions with IGTV videos, such as likes, comments, and shares. Higher engagement indicates that users find the content compelling.
   - **Followers:** Analyze how IGTV content affects the growth of followers for both individual creators and the IGTV platform as a whole.
   - **User Retention:** Measure how frequently users return to IGTV and how often they engage with the platform. High retention rates indicate sustained interest.

2. # **Content Metrics:**
   - **Content Uploads:** Monitor the frequency of content uploads by creators. More content uploads could indicate a healthy ecosystem.
   - **Content Categories:** Analyze which types of content (e.g., tutorials, vlogs, music videos) are most popular and which ones drive user engagement.

3. # **Monetization Metrics:**
   - **Ad Revenue:** If IGTV is monetized through advertising, track the revenue generated from ads. Increasing ad revenue could be a sign of success.
   - **Sponsored Content:** Measure the number of sponsored posts and their impact on revenue.

4. # **User Feedback and Surveys:**
   - Conduct user surveys and collect feedback to understand user satisfaction, pain points, and suggestions for improvement.

5. # **Retention and Churn Analysis:**
   - Analyze user churn rates to understand why users stop using IGTV. Identifying reasons for churn can help in making product improvements.

6. # **Content Discovery Metrics:**
   - Track how users discover IGTV content, whether through the Explore page, hashtags, recommendations, or other methods.

7. # **Audience Demographics:**
   - Understand the demographics of IGTV users and viewers. This information can help in targeting content and advertising effectively.

8. # **Competitor Benchmarking:**
   - Compare IGTV's performance metrics with those of competing platforms like YouTube or TikTok to assess its competitive position.

9. # **Technical Performance:**
   - Monitor the technical performance of the IGTV platform, including video loading times, playback quality, and any technical issues reported by users.

10. # **User Behavior Analysis:**
    - Analyze user behavior patterns within the IGTV app, such as the time spent watching videos, the frequency of visits, and the paths users take through the platform.

Success in the context of IGTV could vary depending on Instagram's specific goals and objectives for the product, such as increasing user engagement, retaining users, generating revenue, or competing effectively in the online video market. Therefore, it's essential to align the measurement approach with the product's strategic goals and iterate based on data-driven insights to drive continuous improvement.


## **Question 2:**
    - Option 2: Imagine you're working with Sprint, one of the biggest telecom companies in the USA. They're really keen on figuring out how many customers might decide to leave them in the coming months. Luckily, they've got a bunch of past data about when customers have left before, as well as info about who these customers are, what they've bought, and other things like that. So, if you were in charge of predicting customer churn, how would you go about using machine learning to make a good guess about which customers might leave? What steps would you take to create a machine learning model that can predict if someone's going to leave or not?

1. # **Data collection**
    - Collect the neccessary past data of all the customers from sprint telecom services and make sure to include the features that are relevant to the churn prediction. the data set can include demographics, usage patterns, and whether or not the user should be churned.

2. # **Data processing**
    - here clean and process the dataset. this includes handling missing values, encoding categorical values, scaling numerical features and feature engineering.

3. # **Exploratory Data Analysis**
    - Here we perform visualizations and analysing the dataset to get insights into the data. Look for patterns and correlations and anomalies that can inform our data modeling decisions. EDA helps to analyse the data properly and select relevant models features for the data.

4. # **Model selection**
    - Choose the appropriate machine learning model for the churn predictions.
    Common models for churn prediction include logistic regression, decision trees, random forests, gradient boosting, and neural networks. The choice of model depends on the dataset and the problem's complexity.

5. # **Model Training and Evaluation**
    - We split the data into training and testing datasets and evaluate the choosen models. We shall use the appropriate evaluations for accuracy, precision, recall, F1-score, and ROC AUC to asses the models performance.

6. # **Hyperparameter training**
    - We may need to fine-tune the hyperparameters of our selected model to optimize its performance. Techniques like grid search or random search can be used for this purpose.

7. # **Model deployment**
    - Once we have a well-performing model, we can deploy it in a production environment, allowing the telecom company to use it for real-time or batch churn predictions.