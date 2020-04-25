
## **Project Report**
 

 **Extract**

I found a dataset on Kaggle called, “The World Happiness Report,” that ranks each country by their “Happiness Score” and contains the factors that effect this score (https://www.kaggle.com/unsdsn/world-happiness#2015.csv). I used 5 CSV files, one dataset for each year from 2015 to 2019.

**Transform**

First, I renamed the column titles in order to make everything lower case, get rid of spaces, and ensure they were consistent throughout each dataset. I wanted to focus on only a few of the factors that make up the Happiness Score. Therefore, I got rid of the columns that I did not want to see and were left with 6 columns that are common throughout each dataset; Country, Happiness Rank, Happiness Score, Government Trust, Healthy Life Expectancy, and Freedom.

**Load**

Once the data was clean, I connected to the engine, loaded to SQL, and created 5 tables, showing the 5 happiest countries per year from 2015 – 2019.


