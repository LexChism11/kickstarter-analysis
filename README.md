# ***Kickstarter-analysis***
Challenge 1 : Performing analysis on Kickstarter data to uncover trends.

## **Overview of Project**

Challenge 1's storyline starts with Louise, a potential candidate looking to compare her kick starter fundraiser to other campaigns. Starting by carefully evaluating the Kickstarted dataset, pivoting out multiple outcomes through excel & then organizing this data into readable graphs. Now, able to describe challenges and difficulties different Theaters could be encountered during their campaigns. As well as concisely analyze the updated results from the dataset.  
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Analysis and Assessment of Challenges
### Gathering data

  I started by copy and pasting my data into an excel workbook, to give me a playground to maneuver data. I froze my top column, threw on a filter and started analyzing the goals vs pledges. The dataset was pulling dates staring from epoch, so I made 2 columns for “date creation” and “ended” conversion and formatted it to short date. Next, I made a start year column using the =Years() function. I also wanted to display the months campaigns started, so I used the =TEXT(T2,”mmm”) function. This gave me the data I needed to start pivoting. 

### Outcomes by Launch Date
  I pivoted out this data to analyze the outcomes of different campaigns by month on a new sheet. I filtered this table, first by the parent category, in this case theater, and the year. I then added the months to my rows, then counted each successful, failed and canceled campaign in my columns. From here, I created a line graph with markers to display my 3 outcomes visually. I accessed that it is more common to have a successful campaign, especially if you start in at the end of the spring in May. Also, that while most people fail to meat their goal than flat out cancel, those two outcomes happen at around the same rate.This over all gives planners an idea on when to start and end their kickstarter. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/96705257/147432759-1e004d9c-01c2-4db1-995c-f048487d041d.png)

### Outcomes based on Goals
  For this evaluation, I made a table with rules to categorize the goal by price. This way, I can see which goals are commonly reached. From here, I used the countif() function to count every successful, failed and canceled campaign within each $ bracket for theater. Then, I summed up the totals, and created columns to give me a % for each parent category. Creating a line graph from this data gives me a lot to review. I can see, while it’s not common to cancel as I learned from my first table, campaigns with high goals above $10,000 are more likely to be canceled. I can see that besides some outliers, successful campaigns usually ask for smaller amounts of money. There is a spike in failures as the goal rises. Despite this, we do have the $35,000-40,000 group hitting their goal despite all odds. 
  
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/96705257/147432794-65cd47ab-b9fd-4861-91d6-4fc503dfadbf.png)

### Challenges
  A challenge I was faced with was making sure I was evaluating the correct data set. When wanting to gather data about outcomes, I needed to know when they started the campaign. For this, I had to use a formula to calculate the date, add it to epoch, then format it to my liking. Otherwise, it would have stayed in scientific mode. 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Results

### Conclusion of Start Sate outcomes.
  This dataset that I pivoted out has a plethora of options and hypothesis. My first conclusion is that people announce their campaigns in the spring, and they start with a lot of donations, and over time they accomplish their goal. That also may be fall inline with tax return season, so many people looking for write offs, and or have extra money to give. The limitation of this particular dataset is that it is not looking at the date ended column. So, it is not taking into consideration the duration of the campaign. We can however create a new graph that does look at the date ended and compare the two.

  My next conclusion focuses on the drop in the winter. The graph steadily drops through-out the summer and hits a low in December, Christmas season. In the winter, people are buying gifts for loved ones, and are not likely to give out more than their budget allows. So, buying theater tickets to help funds depends on audience budget. Also depending on region, people do not go out to the theater at all. Plays can be held outside, or indoors. If you live in a warm place, you are likely to have access to all kinds of theaters year-round. Where ass in colder regions, you are limited to indoor locations & weather that permits travel. If this graph was not limited by just country, and went deeper into location we would avoid this. 
### Conclusion of Goal outcomes.

The conclusion I drew from this data is obvious, the lower your goal the more likely you are to hit it. The % canceled rises right as successful campaigns drops. While not dependent on each other, they happen parallel of each other.  Percentage successful always has spikes when the other outcomes have lower percentages. So, the higher goal amount campaigns that are more likely to fail. Anything below $10000 is has more than a 50% chance of being successful. While campaigns above $45000 is very likely to fail. This data is limited because every campaign may not have the same reason for success/failure. It ma not solely be the goal that influenced outcomes.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------


