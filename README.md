# Big_Data

## Overview

Big Data is a terminology used to process a large amount of Data for a specific company; this process is called ‘Natural Language Processing.’ Recently, Jennifer and I were asked by Big Market, a company we currently work for, if we could help a client, Selby, who is about to release many products on a well-known online server. Selby asked if I could analyze other competition and rewards programs so that they could be more competitive. Selby uses Spark, a unified analytics engine that deals with large-scale data processing. Jennifer and I decided to use Spark to further our work and AWS (Amazon Web Services) to store the amount of collected data. 

Once we received the data and understood the system when they began to ETL (Extract, Transform, and Load) the data. Below are screenshots of such a process. 

We started by collecting Data from Amazon DataBase. We looked at the sports review and lined up the columns along with the numbers and statements in the rows:

<img width="1208" alt="Screen Shot 2022-09-25 at 5 25 57 PM" src="https://user-images.githubusercontent.com/106892740/192173003-53387b2b-d456-4bab-a7de-1755895ab473.png">

We then collected the number of customers that participated in the review to further our analysis: 

<img width="280" alt="Screen Shot 2022-09-22 at 6 47 19 PM" src="https://user-images.githubusercontent.com/106892740/192173106-e6504abd-d63d-423a-b1ea-446f50d52598.png">


Once we gathered the information, we had to look at the product, participants, and the dates that they reviewed: 

<img width="569" alt="Screen Shot 2022-09-22 at 6 47 54 PM" src="https://user-images.githubusercontent.com/106892740/192173392-139043f0-7e79-4fbe-ac59-1c503477afbd.png">


We complete with the star rating and votes. We will discuss the review results and the pros and cons of the vine program based on our results.

<img width="665" alt="Screen Shot 2022-09-22 at 6 48 11 PM" src="https://user-images.githubusercontent.com/106892740/192173509-090c0290-4358-40f9-a3e3-7b60efac6c43.png">

## Results:

After completing the task and receiving high satisfaction, we were asked to analyze Amazon’s review program written by paid Amazon members. The Vine program services allow manufacturers and publishers receive reviews for their products to determine the need. We were asked to Extract the information using AWS RDS, transform the information into pgAdmin and load the results into PySpark, pandas, or SQL; we decided to use PySpark to conclude with the results. We also looked at duplicate data and eliminated such data.  


**How many Vine reviews and non-Vine reviews were there?**

We took the total number of reviewers or customers within the database and determined that 4,850,360 customers possibly participated in the review. However, we could not determine how many did not participate because the data continued to show the same number based on review and customer id. 

<img width="544" alt="Screen Shot 2022-09-25 at 5 10 37 PM" src="https://user-images.githubusercontent.com/106892740/192172195-6bc1405f-e86e-4bcc-bd2f-568a1a569e76.png">

**How many paid for the vine program? How many did not pay for the vine program**  

We could draw from the numbers below to determine how many customers participated in the vine program and how and paid or did not pay based on the information given. As we looked a the number, we could see 4,140 paid for the vine program, and 1,442,261 did not pay for the program. As for my first question, stating how many non-vine reviews are there, we can use the paid and non-paid numbers based on participation. However, the numbers would be questionable based on the circumstance of paying or not paying or the number of viewers in the reviewer column.  


<img width="751" alt="Screen Shot 2022-09-25 at 5 12 17 PM" src="https://user-images.githubusercontent.com/106892740/192172480-162b419a-e9aa-4bed-b317-76c0050cfacd.png">

<img width="879" alt="Screen Shot 2022-09-25 at 5 12 27 PM" src="https://user-images.githubusercontent.com/106892740/192172493-ebd0c224-0db8-4235-b3a6-d91b4af4b9ea.png">



**How many Vine reviews were five stars? How many non-Vine reviews were five stars?**

The 5-star viewers look very impressive and questionable; out of the total number of viewers based on the data, 4,850,360 were flagged as 5-star views, and 1,810,240 were not 5-star viewers. The numbers appeared to gear towards the good reviews over the negative views. 

<img width="714" alt="Screen Shot 2022-09-25 at 5 11 09 PM" src="https://user-images.githubusercontent.com/106892740/192172229-18f13004-6830-46f6-8219-f8d440e87755.png">


<img width="761" alt="Screen Shot 2022-09-25 at 5 11 24 PM" src="https://user-images.githubusercontent.com/106892740/192172240-855f7013-cf8d-4b04-8a1e-5a944b598fd8.png">


**What percentage of Vine reviews were five stars? What percentage of non-Vine reviews were five stars?**

The percentage of 5-star and non-5 stars reviewers are unique, but the non-review shows 62.6% out of the total viewers, and the 5-star viewers are 159.5%.  

<img width="761" alt="Screen Shot 2022-09-25 at 5 11 37 PM" src="https://user-images.githubusercontent.com/106892740/192172255-4a93dcc5-0a9b-412f-86a4-062efd009d2f.png">

<img width="831" alt="Screen Shot 2022-09-25 at 5 11 54 PM" src="https://user-images.githubusercontent.com/106892740/192172398-77dd605d-8e8b-44ea-a3a4-f8d46e88055d.png">

## Summary:

Our results are impressive but lacking due to the information given to us. We posted several bullets that concluded without finding. However, we did not have or could not gather additional information to complete a need-to-know for the company. Only a certain amount of the dataset was forwarded to us, and we would like to request additional information. We request the following dataset: 

1. Number of non-participates
2. Age & Gender   

The data appears biased and favors the 5-star reviewers more than the non-five stars and participants. I recommend additional information and analysis to support our findings by addressing all rating stars and gender and age. 


