
## **Project Report**
 

 **Extract**

I found a dataset on Kaggle called, “The World Happiness Report,” that ranks each country by their “Happiness Score” and contains the factors that effect this score (https://www.kaggle.com/unsdsn/world-happiness#2015.csv). I used 5 CSV files, one dataset for each year from 2015 to 2019.

**Transform**

First, I renamed the column titles in order to make everything lower case, get rid of spaces, and ensure they were consistent throughout each dataset. I wanted to focus on only a few of the factors that make up the Happiness Score. Therefore, I got rid of the columns that I did not want to see and were left with 6 columns that are common throughout each dataset; Country, Happiness Rank, Happiness Score, Government Trust, Healthy Life Expectancy, and Freedom.

**Load**

Once the data was clean, I connected to the engine, loaded to SQL, and created 5 tables, showing the 5 happiest countries per year from 2015 – 2019.



---

---
* More about the Dataset
---
---

* The World Happiness Report is a landmark survey of the state of global happiness. The first report was published in 2012, the second in 2013, the third in 2015, and the fourth in the 2016 Update. The World Happiness 2017, which ranks 155 countries by their happiness levels, was released at the United Nations at an event celebrating International Day of Happiness on March 20th. The report continues to gain global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. Leading experts across fields – economics, psychology, survey analysis, national statistics, health, public policy and more – describe how measurements of well-being can be used effectively to assess the progress of nations. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness.
* The happiness scores and rankings use data from the Gallup World Poll. The scores are based on answers to the main life evaluation question asked in the poll. This question, known as the Cantril ladder, asks respondents to think of a ladder with the best possible life for them being a 10 and the worst possible life being a 0 and to rate their own current lives on that scale. The scores are from nationally representative samples for the years 2013-2016 and use the Gallup weights to make the estimates representative. The columns following the happiness score estimate the extent to which each of six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity – contribute to making life evaluations higher in each country than they are in Dystopia, a hypothetical country that has values equal to the world’s lowest national averages for each of the six factors. They have no impact on the total score reported for each country, but they do explain why some countries rank higher than others.
*  Inspiration - What countries or regions rank the highest in overall happiness and each of the six factors contributing to happiness? How did country ranks or scores change between the 2015 and 2016 as well as the 2016 and 2017 reports? Did any country experience a significant increase or decrease in happiness?






