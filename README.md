# customer-segmentation-python:
This project applies customer segmentation to the customer data from a company Ulabox and derives conclusions and data driven ideas based on it.

### About Ulabox:
Ulabox is the most successful pure-player online grocery in Spain. It picks up more than €1 million in monthly revenue and asserts a customer satisfaction above 95%.

### Dataset
File: [customer_segmentation_2.csv]
GitHub : [https://github.com/ulabox/datasets/tree/master/data]

__customer_segmentation_2.csv__ dataset includes a subset of anonymized __30k orders__ from the beginning of 2017. All kind of customers (around 10k) are represented in this dataset: from urban and rural areas, from first-timers to loyal customers.
And __customer_segmentation_final_datasets.csv__ file is the final dataset after modified the customer_segmentation_2 dataset

#### Data dictionary
The dataset contains 30k samples with the following features:

* __customer__: Anonymized customer's id.
* __order__: Order id, starting from zero.
* __total_items__ : The number of items purchased in the order.
* __discount%__ : The percent of total discount received. For instance, if the customer saves €20 in a €100 order (that is, he had to pay €80), this field will contain a 20.
* __weekday__ : Day of the week when the order was paid. 1=Monday, 7=Sunday.
* __hour__ : The hour of the day the purchase was done. From 00 to 23.
* __Categories' partials__ : Percent of money spent in each of the 8 website's main categories:
  * __Food%__ : Non perishable food, for example: rice, cooking oil, snacks, cookies, sauces, canned food.
  * __Fresh%__ : Fresh and frozen food, for example: fresh tuna, fruits, frozen pizza, salads, meat.
  * __Drinks%__ : All kind of beverages, like: water, juices, wine, alcoholic drinks, milk, soy drinks.
  * __Home%__ : Products for home, from toilet paper to small appliances.
  * __Beauty%__ : Items for cleaning your body and makeup; for example: shampoo, shaving foam, cosmetics.
  * __Health%__ : Medicinal solutions that can be sold in Spain without medic prescription: diet pills, condoms, tooth paste.
  * __Baby%__ : Useful articles if you have a baby: diapers, baby food, baby care.
  * __Pets%__ : Items related with dogs, cats and other pets; like food, toys, sanitary sand.

        
### Customer segmentation
In customer segmentation we categorize similar customers together in the same cluster and analyse them. It can reveal information like: 
1) who are the most valuable customers of the company 
2) what kinds of customers does the company have
3) This can be used for targeted marketing and other marketing strategies.
4) Sometimes it can even reveal a potential white space in the market place which no company has yet occupied.
Well we can get creative here.

### Clustering
Clustering is a process in which we put similar data points into the same cluster. There are a lot of algorithms to do this, for example agglomerative heirarchical clustering, kmeans clustering, Gaussian Mixture Model etc. We segmente the data with the help of __Kmeans Clustering__.


__Thank you for your time :)__
