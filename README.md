# EDA ANALYSIS OF UNICORN COMPANIES
 Unicorn Companies Analysis
Our Data set was a CSV file which contained informations of companies that had reached unicorn status by Valuation.
A unicorn status is met when your valuation exceeds 1 Billion $.
The goal was to analyse this data set to reveal important informations that  about the companies, the industry they operate in, and also help in the decision making of any selected investor that want to invest in a company with the aim of that company achieving unicorn status.

The steps i took as are follows:

- First i needed to import the necessary libaries
- need to then import my date files
- get a view of how my data looks like and the data types of my columns
- rename some columns which had spaces in them, to make it easier for me
- check if there is any missing data , and there was missing data in city and investors, but i had  no need to remove the missing datas because it will have no huge impact in the results i get
-checked if there were non numerical values in both my Funding and Valuation column, and i observed there was unknown values in the funding column, since the data type of my funding column was an object, i needed to replace the unknown with NaN, because i will be converting the funding column to a float datayype for calculation purposes

i also converted the valuation column from an object data type to float

- I encountered some problems next when i wanted to replace the  string B and M in the funding column, i did not want to add numerous zeros  when the string B and M are replaced, i wanted to majorly convert the figures in millions to billions, which would make the figures in millions to be come decimals, i do hope to  find a way to solve that.

- i also encountered some problems when i was plotting my scatter plot, i wanted more figures to show in the ylabel and x label so that the plot can be easily read, i made no headway and i hope to find a way to solve that.

-i also split my investors to a list and then exploded it so  later on when i needd to find the investors who funded the most unicorn

-i then went further to visualize the relationship using bivariate, univariate and multivate analysis and come up with  my personal opinions
