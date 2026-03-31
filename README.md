Spotify User Behavior Analysis
1. Project Overview

This project analyzes a synthetic dataset that simulates user behavior on Spotify, one of the world’s leading music streaming platforms. The dataset contains 5000 user records designed to reflect realistic user engagement, subscription behavior, and advertisement interactions.

The objective of this project is to derive meaningful insights related to:

User engagement patterns
Subscription behavior and conversion trends
User churn and inactivity
Marketing effectiveness through advertisements

This project is suitable for data analysis, dashboard development, and introductory machine learning applications.

2. Dataset Information
Total Records: 5000
Total Columns: 18
Data Type: Synthetic (realistic simulation)
Domain: Music Streaming / User Analytics
Platform Context: Spotify-like environment
File Format: CSV
3. Data Dictionary
Column Name	Description	Data Type
user_id	Unique identifier assigned to each user	Integer
country	Country where the user is located	Categorical
age	Age of the user	Integer
signup_date	Date when the user signed up	Date
subscription_type	Type of plan (Free, Premium, Family, Student)	Categorical
subscription_status	Indicates whether the subscription is Active or Inactive	Categorical
months_inactive	Number of months the user has been inactive	Integer
inactive_3_months_flag	1 = inactive ≥ 3 months, 0 = active/recent	Binary
ad_interaction	Indicates whether the user interacted with advertisements	Binary
ad_conversion_to_subscription	Indicates whether ad led to subscription conversion	Binary
4. Key Features
Simulates realistic user behavior on Spotify
Includes both free-tier and premium users
Tracks subscription lifecycle and inactivity
Captures advertisement interaction and conversion behavior
Supports churn analysis and user segmentation
5. Exploratory Data Analysis (EDA)
5.1 User Distribution
Analyze how users are distributed across different countries
Identify regions with higher platform usage
5.2 Subscription Analysis
Compare Free vs Premium subscription usage
Evaluate active vs inactive users
5.3 Churn Analysis
Use months_inactive and inactive_3_months_flag
Identify inactivity patterns and potential churn
5.4 Marketing Effectiveness
Analyze relationship between ad_interaction and conversion
Evaluate advertisement impact on subscription
5.5 Demographic Analysis
Study age distribution
Identify key user segments
6. Key Analytical Questions
What factors influence subscription upgrades on Spotify?
Which countries show higher engagement levels?
How does inactivity contribute to churn?
Do advertisements lead to subscription conversion?
Which user segments are most valuable?
7. Use Cases
User behavior analysis
Churn prediction modeling
Marketing analytics
Customer segmentation
Data visualization and reporting
8. Disclaimer

This dataset is synthetically generated for educational purposes and does not contain real user data from Spotify. It is designed to simulate realistic behavior patterns for analysis and learning.

9. Conclusion

This project presents a structured approach to analyzing user behavior on Spotify. By leveraging demographic, subscription, and interaction data, meaningful insights can be derived to improve user engagement, retention, and overall business performance.
