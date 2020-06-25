# starbucks_offer_analysis

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Conclusion](#conclusion)

## Installation <a name="installation"></a>

Please make sure that progressbar2 library is installed on your system prior using the notebook. There are also several libraries that i used here that should be installed if you are install Python from Anaconda Distribution.

## Project Motivation<a name="motivation"></a>
In this project, I want to apply my knowledge as Data Scientist to explore and gain insight from Starbucks offer data. I cleaned and analyzed the data. I am using Matplotlib to visualize findings. To fill missing values, i am using fillna and fill them with zeroes.

Last, I used support vector machine to predict which tye of offer is better to give to the customer.

## Conclusion<a name="conclusion"></a>

I have provided the notebook here in the repository. Comment "savefig" if you do not want to save generated plot.

Result summary:
1. The given data has been explored and analyzed. Some insight have been found:
2. The best offer type is discount. Discounted product brings highest ads conversion.
3. Male customer count is higher than female ones. It looks like that male customer drinks coffee much more than female customer.
4. There is no difference between female and male customer in registration year. Starbucks should target customer who registered their account in between 2016 and 2017.
5. The customer between 50 and 60 years old is more likely to be influenced by offer. The female customer age distribution is peaked at around 60’s while the male customer is at 50’s. Starbucks should focus their offer to younger male and older female for better ads conversion.
Starbucks male customer who make transaction after seeing the offer has lower average earnings compared to the female customer. Male customer has average earnings around $60k and has higher count in earnings range between $30k and $75k. On the other side, count is higher for female customer with earning between $5k and $120k.
6. We have built machine learning model to help company to predict what is the best offer to give to their customer. This prediction will help Starbucks to improve their offer to transaction conversion rate. 

You can find detailed finding on my blog post on [Medium](https://medium.com/@satriowputra/starbucks-offer-analysis-466f53443514?sk=c40d157628b5f43d93d913e0b8ecfe6b).
