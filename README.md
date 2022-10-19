# NYC Bike Counts Retrospective Analysis

For this assignment, you’ll perform a retrospective analysis on the linear regression analysis that you previously performed on the NYC Bike Counts dataset. Specifically, you'll analyze your linear regression analysis to identify anything that you could have done differently.

Instructions


Choose one of the following questions (which concern what affects the number of bikes crossing the Brooklyn Bridge):


Does the amount of precipitation affect the number of bike trips across the Brooklyn Bridge?
Hint: If you choose this question, you'll later need to change the type of the values in the “Precipitation” column to int64. And before you do that, you'll need to replace the non-numeric character values of "T" and "0.47 (S)" with numbers as objects by using the following code:
df[column].replace({"T": "0", "0.47 (S)": "0.47"}, inplace=True)


Does a high temperature affect the number of bike trips across the Brooklyn Bridge?




Formulate a null and an alternative hypothesis for your chosen question.


Use the steps that you’ve learned to guide you in performing qualitative and quantitative analyses.


Use your knowledge of linear regression models to test the null hypothesis.


Identify whether you reject the null hypothesis and provide a short summary.
