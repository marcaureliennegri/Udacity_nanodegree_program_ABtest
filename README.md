# AB test

Project: Helping an online company to decide whether they should launch their new page or no.
A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of this kind of experiment due to its frequency of use.

For this project, you will be working to understand the results of an A/B test run by an e-commerce website. Your goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Within the framework this project, we tried to understand whether the company should implement a new page or keep the old page with following:

**Probability based approach:**
* A/B test
* Regression approach
* Requirements
* Python 3.6 (or higher)
* matplotlib 2.1 (or higher)
* numpy 1.10 (or higher)
* pandas 0.20 (or higher)
* statsmodels 0.8.0

**Probability based approach:**
We will try to find probability of an individual receiving the new page or an old page and what are the chances of those.
A/B test:
* In A/B test we set up our hypothesis to test if new page results in better conversion or not
* We will simulate our user groups with respect to conversions
* We will find the the p_value
* We will also use an alternative approach to validate / double check our results and decide whether to reject the null hypothesis
Regression Approach:
* We shall look at exploring two possible outcomes. Whether new page is better or not.
* By further adding geographic location of the users, we will attempt to find if any specific country had an impact on conversion

**Sources:**

https://softwareengineering.stackexchange.com/questions/254475/how-do-i-move-away-from-the-for-loop-school-of-thought

http://www.statsmodels.org/dev/generated/statsmodels.stats.proportion.proportions_ztest.html

https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.join.html

http://knowledgetack.com/python/statsmodels/proportions_ztest/

https://stackoverflow.com/questions/45923738/replace-column-value-based-on-value-in-other-column-for-all-rows-in-a-pandas-da
