# Capstone-Project

Alton Franklin
Capstone Assignment

An overview of the question to be solved in the capstone.
Breakout Trading
For my capstone project, I am choosing to identify a problem within Day Trading called Breakout Trading. During strong trending days, early momentum often pushes stocks to the prior day's high. 
The problem is avoiding false breakouts (fake outs) that trigger stop losses. 
A stop-loss is an automated risk-management order placed with a broker to close out a trade when the price hits a specific, predetermined level. It acts as a financial safety net, capping maximum risk and removing emotion from the exit strategy.
When you enter a trade, you determine the maximum amount of money you are willing to lose. If the market moves against you and reaches your designated stop price, the stop-loss triggers and automatically executes a market order to sell (or buy, if you are shorting) the asset.
For example:
•	You buy stock shares at $100.
•	To protect your capital, you set a stop-loss at $90.
•	If the stock drops to or below $90, your broker automatically closes your position, limiting your loss to $10 per share.
The solution is to enter only on a confirmed break above the resistance level, waiting for a pullback that retests the broken level as new support, risking no more than 1% of total account capital per trade."
This trading strategy advises you to wait for an asset's price to securely break through a price ceiling (resistance), confirm that new price level as a floor (support) during a temporary dip, and protect your account by risking a maximum of 1% of your total funds on the trade. 



Identification of the type of data that will be used to solve the question.

Decision trees are highly effective for non-linear decision-making in complex markets.
Technique: These models ingest dozens of features (such as daily trends, liquidity sweeps, and price gaps) to determine the highest-probability trading conditions. 
Application: The AI evaluates a specific breakout setup against historical examples of success and failure to confirm whether a trade should be taken. 

Required Capstone Assignment 16.1: Finalizing your problem statement

1.	The research question you intend to answer (in one sentence, if possible).
How do you avoid false breakouts (fake outs) that trigger stop losses?

2.	Your expected data source(s) (as either a link to existing data or a sentence describing where you will source the data from)
Expected data sources are tick data, level 2 market depth, time and sales, and aggregated OHLCV Bars.
3.	The techniques you expect to use in your analysis
I can use clustering and principal component analysis to refine breakout strategies, though they serve different functions. PCA simplifies complex data, and clustering groups similar behaviors.
I can use K-fold cross-validation and machine learning for day trading breakout strategies.
I can also use multiple linear regression techniques.
4.	What are the expected results?
False Breakouts: Up to 50% or more of breakouts fail, meaning the price briefly crosses a level and immediately reverses.
Whipsaw Losses: Frequent small losses occur when stop-losses trigger during fake moves.
Massive Winners: Successful breakouts catch fast, powerful trends that cover previous losses and create net profits.
Slippage: Fast market movement during a break can cause poor execution prices on orders.

5.	Why is this question important?
Protecting Money: Day traders use leverage and fast trades. False breakouts drain accounts quickly.

Improving Accuracy: Knowing the risks helps traders wait for confirmation instead of guessing.

Better Risk Management: It forces traders to use stop-loss orders to limit damage.

Emotional Control: Understanding fakeouts stops traders from panic-selling or chasing bad trades.

Exploratory Data Analysis (EDA) is a crucial step in understanding your dataset before building models or drawing conclusions. 
Here's how to approach EDA systematically: 
## Key Steps in EDA: ### 
1. **Data Overview** - Load and examine the structure of your data - Check data types, shape, and basic information - Identify missing values and duplicates ### 
2. **Descriptive Statistics** - Calculate summary statistics (mean, median, mode, std dev) - Understand distributions of numerical variables - Examine frequency counts for categorical variables ### 
3. **Data Visualization** - Create histograms, box plots, and scatter plots - Use correlation matrices and heatmaps - Generate bar charts for categorical data ### 
4. **Pattern Detection** - Identify outliers and anomalies - Discover relationships between variables - Look for trends and seasonal patterns ## Essential Python Packages for EDA:


References
https://capital.com/en-int/learn/trading-strategies/breakout-trading
https://www.investopedia.com/articles/trading/08/trading-breakouts.asp
https://breakouttradingacademy.com/best-ai-for-breakout-trading/

