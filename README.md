# Kickstarting with Excel
## Analizing Kickstarter data to find trends
### Purpose
To determine the success of Kickstarter projects in relation to their launch dates and funding goals.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
To determine how launch date effects the success of a kick starter I first created a pivot table on the new sheet “Theater Outcomes by Launch Date”. The Pivot table broke down theater Kickstarters by the month they were launched and the outcome. 			
![image](https://user-images.githubusercontent.com/100768274/158084544-9c09a192-25b2-48ea-8294-0f6fbad76ce3.png)
From the pivot table I created a line graph of the outcomes throughout a year. 
![image](https://user-images.githubusercontent.com/100768274/158084621-bc5a9b33-bc94-4eaa-8414-a9afd38debe6.png)
### Analysis of Outcomes Based on Goals
To Analyze how the target goal for the Kickstarter effected the success rate I broke the goal down into the following ranges.

![image](https://user-images.githubusercontent.com/100768274/158084698-3a986944-0799-4150-96c0-889794ee2e1a.png)

I then populated the ranges by the outcomes of Kickstarter plays. To populate the ranges, I used the COUNTIF function. I filtered the Kickstarters by the range of the goal, the outcome and the subcategory “plays”. From here I tallied up all the outcome and then calculated the percentage for the outcomes. 
![image](https://user-images.githubusercontent.com/100768274/158085137-cc6403cc-92de-48b1-b646-b28e4636e3be.png)
Using this table I created the following graph.

![image](https://user-images.githubusercontent.com/100768274/158085160-3795d27a-18fa-4922-9a85-03645bca1af7.png)

### Challenges and Difficulties Encountered
## Results
- From analyzing the Outcomes based on Launch Date I can conclude that over all months more theater Kickstarters were successful than failed. Kickstarters launched in May were the most successful, with the next three being the summer months of June, July and August.

From analyzing the Outcomes based on Goals I can conclude that the goal range of “$20,000 to $24,999 had the highest ratio of success to failure at 84.9%. 

- Some limitations of this dataset is that the outcomes based on Launch date does not beak the theater category down to include only plays. This may provide an overly broad amount of data. A problem with the Outcomes based on goals table and graph is that the higher ranges may have too small of a sample size to be reliable. 

-  Some other possible graphs/tables to create would be some that show the success rate based on what specific past year that it was launched. Another good graph/table would be one that breaks down the data based on country of origin. 
