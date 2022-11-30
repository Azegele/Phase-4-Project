# E-COMMERCE RECOMMENDER SYSTEM

## BUSINESS UNDERSTANDING

![image](https://user-images.githubusercontent.com/110466244/204891623-109c27ca-b614-44c0-a982-d29ad348a9d2.png)

### Overview

>Online shopping refers to a delivery and pick-up service. This particular service  is offered by companies through a website and mobile app. The service allows customers to order items from participating retailers with the shopping being done by a personal shopper or company.
>Covid-19 has changed the way the world operates. The ‘new normal’ has also seen dramatic increases in online shopping trends for apparent reasons. Contactless transactions are safer, and lockdowns have given people no choice but to use online platforms to purchase goods. As you know, however, don’t last forever. Still, once a customer has experienced the convenience and safety of an initially obligated online shopping experience, they are very likely to use it again even when they don’t have to.
>Some of the advantages of online shopping include; there are a variety of products, it's covenient, there are a lot of online discounts, there is buyer/shopping secrecy, the customers can avoid crowds, you can find unique/rare products and there is detailed information about the products that you are buying.
>To effect some of these advantages of online shopping a recommendation system or recommendation engine can be used for information filtering where it tries to predict the preferences of a user and provide suggestions based on these preferences.

### Main Ojective

To provide a recommendation system that will help both existing and new customers. Our main of creating a recommendation system is to categorise the customers based on their purchase quantities and set this as our guide in recommending the products based on the size of a business.

### Specific Objectives

1. To particularly provide product recommendations and to look for unique ways to personalize marketing to customer base.

2. To determine the month with the highest sales so as to plan the optimal time to give discounts.

3. To determine the peak hours of the day inorder to better strategize our marketing through online ads.

4. To determine if the unit price affects the quantity demanded


### Data Understanding

Our data set is from UCI MachineLearning Repository. It is from an non-store online shop selling unique gifts.
The Data set collected is from 2010 December to 2011 December.

The data has 8 features;

+ InvoiceNo
+ StockCode
+ Description
+ Quantity
+ nvoiceDate
+ UnitPrice
+ CustomerID
+ Country

### Models Implemented

Collaborative Filtering

We used Cosine Similarity to recommend various
Products to customers.

Memory_Based

We used the SVD model to create our model and
test our data. 

### Evaluation

Accuracy

RMSE

MAE

### Findings

Memory based 

We used Cosine Similarity to recommend various Products to customers.
In our predicition we got an RMSE of 0.0655.

Model based

We used the SVD model to create our model and test our data. Here we got an RMSE of 0.3954

### Recommendations

Our Memory_based model and Model_based model is able to recommend products to customersbased on their similarity

Follow up to find out if the increase in online purchases are due to new customers or repeat customers and if so, explore ways to onboard new customers possibly through convenience, efficiency and reviews to improve their trust.

Follow up on third party resellers that have received scam claims and action taken if found guilty.

### Coclusion
The recommendation system we developed will be very helpful to the customers and e-commerce companies to recommend products based on experience with the products.

### Author and Aknowledgement:

Special thanks to our Moringa School Data science Techincal Mentors for their guidance throughout the process of our project and the amazing Elites team members :point_down:

* [Bradley Azegele](https://github.com/Azegele)
* [Daniel Kimutai](https://github.com/danielkimutai)
* [Grace Anyango](https://github.com/GraceA2022)
* [Julia Karanja](https://github.com/juliakaranja)
* [Phelma Kandie](https://github.com/kandy372)






