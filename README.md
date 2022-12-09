# kickstarter-analysis

## Overview of Project

### Purpose: 
#### 	The purpose of this analysis is to provide the client with statistical information about what makes crowdfunded projects successful as well as what may lead them to be unsuccessful. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
		The first step of my analysis of the outcomes based on launch date was to make a table.  The table was made with the dates created as rows and outcomes as columns as well as values. 
	The table was then filtered by parent category. Every category was filtered out save for theater.  
	Lastly, I created the line chart to illustrate the data visually.  The x-axis was time, incremented based on month, while the y-axis was the sum of projects with a given outcome.

### Analysis of Outcomes Based on Goals
		The first step of my analysis of the outcomes based on goals was to also make a table.  The table was made with the goals as rows, grouped in ranges of 5000, and with outcomes as columns.
	Then I summed up the totals and calculated the percentage that were successful as well as the percentage that had failed.
	Lastly, I created a line chart to visuallize the data.  The x-axis were goal amounts in their incremental groups, while the y-axis was the percentage of projects with their given outcome.

### Challenges and Difficulties Encountered
	There are some challenges or difficulties that can be encountered when analyzing this dataset.
	    One such difficulty is taking the higher success rate in larger goals at face value.
	When there is a small sample size, the data can be misleading. 
	For example, in this dataset, when the line for successful outcomes based on goals crosses the failures at $35000 to $45000.  At this range, there are only 10 projects.  
	6 of these were successful so, one could think that those projects have pretty good odds of being successful.  However, given this small of a sample size, the margin of error is too great.
	To more accurately gauge successs rate we should look to the larger sample size of projects at a range of $1000 to $1500.  There are 961 projects in this range.  The margin of error in a dataset this large is much lower.
		Another difficulty that could be encountered is not accounting for several outliers in the initial dataset.
	Outliers can throw off several deciding factors when calculating data including mean (average) and standard deviation.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	Someone should not start a theater campaign in late Autumn/Winter.  The success rates during that time is far too low.
	Campaigns that start in Summer have the best chance of success.

- What can you conclude about the Outcomes based on Goals?
	The Goal of the project should not exeed $10000, going higher is too risky.  Going past $15000 is at best a 50/50 chance for a trustable sample size.

- What are some limitations of this dataset?
	There was no data on cancelled theater projects.
	So few projects had goals above $15000;  what goes in to making those projects successful is questionable.

- What are some other possible tables and/or graphs that we could create?
	We could create a scatter plot with Average pledge amount (y-axis) vs number of backers (x-axis) for theater projects.
		To estimate what amounts to set backing rewards, one would look at the highest concentration of plot points.
	Table containing the country of the project and it's percentage funded as well as values for sum of total projects per coutry andfor percentage of sum at or above 100.
		To estimate which countries have higher success rates for theater projects, we look at the percentage of sums at or above 100.