# 2022 Jun: Kickstarter Campaign Analysis
 DABC class, Kickstarter sample data. Module 1.
 Excel tables, pivot tables, and graphs.
 
 
 - The month of May has shown the highest number of successful outcomes.
 
 ![Outcomes Based on Launch Date.png](https://github.com/laurinalastella/kickstarter-analysis/blob/main/Outcomes%20Based%20on%20Launch%20Date.png?raw=true)
 
 
 - Among the categories, theater has the highest number of successful campaigns.
 
 ![Parent Category Outcomes.png](https://github.com/laurinalastella/kickstarter-analysis/blob/main/Parent%20Category%20Outcomes.png?raw=true)
 
 
 
 
 - In both the US and GB, plays are the most successful sub-category of theater campaigns.
 
 ![Subcategory Statistics US.png](https://github.com/laurinalastella/kickstarter-analysis/blob/main/Subcategory%20Statistics%20US.png?raw=true)
 
 
 ![Subcategory Statistics GB.png](https://github.com/laurinalastella/kickstarter-analysis/blob/main/Subcategory%20Statistics%20GB.png?raw=true)
 
 
 Observations:
 - Your five favorite Edinburgh plays had a minimum goal (in GB Pounds) of 1000, and a maximum goal of 4000.
 - They had an average goal of approximately 2000 GBP, and all of their pledges were over their goals.
 
 Recommendations:
 - Aim your campaign goal to be between $3000-$5000.
 - May is the best month to launch a campaign.
 
 
 
<!------ 2022=06-23: Update: Challenge 1 ----------->


# Kickstarting with Excel

## Overview of Project

### Purpose: To practice skills such as:
* Using formulas to re-format existing data, and to extract new calculated data.
* Creating Pivot Tables to group and summarize raw data.
* Creating graphs to display and explain the most useful summary data for the customer. Visualizing data is often the best way to tell a story. Clear and accurate visualizations should inspire good decisions.

### Analysis of Outcomes Based on Launch Date
- Parent Category filter = Theater.
- Date Created = UNIX Date converted to Excel date, grouped by Month, all Years combined.
- Outcomes grouped and counted by Month.

![Graph_Theater_Outcomes_vs_Launch](/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
- COUNTIFS used to count the number of Outcomes per Goal amount, in bins of $5000.
- Subcategory of Plays, under Theater Category.
- Simple percentages calculated. All percentages are accounted for, and add up to 100%.

![Graph_Outcomes_vs_Goals](/resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered

* Leaning what UNIX dates are and how to convert them to readable dates seems very useful. This was not something I knew about. I'm happy to know more about it now.
* Excel is one of the only parts of this Data Analytics Boot Camp that I will have familiarity or comfort with. Pivot Tables and Graphs are difficult to learn. Sometimes the default settings are not what is needed, and learning how, where, and why to customize the settings can be confusing.

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?
   - May has the highest number of successful campaigns.
   - December has the lowest number of successful campaigns.

### What can you conclude about the Outcomes based on Goals?
   - Goals of $45,000 and higher have the lowest number of successful outcomes.

### What are some limitations of this dataset?
   - The scale of the project is missing. Data points like size of production, size of the theater, number of cast & crew members, etc. are missing.
   - The scale of the marketing campaign is missing. The amount of pre-launch funding for social media or other marketing efforts is not included.

### What are some other possible tables and/or graphs that we could create?
   - Staff Pick has not been explored.
   - Day of the week the launch happens, including weekdays versus weekends, can have an effect on social media campaigns. Looking at the dates more granularly could reveal useful trends.
   - Absolute number of Backers compared to other metrics has not been explored.
