# Text-Analysis

---

- [1. Introduction of Text Analysis](#1-introduction-of-text-analysis)
- [2. SNP Feedback Analysis](#2-snp-feedback-analysis)
  - [2.1 Course Recommendations for New Customers](#21-course-recommendations-for-new-customers)
  - [2.2 Course Recommendations for Existing Customers](#22-course-recommendations-for-existing-customers)
- [3. Yelp Customers' Reviews Analysis](#3-yelp-customers'-reviews-analysis)
  - [3.1 Machine Learning in Python](#31-machine-learning-in-python)
  - [3.2 AWS and GCP ML Text Analysis](#32-aws-and-gcp-ml-text-analysis)
 
 ---
 
 ## 1. Introduction of Text Analysis
 Text analysis, or [natural language processing](https://en.wikipedia.org/wiki/Natural_language_processing) is the process of cleaning texts, digging out patterns behinds raw words, and combine texts with machine learning models. In this part, two projects related with text analysis are included. For the [SNP feedback analysis](https://github.com/Zhenyu0521/Text-Analysis/tree/master/SNP%20Feedback%20Analysis), I applied NLTK packages in Python to help SNP, one of educational companies, explore its customers' feedback of different courses and extracted some insights about its customers and markets. For the [Yelp reviews analysis](https://github.com/Zhenyu0521/Text-Analysis/tree/master/NLP%20for%20Yelp%20Reviews), I used math and statistics to get text in a format that the machine learning algorithms can understand and built up a machine learning model to predict restaurants' stars based on customers' reviews. What's more, I also applied AWS and GCP to conduct text analysis.
 
 ## 2. [SNP Feedback Analysis](https://github.com/Zhenyu0521/Text-Analysis/tree/master/SNP%20Feedback%20Analysis)
By analyzing SNP's feedback data, including numerical and text data, our team helped SNP provide recommendations for new customers and determine the way to further improve SNP's courses.

### 2.1 Course Recommendations for New Customers
Based on SNP’s Customers’ feedback analysis, the clients from different industries show different preference for courses based on their ratings. In order to uncover these preferences, our team grouped all customers/companies into their respective industries (entertainment, internet, computer software, computer hardware, etc.).

Next, we aggregated the customers’ numerical ratings from ‘Please rate your overall satisfaction with the training’, ‘Expectations [Overall, how was your experience compared to your expectations coming into the class?]’ and created an average score that was accessible and understandable. Based on this analysis, we are able to provide recommendations for the top 5 industries: internet, computer software, insurance, health care and e-learning. The results are as follow: 
![average_rating](https://github.com/Zhenyu0521/Text-Analysis/blob/master/SNP%20Feedback%20Analysis/Pics/average%20ratings.png)

### 2.2 Course Recommendations for Existing Customers
Based on conversations with SNP, we understand that many existing customers who have finished courses are still eager to learn more. This feedback is captured by the question ‘Going forward, what other skills are you interested in developing?’. Our group collected key words from these comments to analyze what customers still want to learn. The process included removing stopwords, deleting punctuations, and visualizing words' frequencies by the [NLTK package in Python](https://github.com/Zhenyu0521/Text-Analysis/blob/master/SNP%20Feedback%20Analysis/SNP%20Proposal%202.1%20Final.ipynb).

According to this analysis, if such desired courses exists, SNP can send customers emails of course recommendations. However, if such courses/skills do not currently exist, it could be an opportunity for SNP to potentially create a new products if there is enough demand. Once the courses is created, SNP can send emails to those customers have expressed interest in them. Our group used text analysis to help SNP identify some skills that customers are interested in learning. The graph below shows a list of the most frequently identified terms/skills, and the number of times each word was recorded.
![word frequency](https://github.com/Zhenyu0521/Text-Analysis/blob/master/SNP%20Feedback%20Analysis/Pics/word%20frequency.png)
 
Based on this analysis, our group is able to provide the following recommendations for the top three industries:
![recommendations](https://github.com/Zhenyu0521/Text-Analysis/blob/master/SNP%20Feedback%20Analysis/Pics/recommendations.png)
 
 
 ## 3. [Yelp Customers' Reviews Analysis](https://github.com/Zhenyu0521/Text-Analysis/tree/master/NLP%20for%20Yelp%20Reviews)

### 3.1 Machine Learning in Python
