# Determining the success of games to identify a popular product and plan an advertising campaign

## Project Status: Completed

## Project Description

## Prepare the data
- Replace column names (convert to lowercase);
- Convert data to the necessary types. Describe which columns had their data types replaced and why;
- Handle missing values if necessary:
    - Explain why you filled missing values in a certain way or why you did not do it;
    - Describe the reasons that could lead to missing values;
    - Pay attention to the abbreviation 'tbd' in the column with user ratings. Analyze this value separately and describe how to handle it;
- Calculate total sales in all regions and write them into a separate column.

## Conduct exploratory data analysis
- Check how many games were released in different years. Are data for all periods important?
- Analyze how sales have changed by platforms. Select platforms with the highest total sales and plot the distribution by years. How long does it usually take for new platforms to emerge and old ones to disappear?
- Take data for the corresponding relevant period. Define the relevant period based on the previous questions. The key factor is that this data will help build forecasts for the year 2017.
- Do not consider data from previous years.
- Identify leading platforms in sales, those growing or declining. Select several potentially profitable platforms.
- Create a box plot for global game sales by platform. Describe the result.
- Investigate how user and critic reviews affect sales within a popular platform. Build a scatter plot and calculate the correlation between reviews and sales. Formulate conclusions.
- Compare the conclusions with game sales on other platforms.
- Look at the overall distribution of games by genres. What can be said about the most profitable genres? Are there genres with high and low sales?

## Create a user profile for each region
- Define for each region's user (NA, EU, JP):
    - The most popular platforms (top 5). Describe the differences in sales shares.
    - The most popular genres (top 5). Explain the differences.
    - Does the ESRB rating influence sales in a particular region?

## Test hypotheses
- The average user ratings for Xbox One and PC platforms are the same;
- The average user ratings for Action and Sports genres are different.
- Set a threshold alpha value yourself.

## Explain:
- How you formulated the null and alternative hypotheses;
- Which criterion you applied to test the hypotheses and why.
## Skills and Tools  
pandas 
numpy
matplotlib
scipy
seaborn

## Data Description

- Name - game title
- Platform - gaming platform
- YearofRelease - year of release
- Genre - game genre
- NAsales - sales in North America (in millions of copies sold)
- EUsales - sales in Europe (in millions of copies sold)
- JPsales - sales in Japan (in millions of copies sold)
- Othersales - sales in other countries (in millions of copies sold)
- CriticScore - critics' score (maximum of 100)
- UserScore - user score (maximum of 10)
- Rating - rating from the ESRB organization (Entertainment Software Rating Board). This association determines the rating of computer games and assigns them a suitable age category.
- Data for 2016 may be incomplete.

## Conclusion of the Research

In this project, we analyzed the gaming genres and platforms of the "Stream" store. The current dataset had 16,715 records and 11 columns. Some columns contained over 40% missing values. We changed the data types of some columns. In the project, we familiarized ourselves with concepts such as TBD and ESRB. We found outdated data prior to 2014. We determined that PS4 and Xbox One are the best-selling platforms, with PS4 being the most profitable. We found that PS4 and Xbox are popular in the European and North American regions, while the Japanese market prefers handheld devices. Europe and North America make up a large part of the sales market. We found that in these markets, the genres Action, Sports, and Shooter have similar sales, while in the Japanese market Role-Playing, Action, and Misc genres are leading. There are genres that are not popular everywhere, such as Strategy, Puzzle, and Adventure. We determined the impact of the ESRB rating on sales. In North America and Europe, M and E ratings predominate, while in Japan, the UNKNOWN rating is leading, followed by E, and to a lesser extent, Adults Only. The importance of critics is not significant except in cases of strong criticism, in which it does not affect sales. The importance of rating is crucial for European and American users, where it should be without violence or with moderate violence. In contrast, the rating does not have a significant impact on sales for Japanese buyers. We tested hypotheses and concluded that the average user ratings for Xbox One and PS platforms are the same, while the average user ratings for Action and Sports genres are different.
