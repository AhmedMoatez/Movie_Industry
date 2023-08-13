### movies_analysis

This analysis explores the "Movie Industry" dataset sourced from Kaggle: https://www.kaggle.com/datasets/danielgrijalvas/movies.

The dataset was thoroughly investigated to gain insights into various aspects of the movie industry.

#### Data Cleaning and Exploration:
The dataset was assessed for missing values, and missing data was replaced with zeros. Data types were adjusted, and a new 'year_correct' column was created from the 'released' date. The dataset was sorted by 'gross' revenue in descending order for further analysis.

#### Correlation Analysis:
The correlation between numeric features was visualized using a heatmap. Both original numeric features and encoded categorical features were analyzed for their correlations. High correlations (greater than 0.5) were identified and highlighted.

#### Top Grossing Companies:
The dataset was grouped by companies, and the total gross revenue for each company was computed. The top 15 companies by total gross revenue were determined and displayed.

#### Top Grossing Companies Over Years:
Another analysis was conducted by grouping the data based on both companies and release years. The top 15 companies with the highest gross revenue from 2011 to 2019 were identified and presented.

#### Regression Plot:
A regression plot was created to visualize the relationship between 'gross' revenue and 'budget' of movies. The plot provides insights into the general trend between these two variables.

This analysis offers a concise overview of the movie industry dataset, highlighting key findings related to revenue, correlations, and company performance. Further exploratory analysis and insights can be obtained from this dataset for those interested in the movie industry.
