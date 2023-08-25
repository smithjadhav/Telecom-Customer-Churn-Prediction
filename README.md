<div align="right">
  
[1]: https://github.com/smithjadhav
[2]: https://www.linkedin.com/in/smitesh-jadhav-2030ds


[![github](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/c292abd3f9cc647a7edc0061193f1523e9c05e1f/icons/git.svg)][1]
[![linkedin](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/9f5c4a255972275ced549ea6e34ef35019166944/icons/iconmonstr-linkedin-5.svg)][2]

</div>


# <div align="center">Telecom Customer Churn Prediction</div>

![Intro](https://github.com/smithjadhav/Telecom-Customer-Churn-Prediction/assets/40405066/024de281-7072-41d7-a38e-c24f4733b028)




## What is Customer Churn?
Customer churn is defined as when customers or subscribers discontinue doing business with a firm or service.

Customers in the telecom industry can choose from a variety of service providers and actively switch from one to the next. The telecommunications business has an annual churn rate of 15-25 percent in this highly competitive market.

Individualized customer retention is tough because most firms have a large number of customers and can't afford to devote much time to each of them. The costs would be too great, outweighing the additional revenue. However, if a corporation could forecast which customers are likely to leave ahead of time, it could focus customer retention efforts only on these "high risk" clients. The ultimate goal is to expand its coverage area and retrieve more customers loyalty. The core to succeed in this market lies in the customer itself.

Customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers.

To detect early signs of potential churn, one must first develop a holistic view of the customers and their interactions across numerous channels.As a result, by addressing churn, these businesses may not only preserve their market position, but also grow and thrive. More customers they have in their network, the lower the cost of initiation and the larger the profit. As a result, the company's key focus for success is reducing client attrition and implementing effective retention strategy.
## Objectives:
- Finding the % of Churn Customers and customers that keep in with the active services.
- Analysing the data in terms of various features responsible for Customer Churn
- Finding a most suited machine learning model for the correct classification of Churn and non-churn customers.

## Dataset:
 [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

### The data set includes information about:

- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents
## Implementation:

**Libraries:** sklearn, Matplotlib, pandas, seaborn, and NumPy



## Few glimpses of EDA:
### 1. Churn distribution:

> ![Churn distribution](https://github.com/smithjadhav/Telecom-Customer-Churn-Prediction/assets/40405066/f6721972-cd32-4b8d-8b56-14ea96477094)

> 26.6 % of customers switched to another firm.

### 2. Churn distribution with respect to gender:
> ![Churn distribution wrt Gender](https://github.com/smithjadhav/Telecom-Customer-Churn-Prediction/assets/40405066/ec22c2ed-cc74-4840-86c2-196308a90d7b)

> There is negligible difference in customer percentage/count who chnaged the service provider. Both genders behaved in similar fashion when it comes to migrating to another service provider/firm.`

### 3. Customer Contract distribution:
> ![Customer contract distribution](https://github.com/smithjadhav/Telecom-Customer-Churn-Prediction/assets/40405066/2b7bf67c-7e70-41aa-a8a7-a0d489786290)

> About 75% of customer with Month-to-Month Contract opted to move out as compared to 13% of customrs with One Year Contract and 3% with Two Year Contract

### 4. Payment Methods:
> ![Distribution of Payments methods](https://github.com/smithjadhav/Telecom-Customer-Churn-Prediction/assets/40405066/4f9791f6-f3c6-4f68-b989-0cceb18cdb92)


> Major customers who moved out were having Electronic Check as Payment Method.
> Customers who opted for Credit-Card automatic transfer or Bank Automatic Transfer and Mailed Check as Payment Method were less likely to move out.

### 5. Internet services:

> Several customers choose the Fiber optic service and it's also evident that the customers who use Fiber optic have high churn rate, this might suggest a dissatisfaction with this type of internet service.
> Customers having DSL service are majority in number and have less churn rate compared to Fibre optic service.
![Churn distribution w.r.t Internet services](https://github.com/smithjadhav/Telecom-Customer-Churn-Prediction/assets/40405066/7abaf130-5196-4000-a58d-f6b7efe6dac3)


### 6. Dependent distribution:

> Customers without dependents are more likely to churn.
![Churn distribution w.r.t dependents](https://github.com/smithjadhav/Telecom-Customer-Churn-Prediction/assets/40405066/4538f694-651c-432c-98c8-26aaaca8e733)


### 8. Senior Citizen:

> Most of the senior citizens churn; the number of senior citizens are very less in over all customer base.
![Churn distribution w.r.t Senior Citizen](https://github.com/smithjadhav/Telecom-Customer-Churn-Prediction/assets/40405066/67459caa-ba2f-44e1-bc60-756d3acd93a9)


### 9. Tech support:

> As shown in following chart, customers with no TechSupport are most likely to migrate to another service provider.
![Churn distribution w.r.t Tech support](https://github.com/smithjadhav/Telecom-Customer-Churn-Prediction/assets/40405066/3ea1dba7-ae2c-4f1c-b5f1-8189746da632)




## Machine Learning Model Evaluations and Predictions:
![ML Algorithms](https://github.com/smithjadhav/Telecom-Customer-Churn-Prediction/assets/40405066/7f2a820f-cf17-4458-b50d-602f104c0599)
> Here as We can See We have got a best Accuracy on SVM Model which is around 93.09% Which is the highest followed by Random Forest and Decision Tree.

## Optimizations

We could use Hyperparamete Tuning or Feature enginnering methods to improve the accuracy further.

## Conclusion
Telecom Industry typically have much more data available that could be included in the analysis, like extended customer and transaction data and operational data around network services provided. Also they typically have much larger amounts of churn/non-churn events at their disposal than the ca. 7000 in this case example. A high accuracy is needed to be able to identify promising customer cases where churn can be avoided as, eventually, the customer returns protected need to outweigh the costs of related retention campaigns.

The variables that are affecting are Contract Duration:- Contract duration month-to-month is the second biggest driver of churn Tenure:- High tenure ranks as the strongest factor for not churning and the strongest feature overall


### Feedback

If you have any feedback, please reach out at mr.smiteshjadhav@gmail.com



### 🚀 About Me
#### Hi, I'm Smitesh Jadhav! 👋
I am an AI Enthusiast and  Aspiring Data scientist Who is Driven the World of Data.


[1]: https://github.com/smithjadhav
[2]: https://www.linkedin.com/in/smitesh-jadhav-2030ds


[![github](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/c292abd3f9cc647a7edc0061193f1523e9c05e1f/icons/git.svg)][1]
[![linkedin](https://raw.githubusercontent.com/Pradnya1208/Telecom-Customer-Churn-prediction/9f5c4a255972275ced549ea6e34ef35019166944/icons/iconmonstr-linkedin-5.svg)][2]



