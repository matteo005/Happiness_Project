# Project 1: "What makes for a HAPPY country!"

# **Navigating Enkhsanaa's Notebook:** 

## Questions: 
Does higher GDP(Gross Domestic Product) correlate to higher happiness index in countries?
    - How to find out the relationshipns? 
    - Is there even relationship exist there? 
    - What approach should be taken? 

## Data: 
1. Collected data from: 
Kaggle's World Happiness Report 2015-2021 - [Kaggle](https://www.kaggle.com/mathurinache/world-happiness-report-20152021)
2. Extracted data and cleaned for analysis.
3. Created some visualization to understand and to grasp general picture about data by different variables, criteria, and time. 
        <img width="437" alt="Screenshot 2021-05-24 135358" src="https://user-images.githubusercontent.com/67448948/119387939-a3da2c00-bc97-11eb-9fc9-a861ce5ae4dc.png">
3. Develop Ho (null hypothesis) and Ha (alternative hypothesis)
      Ho: Higher GDP and Higher Happiness index do
4. Calculated data that is associated  with happiness index and GDP in different countries and regions to answer questions were asked. 
5. Final results of study. 

## Tools: 
 - Git Bash
 - github
 - Python
 - pandas
 - matplotlib
 
## General Conclusions


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


## Data: 


## Tools: 


## General Conclusions
