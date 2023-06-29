<h1><center> Analysis of British Airline Airways by BELLO ISMAHEEL. </center></h1>

## Outline

- Introduction
- Research Questions
- Insights and Conclusions

### Introduction

In this project, we aim to gain insights into customer sentiments and opinions about British Airways by analyzing customer reviews from [Skytrax](https://airlinequality.com). By web scraping information from this popular platform, we will collect a diverse range of customer feedback on various aspects of their experiences with British Airways.

The dataset obtained from airlinequality.com includes several factors that customers rate, such as seat comfort, cabin staff service, food & beverages, ground service, value for money, inflight entertainment, and more. These factors, along with other relevant information such as the reviewer's name, rating, date published, country, trip details, and aircraft, will provide us with a comprehensive understanding of customer sentiments towards British Airways.

To ensure the accuracy and relevance of our analysis, we will perform data cleaning and preprocessing techniques on the gathered data. This step is crucial for handling missing values, standardizing formats, and removing any noise or inconsistencies that may affect the reliability of our findings.

<h2><center>Research Questions</center></h2>

1. Top 5 Customer Origins for Review Submissions.
2. Top 20 Aircraft with the best Average Rating.
3. Top 20 Aircraft with the least Average Rating.
4. Is there an association between the overall rating and specific factors (Seat Comfort, Cabin Staff Service, Food & Beverages, Ground Service, Value for Money, Inflight Entertainment, Wifi & Connectivity) of British Airways flights?
5. How do the ratings for different factors change over time for British Airways flights.
6. Is there a relationship between the overall rating and the verified trip status of the reviewers on British Airways flights?
7. What are the most frequent words used by customers in their reviews of British Airways?

<h2><center> Insights and Conclusions</center></h2>

### 1. Top 5 Customer Origins for Review Submissions.


Based on the results, it is evident that a significant portion of customer feedback originates from key countries such as the United Kingdom, United States, Australia, Canada, and Germany. These countries contribute the highest volume of customer feedback regarding the airline experience.

<div style="text-align: center;">
  <img src="top5review.png" alt="Image Description" />
</div>


### 2. Top 20 Aircraft with the best Average Rating.

The analysis reveals that approximately 15 aircraft have received exceptional customer satisfaction across various aspects, including Seat Comfort,Cabin Staff Service,Food & Beverages,Ground Service,Value for Money,Inflight Entertainment,Wifi & Connectivity,and more. Notable aircraft associated with high customer satisfaction include Boeing 747 / A320, A319 / Boeing 777-300, A380 and Boeing 777, Boeing 747-400, A320, A319, A340-300, A320, Boeing 747 and Boeing 777, B737-400 / A380 / A319, B777-300ER / A320 / A380, Boeing 777-236 ER, B747 400, A320, Boeing 777, B747-400 in retro, A319 / Boeing 787-9, Boeing 747-400 / A320, Saab 2000, and SAAB 2000.

These aircraft have consistently met or exceeded customer expectations across various service dimensions, resulting in high levels of customer satisfaction. Their performance in terms of amenities, staff service, onboard comfort, entertainment, and value for money has resonated positively with customers. The satisfaction expressed by customers towards these specific aircraft highlights their effectiveness in delivering an exceptional airline experience.

<div style="text-align: center;">
  <img src="top10bestr.png"/>
</div>

### 3. Top 20 Aircraft with the least Average Rating.

The interpretation of the result suggests that there is a group of aircraft models, including Boeing 777 200/300, Boeing 777, A319 / Boeing 789, Boeing 777-200, Dreamliner, Boeing 777 200, A380 and 747, Boeing 747-300, A322, A230, Boeing 747 & A319, Boeing 737-400, Boeing 737 800, 777-200, Various, A320 / Boeing 777-200, Boeing 747-400, A320 / Boeing 777-300, A321Neo, and A321-neo, that have received relatively low overall ratings from customers.

The overall ratings of 2/10 for these aircraft indicate a significant level of dissatisfaction among customers who have flown on them. Furthermore, there are other aircraft models that have even lower ratings of 1/10, signifying an even higher level of dissatisfaction.

These low ratings highlight the need for improvement in various aspects of the airline experience provided by these specific aircraft models. Customers may have expressed dissatisfaction with factors such as seat comfort, cabin staff service, food and beverages, ground service, value for money, inflight entertainment, wifi and connectivity, or other aspects of the overall flight experience.

To address these concerns, British Airways should carefully examine customer feedback and reviews related to these aircraft models. Identifying and rectifying the specific issues and shortcomings mentioned by customers can lead to improved customer satisfaction and an enhanced flying experience. It is crucial for the airline to prioritize customer feedback and take proactive measures to address the areas of concern raised by customers for these particular aircraft models.

<div style="text-align: center;">
  <img src="least10bestr.png"/>
</div>


### 4. Is there an association between the overall rating and specific factors (Seat Comfort, Cabin Staff Service, Food & Beverages, Ground Service, Value for Money, Inflight Entertainment, Wifi & Connectivity) of British Airways flights?

I have examined the association between the overall rating and specific factors (Seat Comfort, Cabin Staff Service, Food & Beverages, Ground Service, Value for Money, Inflight Entertainment, Wifi & Connectivity) of British Airways flights. The correlation coefficients obtained from the analysis are as follows:

- Seat Comfort: The correlation coefficient between the overall rating and seat comfort is 0.720802. This indicates a strong positive correlation, suggesting that customers who perceive higher seat comfort tend to give higher overall ratings.

- Cabin Staff Service: The correlation coefficient between the overall rating and cabin staff service is 0.692213. This implies a strong positive correlation, indicating that customers who experience better cabin staff service are more likely to provide higher overall ratings.

- Food & Beverages: The correlation coefficient between the overall rating and food & beverages is 0.719577. This suggests a strong positive correlation, indicating that customers who are satisfied with the food and beverages offered onboard are more inclined to give higher overall ratings.

- Ground Service: The correlation coefficient between the overall rating and ground service is 0.712212. This reveals a strong positive correlation, implying that customers who have positive experiences with the ground service provided by British Airways tend to give higher overall ratings.

- Value for Money: The correlation coefficient between the overall rating and value for money is 0.862426. This demonstrates a very strong positive correlation, indicating that customers who perceive higher value for money in their flight experience are more likely to provide higher overall ratings.

- Inflight Entertainment: The correlation coefficient between the overall rating and inflight entertainment is 0.636917. This suggests a moderate positive correlation, indicating that customers who are satisfied with the inflight entertainment options are more inclined to give higher overall ratings.

- Wifi & Connectivity: The correlation coefficient between the overall rating and wifi & connectivity is 0.594821. This suggests a moderate positive correlation, implying that customers who have a positive experience with the wifi and connectivity services provided by British Airways are more likely to provide higher overall ratings.

Based on these findings, it is evident that there is a positive association between the overall rating and the specific factors mentioned. This suggests that customers' perceptions of seat comfort, cabin staff service, food & beverages, ground service, value for money, inflight entertainment, and wifi & connectivity significantly impact their overall rating of British Airways flights. The airline can focus on enhancing these factors to improve the overall customer experience and satisfaction.

<div style="text-align: center;">
  <img src="heatmap.png"/>
</div>


### 5. How do the ratings for different factors change over time for British Airways flights.

The ratings for specific factors such as Seat Comfort, Cabin Staff Service, Food & Beverages, Ground Service, Value for Money, Inflight Entertainment, and Wifi & Connectivity have been analyzed over time. The data reveals that customers, on average, expressed exceptional satisfaction towards these factors predominantly during the period from September to December 2015. Additionally, towards the end of 2021, there was another notable increase in customer satisfaction for these factors.

Overall, the trend for these services has remained stable, indicating a consistent level of satisfaction or dissatisfaction. However, it is important to note that during the periods mentioned earlier (September to December 2015 and the end of 2021), there were exceptional levels of satisfaction reported by customers.

<div style="text-align: center;">
  <img src="over_time.png"/>
</div>


### 6. Is there a relationship between the overall rating and the verified trip status of the reviewers on British Airways flights?

A statistical analysis using a two-sample independent t-test was conducted to examine the potential relationship between the overall ratings and the verified trip status of reviewers for British Airways flights. The obtained p-value was 7.509296177167211e-08. With a chosen significance level (alpha) of 0.05, this p-value indicates a significant relationship between the overall rating and the verified trip status of the reviews.

In simpler terms, the statistical test suggests that there is a meaningful and statistically significant association between the overall ratings given by reviewers and their verified trip status. This implies that the verified trip status of reviewers has an impact on the overall rating they provide for British Airways flights.

Additionally, a boxplot was utilized to examine the distribution of overall ratings based on the verified trip status of reviews. The boxplot reveals that there is a wide range of variability among reviewers whose trips are verified. It indicates that a significant number of reviewers with verified trips tend to provide lower overall ratings for their trips. However, there are also a few reviewers who rate their trips exceptionally well. Only a small proportion of reviewers fall around the average rating.

In simpler terms, the boxplot analysis shows that reviewers whose trips are verified exhibit a diverse range of opinions in their overall ratings. While some of them have negative experiences and rate their trips poorly, others have extremely positive experiences and rate their trips highly.

Only a minority of reviewers fall within the average rating range. This suggests that the verified trip status of reviewers can significantly influence their perception and evaluation of British Airways flights.

On the contrary, for reviewers whose trips have not been verified, the majority of them provide higher overall ratings for their trips. However, there are still some reviewers who give poor ratings. Only a small portion of reviewers fall within the average rating range.

In simpler terms, reviewers whose trips have not been verified tend to have more positive perceptions of their trips, as indicated by their higher overall ratings. However, there are still some reviewers who have negative experiences and rate their trips poorly. The number of reviewers falling within the average rating range is relatively low. This suggests that the verified trip status plays a role in shaping the reviewers' evaluations, with non-verified reviewers generally showing more positive attitudes toward British Airways flights compared to verified reviewers.

<div style="text-align: center;">
  <img src="rel.png"/>
</div>


### 7. What are the most frequent words used by customers in their reviews of British Airways?

Customers are discussing various aspects of their experience with the airline. These aspects include the behavior and attitude of the staff, the quality and variety of the food provided, the performance and professionalism of the crew members, the overall service received, positive attributes they have observed, the efficiency of check-in processes, and factors related to timing such as punctuality and delays. By analyzing these discussions, airlines can gain insights into what customers prioritize and what aspects of their service they appreciate or find lacking.

<div style="text-align: center;">
  <img src="wordcloud.png"/>
</div>


Based on the sentiment analysis of 3,586 reviews, it was found that approximately 70.5% (2,529 reviews) were classified as positive, about 29.1% (1,043 reviews) were categorized as negative, and a small portion of about 0.4% (14 reviews) fell into the neutral category.

<div style="text-align: center;">
  <img src="sentiment.png"/>
</div>
