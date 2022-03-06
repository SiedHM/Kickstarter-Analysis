# Challenge-1 Report

#1.	Overview of Project.
:A play writer named Louise is writing a play name Fever. For this, she plans to conduct a crowed funding campaign with an estimated budget of a little more than $10,000. Before she starts the campaign, she wants to understand whether there are specific factors that make a campaign successful.  As an excel expert, I am asked to help her by analyzing a kickstart crowd funding data in excel and identify categories that makes campaigns successful. More specifically, she wanted to know how different campaigns fared in relation to their launch dates and their funding goals.



#The purpose of the report is
:i.	To analyze campaign outcomes [i.e., successful, failed and canceled] based on their launch date.
ii.	To analyze percentage of successful, failed, and canceled campaigns based on the funding goal amount 

#2.	Data and Method of analysis
 :I used Kickstarter Data which contains about 4114 crowed funding campaign projects from multiple countries. The data was obtained from Bootcamp for this exercise. I used the excel cell YEAR, CUNTIFS functions, and Pivot table to generate the results. 
The results are analyzed graphically. 

#3 Analysis and Challenge






##3.1. Analysis of Outcomes Based on Launch Date
:   Figure-1 below shows the number of successful, failed and canceled projects based on their launch dates. From this figure, it can be seen that number of successful projects are greater than the numbers of failed and cancelled projects over the entire start dates. Larger number of successful projects started from May to August (i.e., about 44% of successful projects start from May to August). Smaller number of successful projects started at the end of the year.
 
 #[Figure-1 Here]
 
Looking at the pattern for successful projects, the number of successful projects almost increased from the beginning of the year (January) until it reached its maximum in May and then decreased after wards. 
The number of failed projects have trend almost similar to the trend of the number of successful projects. 

#3.2.	Analysis of Outcomes Based on Goals



:Figure-2 shows the percentage of successful, percentage of failed and percentage of cancelled projects based on the fund goals. As can it can be seen from the figure, when the funding goal amount is between $1000 and $29999, the percentage successful(failed) campaign projects decreased(increased) as the funding goal amount increased. Further, when the funding goal amount is above $44999, the percentage of successful projects are below 20% and the percentage of failed projects are above 85%. From this figure, we can conclude that the funding goal amount has an impact on the percentage of successful/failed projects. The higher the funding goal, the more likely is the project to fail. 
 #[Figure-2 Here]



##3.3.	Challenges and Difficulties



:     Based on the instruction given on the challenge, virtual class and also the notes in the module-1, I managed to generate the results for the first deliverable, i.e., outcome based on launch date without any difficulty. However, for the second deliverable, in particular with the COUNTIFS function, I got several error messages. The problem was when I write the function and select the required rows and columns from the other sheet (main data), it gives me error message.  This problem still there when I apply other functions, i..e, if try to use other function in the current sheet and need data from other sheet, I move the cursor to the other sheet to select the rows and columns with the required data,  I still face same problem.
I solved the problem without moving the cursor to the other sheet by typing the sheet name and columns and row numbers of the other sheet in the current sheet.



#4.	Conclusions



: The findings of this project imply that most campaigns launch their campaign almost in the second quarter of the year (May to August). The percentage of successful projects is 50% or above when the goal amount is below $20,000. 
The implication from this is that the higher, in particular, an extremely high goal amount, the more likely is the project campaign to fail.  



#What are some other possible tables and/or graphs that we could create?
We can generate tables/graphs of the following.
1.	In addition to the graph of outcome based on the launch date, we can have outcome based on the duration of the campaign. This requires generation new variable or column using the project start data and project end data.  It may answer to the question how long should the project campaign last to be successful? 
2.	Table that contains the subcategory and percentage of funding amount. 
