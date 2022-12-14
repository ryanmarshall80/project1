# What makes people in countries around the world happy?
Project 1 EDA Analysis for Group 2:
What makes people in countries around the world happy?


## Project Overview

People around the world seem more interested than ever in living not only successful lives, but happy ones as well. With this in mind, we wanted to determine which factors contribute to living a happy life. We started by investigating a few factors we believe may correlate to how happy a country’s citizens are. These factors are obesity, economy, internet usage, and alcohol consumption. 

## Project Structure

For this project, we used a dataset that has a calculated Happiness Score of 157 counties. We then found datasets for obesity, economy, internet usage, and alcohol consumption to determine if there is a correlation between each factor and the happiness level of each country. 

Our final code can be found in ryanmarshall80/project1.

Lastly, we created a powerpoint to present our findings to the class. 

## Project Contributors

- Annalyse Bergman
- Elamathi Elangovan
- Joshua Samuel
- Meena Rai
- Ryan Marshall

## Objective

Analyze data to determine if there is a correlation between happiness and obesity, economy, internet usage, and alcohol consumption. Other analyses will be done in relation to happiness and the datasets we have acquired. Determine implications for research. 

## Hypothesis

- H0: There is no correlation between obesity and happiness.
- HA1: There is a negative correlation between obesity and happiness.
- HA2: There is a positive correlation between obesity and happiness.

## Methodology

We first acquired our Happiness dataset and a dataset for each factor (Obesity, Economy, Internet Usage, and Alcohol Consumption) from resources such as Kaggle, WHO, and the World Bank. Using Jupyter, we then cleaned and merged datasets creating new data frames. With these data frames, we created scatterplots for each pair. On each scatter plot, we ran a linear regression model to determine if there was a correlation between the two factors. We also created a correlation matrix for further analysis. 

## Result 1: Obesity

Our analysis shows there is a moderate positive correlation between obesity and happiness. The r-value is 0.57.

![](Images/happiness_vs_obesity.png)

Based on our analysis, the null hypothesis can be rejected. The results show that there is a positive correlation, so the second alternative hypothesis is correct. The first alternative hypothesis can also be rejected. 

We also charted obesity vs. happiness of the top 5 happiest countries and the bottom 5 happiest countries. 

![](Images/obe_country_f.png)

![](Images/obe_country_l.png)

## Result 2: Economy

Our analysis shows there is a strong positive correlation between economy and happiness. The r-value is 0.78. 

![](Images/happiness_vs_economy.png)

We also charted economy vs. happiness in the top 5 and bottom 5 countries.

![](Images/gdp_country_f.png)

![](Images/gdp_country_l.png)

## Result 3: Internet Usage

Our analysis shows there is a strong positive correlation between internet usage and happiness. The r-value is 0.8.

![](Images/happiness_vs_internet.png)

We also charted internet usage vs. happiness in the top 5 and bottom 5 countries.

![](Images/int_country_f.png)

![](Images/int_country_l.png)

## Result 4: Alcohol Consumption

Our analysis shows there is a weak positive correlation between alcohol consumption and happiness. The r-value is 0.34. 

![](Images/happiness_vs_alcohol.png)

We also charted alcohol consumption vs. happiness in the top 5 and bottom 5 countries. 

![](Images/alc_country_f.png)

![](Images/alc_country_l.png)

## Other Analysis

While we were completing our analysis, we thought it would also be interesting to see how happiness has changed over time in select countries. We found that countries that are more stable have a higher and more stable happiness level.

![](Images/Happiness_Change_over_Time.png)

We also created a heat map to see the distribution of Happinees throughout the world.


![](Images/Happy_heat_map.png) 




Finally, we did an analysis on suicide rates compared to happiness levels. We determined that suicide rate are not correlated to happiness scores of each country, and they appear to be consistent throughout the regions of the world.

![](figure_9.png)

![](figure_10.png)

## Conclusion

Through our analysis, we determined there is a strong correlation between the economy and internet usage with happiness. We can contribute this to people being in a more stable environment and having more money allows them to have a higher happiness level. We also saw there is a high correlation between the economy and internet usage itself. This makes sense when considering the cost of having wide spread internet in a country and individual access. 

Obesity also has a positive correlation with happiness, but it is not as strong a connection as the economy or internet usage. However, there is a strong correlation between obesity and the economy. We believe this is because people living in a higher economy have more access to food and a sedentary lifestyle, contributing to high obesity levels. 

Alcohol has the lowest correlation with happiness than the other factors. It also has very low correlation between all other factors as well. This can be contributed to the many personal, social, and cultural reasons people drink. 

Below is a correlation matrix between all factors that were analyzed. 

![](Images/figure_5.png)

## Limitations

The data we used is from 2015 and only 157 countries were used in the analysis. 

## Future Exploratory Analysis

Future analysis can be done on what other factors contribute to happiness. Research shows that genes, life circumstances, and intentional activities all play apart in what makes a person happy. If analysis can narrow down what makes a person more happy, we can apply that knowledge to help raise happiness levels around the world. 

## References

https://www.kaggle.com/datasets/mathurinache/world-happiness-report?select=2020.csv

https://ourworldindata.org/alcohol-consumption

https://www.who.int/data/gho/data/indicators/indicator-details/GHO/prevalence-of-obesity-among-adults-bmi-=-30-(age-standardized-estimate)-(-) 

(https://www.kaggle.com/datasets/mathurinache/world-happiness-report?select=2020.csv)

https://databank.worldbank.org/ 

https://www.edbatista.com/2017/12/understanding-the-pie-chart-in-the-how-of-happiness.html

https://greatergood.berkeley.edu/article/item/genetics_of_happiness

