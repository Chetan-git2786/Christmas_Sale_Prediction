## Data Analysis on the Christmas Sale Prediction Dataset

**Details about the project** :

This project was done with the objective to predict whether the store remains to be opened/closed on the eve of current year Christmas Sale based on the profit/Loss to be incurred by the store owners. With the availability of the data pertaining to the previous years Transactions ,we could predict whether we could gain profit or loss by using the python libraries .

![enter image description here](https://github.com/Chetan-git2786/Christmas_Sale_Prediction/blob/main/Christmas_Sale.jpg?raw=true)![enter image description here](https://github.com/Chetan-git2786/Christmas_Sale_Prediction/blob/main/Christmas_Sale_pic6.jpg?raw=true)
![enter image description here](https://github.com/Chetan-git2786/Christmas_Sale_Prediction/blob/main/Christmas_Sale_pic17.jpg?raw=true)

   The dataset has the previous year's information w.r.t  several fields such as Product Category, Sale price, Purchase price, Count, Product In-Stock by EOD
![enter image description here](https://github.com/Chetan-git2786/Christmas_Sale_Prediction/blob/main/Christmas_Sale_pic15.jpg?raw=true)
**Python Libraries Used :**
In this project, the python code was written by making use of the Python Libraries like Numpy, Pandas, Matplot lib to load the data & derive the insights in the form of a visualization based on category wise sales on various dates during the past Christmas Season.

Also, did some kind of feature engineering using the python libraries by adding few columns like "Revenue" ,"Total Cost Price" &  "Profit"  to the existing features and calculated its corresponding values from the existing features, as a result of which we could harness the information and arrived at gaining required insights.

**Insight from Visualization:** 
     The information related to the category wise sales summary was plotted using matplotlib through which it has been figured out that the sales for few categories have dropped down.
      
**Insight from Feature Engineering :** 
              While performing the feature engineering and feature extraction by adding few columns like "Revenue" ,"Total Cost Price" &  "Profit" and populating the category wise data(i.e., achieved by sub setting), subsequently it has been found that the "Revenue", "Total cost" and "profits" for the categories like "Education & Construction Toys", "Vehicles, Tracksets & Remote Control Toys","Collectibles & Toy Guns" is zero. 
![enter image description here](https://github.com/Chetan-git2786/Christmas_Sale_Prediction/blob/main/Christmas_Sale_pic13.jpg?raw=true)
  **Valuable Insight :**
              Upon keen verification of the records on various dates for the above mentioned categories, it has been found that the "Total cost" "profits", "revenues" were zero, because of the reason that the column "count " has been reflected with zero values. The main reason or the underlying fact for this to happen is that these products went out of stock on those days or the previous day

**Below is the action taken to overcome the problem** : 
    By Filtering the data under each category for the days with sales (i.e., when items were in stock) we could calculate the average profits for that particular category. By extracting the no. of days without sales(i.e., the items were out of stock) and make a prediction: how much profit we can generate if we will have those categories in stock, we could conclude whether to keep the shop open or close. 

**Conclusion :** 
As the profit remained high i.e., 7.9 million compared to the benchmark profit figure of 5.7 million we can keep the shop open.

To check out the notebook, please click [here](https://github.com/Chetan-git2786/Christmas_Sale_Prediction/blob/main/Christmas_Sale_Prediction.ipynb)
![enter image description here](https://github.com/Chetan-git2786/Christmas_Sale_Prediction/blob/main/Christmas_Sale_pic16.jpg?raw=true)
