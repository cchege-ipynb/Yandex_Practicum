## Determine whether a game succeeds or not in  video game advertising campaigns

**This project shows;**
- ability to prepare a dataset for analysis
- ability to build distribution graphs and explain them
- ability to calculate standard deviation and variance
- ability to formulate alternative and null hypotheses
- ability to relevantly apply and test them
- ability to explain the results of the hypothesis tests
- ability to follow the project structure and keep the code neat and comprehensible
- ability to leave clear, relevant comments at each step
- ability to give relevant conclusions

**The project involves:**
- Replacing the column names (make them lowercase).
- Converting the data to the required types.
- Describing the columns where the data types have been changed.
- Dealing with missing values:
    - Explaining the reason for filling in the missing values and not to leave them blank.
    - Exlpaining why the values are missing giving possible reasons.
    - Paying attention to the abbreviation TBD (to be determined) specifying how to handle such cases.
- Calculating the total sales (the sum of sales in all regions) for each game and putting these values in a separate column.
- Looking at how many games were released in different years. Describing the significance of the data for every period.
- Considering the varied sales from platform to platform, then choosing the platforms with the greatest total sales and building a distribution based on data for each year: Finding the platforms that used to be popular but now have zero sales: Getting long it generallytake for new platforms to appear and old ones to fade.
- Determining what period you should take data for using the answers to the previous task. The data should allow one to build a prognosis for 2017.
- Choose the data that is relevant. Disregard the data for previous years.
- Determining the platforms are leading in sales and the ones growing or shrinking. Also selecting several potentially profitable platforms.
- Building a box plot for the global sales of all games, broken down by platform. Explaining the differences in sales significant and average sales on various platforms.
- Looking at how user and professional reviews affect sales for one popular platform, then building a scatter plot as well as calculating the correlation between reviews and sales. Drawing conclusions.
- With the conclusions in mind, comparing the sales of the same games on other platforms.
- Taking a look at the general distribution of games by genre. Decribe the most profitable genres and the genres with high and low sales.
- For each region (NA, EU, JP), determining:
       - The top five platforms. Describe variations in their market shares from region to region.
       - The top five genres and explaining the difference.
       - Whether the ESRB ratings affect sales in individual regions.
- Testing the following hypotheses:
        — Average user ratings of the Xbox One and PC platforms are the same.
        — Average user ratings for the Action and Sports genres are different.
- Setting the alpha threshold value.
- Explaining:
        — The formulation of the null and alternative hypotheses
        — The significance level chosen to test the hypotheses, and why.

## Data description
— *Name\
—  Platform\
—  Year_of_Release\
—  Genre\
—  NA_sales* (North American sales in USD million)\
— *EU_sales* (sales in Europe in USD million)\
— *JP_sales* (sales in Japan in USD million)\
— *Other_sales* (sales in other countries in USD million)\
— *Critic_Score* (maximum of 100)\
— *User_Score* (maximum of 10)\
— *Rating* (ESRB)

## Task
While working for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. There's need to identify patterns that determine whether a game succeeds or not. This will allow one to spot potential big winners and plan advertising campaigns.\
The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.

## Libraries Used
_pandas, numpy, matplotlib, scipy, seaborn_


```python

```
