# Analysis of Factors Correlated to Gross Earnings of Movies
This project aims to identify factors that correlate with the gross earnings of movies using Python. The project includes data cleaning, exploratory data analysis, and regression analysis using libraries such as pandas, matplotlib, and seaborn. The insights gained from this project can inform decision-making in the film industry.

The hypothesis I would like to test is that the following three factors would have a high correlation with gross earnings:

&#x2610; Budget has a high correlation with gross earnings.

&#x2610; Score has a high correlation with gross earnings.

&#x2610; Genre has a high correlation with gross earnings.

# First Findings 
Based on the initial analysis of the correlation scatterplot, it was found that only two categories, budget and votes, showed a correlation score greater than 0.5.

It appears that the hypothesis regarding the correlation between budget and gross earnings holds true with a strong correlation coefficient of 0.74. Additionally, it was found that votes also have a moderate correlation with gross earnings with a correlation coefficient of 0.61. This suggests that the amount of money invested in a movie and the number of votes it receives can significantly impact its gross earnings. 

# Second Findings 
In the second analysis, all factors, including genre, company, and director, which were assigned random numbers from words, were included. The analysis revealed a strong positive correlation between gross earnings and the writer (0.78), director (0.69), and company (0.64) factors. The year factor was excluded from the analysis due to the significant impact of inflation on the results — and the movie name was also excluded due to outliers.

However, the correlation between genre and gross earnings was only 0.19, indicating that movie genre does not have a direct correlation with gross earnings.

# Conculsion
:white_check_mark: Budget has a high correlation with gross earnings.

:x: Score has a high correlation with gross earnings.

:x: Genre has a high correlation with gross earnings.



