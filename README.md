# kickstarter-excel
Excel project for analyzing kickstart data
# Kickstarting with Excel
​
## Overview of Project
​ The overview of the project was to use different methods and functions within Microsoft excel to interpret and showcase a data set; as well as to illustrate it with the use of graphs and charts in order to give anyone viewing it a visual that shows the changes within it. 

### Purpose
​ The purpose of this project was to compare how Louise's campaigns differed from each other while utilizing the datasets of Launch dates and Funding Goals as methods of comparison between them.

## Analysis of the project
​The way I approached the project was to get a better understanding of how to use the different functions within excel. By following how the steps and equations were presented throughout the module, it helped me set up the excel sheet and ensured the proper outcome that was expected. Although there was a lot of success when following the provided instructions, I did encounter a few challenges and issues that halted progress when creating the tables and charts.  

### Analysis of Outcomes Based on Launch Date
This part of the project, was the most successful part for me when in terms of understanding how to approach it as well as completing it as a whole. Most of it was done during the completion of the module itself so the majority of it was just fine tuning the data as well as the chart to ensure that it matched what was requested. My initial thought process was to start a whole new section before I had realized that most of the work was already completed. 
​
### Analysis of Outcomes Based on Goals
​Compared to the previous work, this section is where I felt the most challenged. I was eventually able to better understand the `countifs(` function. I did use the hint that was provided to set up the rest of the formula that was used on this section, however, I did encounter a few issues that I ended up stepping away from the project for a day in order to get a fresh mind on the next day I worked on it. 

### Challenges and Difficulties Encountered
Most of my challenges on this project did occur in the Outcomes Based on Goals section. The `countifs(​` function was initally working well with setting up the table that was required before the chart was created. However, once the line graph was illustrated it did not match the example one given in the Deliverables section of the project. This was a significant road block for me since I was genuinely lost on what may have gone wrong with my data set. Turns out after consulting another classmate on where I may have gone wrong, my `countifs(` function was missing two things. On my fist data set I had `=COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,"successful",Kickstarter!$R:$R,"plays")`  After looking carefully at it, I was missing an equals sign after the greater than sign which threw off my data as well as the chart. 

The second issue that was discovered was on this function `=COUNTIFS(Kickstarter!$D:$D,">=50000",Kickstarter!$F:$F,"cancelled",Kickstarter!$R:$R,"plays")` this function is what I ended up using since I had originally followed the previous steps leading up to the last section which initially included adding a range limit however, it which it turned out to not need that one at all which ended up allowing my data to match the charts that were given in the project examples.

#Results
​
## Conclusions about Theater Outcomes by Launch Date
​When it comes to this data set, there shows the trend of a high output of projects within months of  May, June and July having the high rate of projects to succeed whereas a small uptick of successful projects occurring in January and February. This can correlate to things such as social events like the winter holidays as well as the summer breaks in schools where families are more inclined to back projects since those are popular times for families and guests to go see shows and events. 

## Conclusion based on Goals
As opposed to the Launch dates, the data shows that low costing projects as wells projects that sit within the $40000 goal seem to have the best rate of success. This could be in relation to either having many projects at low costs come out at once or having a single lucrative project.  
​
# Data Limitations
​The data is limited by the lack of demographics such as backers by age group, race, gender identity as well as geographical data such as economic status, ethnic groups and occupational status. Furthermore, the demographics can relate to where the backer found the Kickstarter in places such as paper or digital advertisements which could be broken down further to help specify where the strong and weak points are when it comes to exposure to the kick starters.  Each of these could provide more details on who is backing the projects and could potentially lead to a more focused plan in the future to get projects funded properly. 
