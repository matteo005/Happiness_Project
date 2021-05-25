# Project 1: "What makes for a HAPPY country!"

# **Navigating Enkhsanaa's Notebook:** 

## Questions: 
One of defining factor of happiness index is GDP (Gross Domestic Product) of the country, and this section aims to investigate that is correlation exist between GPD and Happiness index.  
1. Does higher GDP correlate to higher happiness index in countries?
In order to answer this question, the following questions were asked and followed up accordingly.
    1.a) How to find out the relationships between two variables? (Develop hypothesis and investigate further)
    1.b) Is there even relationship exist between these two variables? (do statistical test against hypothesis to find out the realrion exist within these two variables)
    1.c) How to tackle the problem and what approach should be taken to answer this question? (Explore data, do calculation, and create related visualization based on data to illustrate the relations. Finally, show the result of such a relation exist or not exist between GDP and Happiness index)
## Data: 
1. Collected data from: 
Kaggle's World Happiness Report 2015-2021 - [Kaggle](https://www.kaggle.com/mathurinache/world-happiness-report-20152021)
2. Extracted data and cleaned for analysis.
3. Created some visualization to understand and to grasp general picture about data by different variables, criteria, and time. 
        <img width="437" alt="Screenshot 2021-05-24 135358" src="https://user-images.githubusercontent.com/67448948/119387939-a3da2c00-bc97-11eb-9fc9-a861ce5ae4dc.png"> 
       <img width="468" alt="Screenshot 2021-05-24 142007" src="https://user-images.githubusercontent.com/67448948/119392354-a2abfd80-bc9d-11eb-8f87-823329d37007.png">
       <img width="692" alt="Screenshot 2021-05-24 142714" src="https://user-images.githubusercontent.com/67448948/119392466-c96a3400-bc9d-11eb-920b-643385759f46.png">
4. Develop Ho (null hypothesis) and Ha (alternative hypothesis) to test existence of relationship. 
    Ho: Relationship does not exist between higher GDP and higher Happiness index. 
    Ha: Relationship exist between higher GDP and higher Happiness index. 
    
5. Calculated data that is associated  with happiness index and GDP in different countries and regions.
    Tested hypothesis by using ANOVA Test. 
     ![image](https://user-images.githubusercontent.com/67448948/119391835-e05c5680-bc9c-11eb-9da4-f472e95e4d17.png)
 determined p_value to test against null hypothesis.
 (statistic=56.670624249813926, pvalue=1.1367658484570351e-27)
 Test result shown below rejects null hypothesis; therefore, it supports Ha. 
   0 < (p_value pvalue = 1.1367658484570351e-27) << 0.05 
6. Produced scatter plot for mean of happiness by each country and did linear regression analysis.

    <img width="827" alt="Screenshot 2021-05-24 145010" src="https://user-images.githubusercontent.com/67448948/119393927-9a54c200-bc9f-11eb-8494-143d7e43d241.png">
7. Calculated pearson r value to define existence of relationship. 
    Pearson r value is 
    0 < (pearson_r_value =  5.524167874543727e-35) << 0.03 
    Relation exist positively weak. 
    Also, linear regression slope is: 
        0 < (m = 0.02) << 1
    This shows that positive very weak reltion exist between GDP and happiness index. 
8. Final results of study. 
 Weak and postitive relation exist between these two variables, and this claim is supported by p_value of ANOVA test result, pearson r value, and slope of linear regression. 
    

## Tools: 
 - Git Bash
 - github
 - Python
 - pandas
 - matplotlib
 - Scipy
 - Numpy
 
## General Conclusions 
 Original intuitive assumption was that Higher GDP will have a higher impact on Higher Happiness index in countries. However, the study results shows that relationship between these two variables are suprrisingly weak. Final conclusion ism GDP correaltes to Happiness index positively and weakly. 

# **Navigating Matteo's Notebook:**

## Questions: 
Does higher generosity correlate to happier countries? 

## Data: 
Kaggle's World Happiness Report 2015-2021 - [Kaggle](https://www.kaggle.com/mathurinache/world-happiness-report-20152021)

## File explanation:
1. MB_Data_Code.ipynb is the initial data cleaning notebook which takes raw input and filtered to selected nation and year. Outputs cleaned data.
2. MB_Analysis_Code.ipynb is the figure generating notebook which takes the cleaned files and generates figures to answer the above questions.
NOTE: Both files assume that the input and output csv file path is located within a data folder at the same level of the notebook. Location of the data folder was moved post merge with the master branch.

## Tools: 
* All data wrangling done using pandas and numpy.
* Figures built using matplotlib and seaborn.

## General Conclusions


# **Navigating Tamara's Notebook:** 

## Questions: 
Is there anything that proves that certain regions have happier countries?

## Data: 
Kaggle's World Happiness Report 2015-2021 - [Kaggle](https://www.kaggle.com/mathurinache/world-happiness-report-20152021)

## Tools: 
* Figures built using matplotlib
* Pandas using groupby

## General Conclusions
We can visually see by the line graph that there are certain regions in the world that have happier countries

# **Navigating Samson's Notebook:** 

## Questions: Are countries under more corruption less happy?


## Data: 
Kaggle's World Happiness Report 2015-2021 - [Kaggle](https://www.kaggle.com/mathurinache/world-happiness-report-20152021)

![image](https://user-images.githubusercontent.com/39179454/119251243-b0656400-bb73-11eb-85dc-c75af4913c91.png)
![image](https://user-images.githubusercontent.com/39179454/119251249-b8250880-bb73-11eb-9518-20ec3f2a9aaf.png)
![image](https://user-images.githubusercontent.com/39179454/119251256-c07d4380-bb73-11eb-8786-40fea55a43d6.png)

## Tools: 
Pandas
Numpy
Matpotlib
Scipy

## General Conclusions
If we look at corruption vs happiness in 2019 we can see that countries actually do get happier as corruption increases. However, this is inverted starting the next year in 2020. There are many reasons why the data could have changed but a major factor that comes into play is Covid-19. If we look at the year 2019 we can say that the citizens of the country don't care about government intervention which explains why the data is low with medium happiness. However, once the pandemic hit the populace would now turn to the government for assistance in paying bills or providing for their families. If they find that the government is lacking in providing adequit support the populace can find that there is corruption within the government. 

Looking at the figure of average corruption and average happiness we can see its similar to years 2019 and below. There is a very slight correlation in corruption affecting happiness but it is not significant. This can also be seen when taking a Ttest which results in a pvalue of 4.6358552763512926e-95. The value is below pvalue of .05 so we reject the null.

![image](https://user-images.githubusercontent.com/39179454/119251521-f242da00-bb74-11eb-9041-8b593d5dbd43.png)

Freedom = Ttest_indResult(statistic=-20.06094743182062, pvalue=2.781555284424539e-44)

![image](https://user-images.githubusercontent.com/39179454/119251557-21594b80-bb75-11eb-81d1-f636e869ef37.png)

Generosity = Ttest_indResult(statistic=9.278119830516218, pvalue=1.431385473016657e-16)

![image](https://user-images.githubusercontent.com/39179454/119251543-11da0280-bb75-11eb-8bfb-de7e896cbed9.png)

GDP = Ttest_indResult(statistic=-19.48635233084674, pvalue=2.785782607905848e-41)

I also did further analysis in the relationship between corruption and freedom, generosity, and gdp. Looking at each of the independant values from the graph, we can see that there is a larger concetration of clusters in gdp which tells us that of all the values there is a higher correlation between correlation and gdp. The pvalues for each individual t-test also support the data.


# **Navigating Andy's Notebook:** 

## Questions:
Do countries who have more freedom live happier lives?

## Hypothesis
Null hypothesis: Happiness has no correlation to freedom of people within different countries from 2015-2016
Alternative hypothesis: an increase of people’s freedom has a positive impact to their happiness within different countries from 2015-2021. 

## Data: 

1. Data Collection Source: 
Kaggle's World Happiness Report 2015-2021 - [Kaggle](https://www.kaggle.com/mathurinache/world-happiness-report-20152021)

Scatterplots of Freedom vs Happiness were graphed over the years of 2015-2021. Results were as followed:

Freedom vs happiness 2015
Line regression value y = 0.07x+ 0.06
T Test value 1.49e-91

Freedom vs happiness 2016
Line regression value y= 0.06x+0.03
T Test value 1.49e-91

Freedom vs happiness 2017
Line regression value y= 0.07x+0.04
T Test value 1.49e-91

Freedom vs happiness 2018
Line regression value y= 0.07x+ 0.06
T Test value 1.49e-91

Freedom vs happiness 2019
Line regression value y= 0.07x+0.02
T Test value 1.49 e-91

Freedom vs happiness 2020
Line regression value y= 0.06x+0.45
T Test value 9.25e-94

Freedom vs happiness 2021
Line regression value y= 0.06x+0.44
T Test value 9.25e-94

## Tools: 
Pandas
Numpy
Matpotlib
Scipy

## General Conclusions

All scatter plot graphs shows a positive slope with an average of 0.066 and with an average y-int of 0.16.  Since the average P-value of 1.07e-91  was smaller than .05, it is concluded that there is no significant relationship between freedom and happiness.

The hypothesis was stated: An increase of people’s freedom has a positive impact to their happiness within different countries from 2015-2021 could not be supported. After veiwing the results, there is no supporting evidence to prove the correlation hypothesis. 

The only significant findings of the data and visualizations presented were the higher y-intercept values from the scatterplots of years 2020 and 2021. While the average y-intcept values of graphs dating 2015-2019 were ((0.06+ 0.03+ 0.04+ 0.06, 0.02)/5 = 0.04, the average values of graphs 2020 and 2021 yeileded an average y-intercept value of 0.45. there was a 10-fold increase in average freedom values from 2020 and 2021. This could be due to global changes such as the 2019 pandemic. Even though the freedom rating went up, there wasnt much of a shift in happiness values. 
