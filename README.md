# Doctor-s-Fee-Prediction

## Objective
1. To scrape the information of doctors from Delhi, Mumbai and Bangalore registered on Practo.

2. To create a machine learning model that predicts the doctor’s consultation fee.

3. Deploying the model trained on web.


## Tools Used
1. Python - Beautiful Soup, Selenium, Pandas, Scikit-learn, Flask
2. HTML & CSS


## Input Parameters
1. City
2. Specialization
3. Qualification
4. Experience
5. Ratings
6. Upvotes


## Insights

![image](https://user-images.githubusercontent.com/68947631/215343399-6b81a305-9510-4b85-8603-d1e82f784f7f.png)

Insight 1: Majority of the doctors had 15 years of experience and there is a skewness towards years of experience beyond 15 years of experience.

![image](https://user-images.githubusercontent.com/68947631/215343744-4133f951-3a2c-4907-9c31-88e66c69065f.png)

Insight 2: Of the three cities included in the study (Bangalore, Delhi, Mumbai), Bangalore had the maximum number of doctors, followed by Delhi and then Mumbai. While the difference between Delhi and Mumbai wasnt too much but there seemed a significant difference between the number of doctors from Bangalore and other two cities.

![image](https://user-images.githubusercontent.com/68947631/215344281-b6f6212d-71c4-4c3d-8b19-59805287f683.png)

Insight 3: MBBS is the qualification held by majority of the doctors. MBBS, BHMS, MD, MS, MA, BPT, BAMS are among the most famous education qualifications among the doctors registered in Practo.

![image](https://user-images.githubusercontent.com/68947631/215343666-ad37e709-3172-49d4-8257-5a0264d6ac52.png)

Insight 4: While maximum doctors charged approximately 500 ruppees as consultation fees, however, the data shows that the doctor's consulation fee is skewed towards higher amount. This is well aligned with the data for the number of years of experience of doctors.

![image](https://user-images.githubusercontent.com/68947631/215344638-cb8e6de0-5c57-4fd6-aa1c-d9f768596e6b.png)

Insight 5: The median consultation fees is least in Bangalore. While the median consultation fees is almost the same in Delhi and Mumbai. This can be related to the competition in terms of the number of doctors registered from Bangalore. Since Bangalore has maximum number of doctors so it can also be a reason why the consultation fees are least there. 


## Model Summary
![image](https://user-images.githubusercontent.com/68947631/215345121-41b6bd6c-ddce-4be3-a2b6-50ac1279936d.png)

Thus, in this project we went with linear regression, since it gives maximum R2 value and least MSE and RMSE.
