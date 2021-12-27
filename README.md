# ***Kickstarter-analysis***
Challenge 1 : Performing analysis on Kickstarter data to uncover trends.


## **Overview of Project**

Challenge 1's storyline starts with Louise, a potential candidate looking to compare her kick starter fundraiser to other campaigns. Starting by carefully evaluating the Kickstarted dataset, pivoting out multiple outcomes through excel & then organizing this data into readable graphs. Now, able to describe challenges and difficulties different Theaters could be encountered during their campaigns. As well as concisely analyze the updated results from the dataset.  
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Analysis and Assessment of Challenges
### Gathering data

I started by copy and pasting my data into an excel workbook, to give me a playground to maneuver data. I froze my top column, threw on a filter and started analyzing the goals vs pledges. The dataset was pulling dates staring from epoch, so I made 2 columns for “date creation” and “ended” conversion and formatted it to short date. Next, I made a start year column using the =Years() function. I also wanted to display the months campaigns started, so I used the =TEXT(T2,”mmm”) function. This gave me the data I needed to start pivoting. 

### Outcomes by Launch Date
I pivoted out this data to analyze the outcomes of different campaigns by month on a new sheet. I filtered this table, first by the parent category, in this case theater, and the year. I then added the months to my rows, then counted each successful, failed and canceled campaign in my columns. From here, I created a line graph with markers to display my 3 outcomes visually. I accessed that it is more common to have a successful campaign, especially if you start in at the end of the spring in May. Also, that while most people fail to meat their goal than flat out cancel, those two outcomes happen at around the same rate. 

![Theater_Outcomes_vs_Launch.png]

### Outcomes based on Goals
