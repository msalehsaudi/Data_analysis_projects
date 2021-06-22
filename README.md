<img src="1.jpg">

#                             <span style="color:blue"> Loan Data exploration</span>
*by: Mohammad Hosameldin Taha Mohamed Saleh*



 I have chosen  the Loan dataset from a bank to investigate it, since it is more pragmatic real life example to learn from.

#                             <span style="color:blue"> Findings from Exploratory data analysis</span> 

 - Main features affecting bank loan outcomes.
 - We can use the findings to get an global equation (through linear regression) to deduce the outcome of future loans.
 - Usage of two systems in the bank for assesing outcomes, one was used before 2009, and one after 2009.



## <span style="color:blue"> Steps taken during this investigation:</span>

### Step 1: Data wrangling

 - We explore the data set to check where the values are changing or missing, so we can extract different datasets depending on our requirements.
 - We specify our questions that we need to investigate.
 - Remove the unneeded data from the dataframe to reduce the noise.
 - Adjusting dates columns from object to a unified date format.
 - For object type columns we sort them into ordered categorical data.
 - We simplify the loan status into a more simplified loan_asses column where the variables are only 3 instead of 10 variables.
 
### Step 2: Data exploration

 - Checking through univariate data exploration any irregularities in the data, or observing the different trends so we can adjust accordingly.
 - Through our exploration we find out that the bank changed their system to asses and issue loans, specifically before 2009 and after 2009.
 - we study only after 2009 in this dataset.
 - For tackling the question of knowing the factors affecting certain features in our report, I have made a function to get the most non related features that affect the feature in question. ( it is absolute correlation, since it doesn't matter if it is directly or inversly propotional) 
 - Plotting univariate, bivariate, and multivariate graphs for our exploration process is very helpful to demonstrate hidden and unthought of relations.
 
 
### Step 3: Data explanation

 - Making part 2 file to feature the main scope of our study for the reader since, they are not concerned about the exploration graphs as much as conclusion graphs needed to read.
 - Making a slide show file for a better presentation.
 - Hiding all codes for a neat presentation.



## <span style="color:blue"> Websites and resources used in this dataset:</span>

 - https://www.udacity.com
 - https://stackoverflow.com
 - https://pandas.pydata.org 
 - https://www.datacamp.com
 - https://www.geeksforgeeks.org


```python

```
