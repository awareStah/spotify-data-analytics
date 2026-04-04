# Spotify User Behavior Analysis

## Project Overview
This project analyzes a synthetic dataset that simulates user behavior on Spotify, one of the world’s leading music streaming platforms. The dataset contains 5000 user records designed to reflect realistic user engagement, subscription behavior, and advertisement interactions.

The objective of this project is to derive meaningful insights related to:
- User engagement patterns  
- Subscription behavior and conversion trends  
- User churn and inactivity  
- Marketing effectiveness through advertisements  

This project is suitable for data analysis, dashboard development, and introductory machine learning applications.

---

![WhatsApp Image 2026-04-01 at 04 43 07](https://github.com/user-attachments/assets/83db4aa7-257e-4d28-b67c-7639188b5f5b)




## Dataset Information

- Total Records: 5000  
- Total Columns: 18  
- Data Type: Synthetic (realistic simulation)  
- Domain: Music Streaming / User Analytics  
- Platform Context: Spotify-like environment  
- File Format: CSV  

---

## Data Dictionary

| Column Name | Description | Data Type |
|------------|------------|----------|
| user_id | Unique identifier assigned to each user | Integer |
| country | Country where the user is located | Categorical |
| age | Age of the user | Integer |
| signup_date | Date when the user signed up | Date |
| subscription_type | Type of plan (Free, Premium, Family, Student) | Categorical |
| subscription_status | Indicates whether the subscription is Active or Inactive | Categorical |
| months_inactive | Number of months the user has been inactive | Integer |
| inactive_3_months_flag | 1 = inactive ≥ 3 months, 0 = active/recent | Binary |
| ad_interaction | Indicates whether the user interacted with advertisements | Binary |
| ad_conversion_to_subscription | Indicates whether ad led to subscription conversion | Binary |
| music_suggestion_rating_1_to_5 | Rating given by user to music recommendations (1–5) | Integer |
| avg_listening_hours_per_week | Average weekly listening time in hours | Float |
| favorite_genre | User’s preferred music genre | Categorical |
| most_liked_feature | Feature most liked by the user (e.g., Playlists, Radio, AI DJ) | Categorical |
| desired_future_feature | Feature user wants in the future | Categorical |
| primary_device | Device used for streaming (Mobile, Desktop, Tablet, etc.) | Categorical |
| playlists_created | Number of playlists created by the user | Integer |
| avg_skips_per_day | Average number of songs skipped per day | Float |

---


## Key Features

- Simulates realistic user behavior on Spotify  
- Includes both free-tier and premium users  
- Tracks subscription lifecycle and inactivity  
- Captures advertisement interaction and conversion behavior  
- Supports churn analysis and user segmentation  

---

## Exploratory Data Analysis (EDA)

### User Distribution
- Analyze how users are distributed across different countries  
- Identify regions with higher platform usage  

### Subscription Analysis
- Compare Free vs Premium subscription usage  
- Evaluate active vs inactive users  

### Churn Analysis
- Use months_inactive and inactive_3_months_flag  
- Identify inactivity patterns and potential churn  

### Marketing Effectiveness
- Analyze relationship between ad_interaction and conversion  
- Evaluate advertisement impact on subscription  

### Demographic Analysis
- Study age distribution  
- Identify key user segments  

---

## Key Analytical Questions

- What factors influence subscription upgrades on Spotify?  
- Which countries show higher engagement levels?  
- How does inactivity contribute to churn?  
- Do advertisements lead to subscription conversion?  
- Which user segments are most valuable?  

---

## Use Cases

- User behavior analysis  
- Churn prediction modeling  
- Marketing analytics  
- Customer segmentation  
- Data visualization and reporting  

---

# Dashboard Interaction 
<a href = "https://github.com/awareStah/spotify-data-analytics/blob/main/Screenshot%202026-03-31%20231928.png">View Dashboard</a>

<img width="805" height="644" alt="Screenshot 2026-03-31 232225" src="https://github.com/user-attachments/assets/83b53b04-404d-474e-ba0d-2a1aa8479bec" />


## Disclaimer

This dataset is synthetically generated for educational purposes and does not contain real user data from Spotify. It is designed to simulate realistic behavior patterns for analysis and learning.

---

## Conclusion

This project presents a structured approach to analyzing user behavior on Spotify. By leveraging demographic, subscription, and interaction data, meaningful insights can be derived to improve user engagement, retention, and overall business performance.



