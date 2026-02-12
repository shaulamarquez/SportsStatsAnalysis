# Learn SQL Basics for Data Science Specialization Capstone 

This is a SQL for Data Science Capstone Project by University of California Davis in Coursera

## Milestone 1: Project Proposal and Data Selection/Preparation
You are a data scientist working for a data analytics firm. Your firm has explored a multitude of data sources and is tasked with providing key insights that your clients can make actionable. Your manager has asked you to provide some data analytics guidance for one of the firm’s clients.

In a typical scenario, you would iteratively work with your client to understand the data wanting to be analyzed. Having a solid understanding of the data and any underlying assumptions present is crucial to the success of a data analysis project. However, in this case, you will need to do a little more of the “heavy liftinganagement.

## To begin, you will prepare a project proposal detailing:
The questions we are wanting to answer,

initial hypothesis about the data relationships, and

the approach you will take to get your answers.

NOTE: The proposal is just a plan for how we will travel. It’s there to help keep you on your path by keeping the end goal in mind. You will then will execute your plan and in the end present your findings in a month to your management.

## Project Proposal
I would like to explore the athletes perticipation and permformance by gender distribution, participation trends, performance outcomes (medals), and country representation over time.

1. Which country has more representative?

   ![image](https://github.com/user-attachments/assets/b6892393-b07f-486a-91b8-401d65e10e64)

2. How many athletes participated in each year?
   ![image](https://github.com/user-attachments/assets/cc738497-4972-4000-b8b4-cccff6fdd95a)

3. Which county has more medals?
   ![image](https://github.com/user-attachments/assets/cfc184ae-725c-4466-9843-cb745cc1fb84)

## Questions:

Which client/dataset did you select and why?
SportsStats (Olympic Dataset - 120 years of data).

SportsStats is a sports analysis firm partnering with local news and elite personal trainers to provide “interesting” insights to help their partners. Insights could be patterns/trends highlighting certain groups/events/countries, etc. for the purpose of developing a news story or discovering key health insights.

I chose this dataset because it is smaller than the other two.

## Describe the steps you took to import and clean the data.
I downloaded and imported it into my Notebook to analyze using Python. I removed the duplicates. There are 27,116 entries and 15 columns. There were 9,474 that had no age, 60,171 that had no heights, 62,875 had no weights and 231,333 had no medals. In NOC, there are 230 entries and 3 columns.

## Milestone 2

1. Provide a summary of the different descriptive statistics you looked at and WHY.

   The Dataset date range from 1896 to 2016. I used the sum, avg, min and max method for descriptive analysis.

2. Submit 2-3 key points you may have discovered about the data, e.g. new relationships? Aha's! Did you come up with additional ideas for other things to review?

   The popular sports through the years are Athletics, Gymnastics, Swimming, Shooting and Cycling. Those who are rich countries tend to win more medals. And throughout the years the number of athletes that are joing the Olympics are flactuating due to number of reasons. Which I included on my data.

   ![image](https://github.com/user-attachments/assets/96bf2560-35d4-45b5-bbfa-013002445ad2)


3. Did you prove or disprove any of your initial hypotheses? If so, which one and what do you plan to do next?

   Yes, It shows that rich countries tend to win more medals. I want to know thru the years the consistency of the rich countries.

4. What additional questions are you seeking to answer?

   I wanna know if men still dominate the sports thru the years?

## Milestone 3

Dive Deeper
Look deeper into the features you are investigating, consider:

Relationships/Correlation, Pearson Correlation
Linear Regression for future prediction(if the relationship is linear)
Textual Analysis for TF-IDF(Term Frequency-Inverse Document Frequency; Row-based and column-based, stop-word removal?
Specify 1-2 correlations you discovered. List the fields that you found to be correlated and describe what you learned from these correlations.

Go Broader
Expand the features you are investigating. Look for connections/relationships that you may have intially missed.

What jumps out at you now?
Use the descriptive stats to point you to features that you may now want to consider.
What key terms did you discover in any text analysis, for whom? Any themes? If you are not analyzing text, summarize what other things you are considering in your analysis?

New Metric
Create 1 or 2 new meterics to track relationship of data you discovered. Explain why you created them.

![image](https://github.com/user-attachments/assets/ee9d16c4-7b84-41ae-b7e7-2778c6abc3aa)

## Interpretation of Each Correlation
1. Total count and medal count (0.91):
There is a strong positive correlation between the total number of USA athletes and the number of medals won. This suggests that when more athletes participate, the number of medals won tends to increase as well.

2. Total count and gold count (0.82):
A strong positive correlation exists between the total number of USA athletes and the number of gold medals won. More athletes likely lead to more opportunities for gold.

3. Total count and silver count (0.80):
This also shows a strong positive correlation between the total athlete count and silver medals, suggesting a similar pattern as for gold medals.

4. Total count and bronze count (0.88):
The strong positive correlation here indicates that an increase in the number of athletes has a particularly high association with the number of bronze medals won.

5. Medal count and gold count (0.92):
The number of medals won and the number of gold medals show a very strong positive correlation, indicating that gold medals contribute heavily to the total medal count.

6. Medal count and silver count (0.89):
A strong positive correlation between total medal count and silver medals suggests that silver medals also significantly contribute to the total.

7. Medal count and bronze count (0.89):
Similar to gold and silver, bronze medals are also strongly correlated with the overall medal count.

8. Gold count and silver count (0.68):
There’s a moderate positive correlation between gold and silver medals, indicating that while there's some relationship, winning gold does not strongly predict winning silver.

9. Gold count and bronze count (0.71):
There’s a moderate positive correlation between gold and bronze medals, showing a similar trend as with silver.

10. Silver count and bronze count (0.80):
A strong positive correlation between silver and bronze medals suggests that when the USA wins more silver medals, they also tend to win more bronze medals.

# Summary
Overall, there is a strong relationship between the total number of athletes and the number of medals won, indicating that increasing athlete participation tends to increase medal counts.
All medal types (gold, silver, and bronze) contribute significantly to the total medal count, though gold has the strongest influence.
The moderate correlations between the different medal types suggest that while winning one type of medal increases the likelihood of winning others, it’s not a perfect predictor.
This matrix reveals that higher athlete participation tends to positively impact the USA’s success in winning medals across all types.

## Milestone 4

# Your presentation must include:
Build on Project Proposal
Build on your project proposal (from Milestone 1) that described the client or dataset you chose, the approach you were going to take, your initial hypotheses, and your initial approach. Include descriptive stats and any visualizations from your data exploration. You want to highlight key learnings from your data exploration and any aha's or changes to your plan as a results of your findings:

Include Client/Hypotheses/Approach

Include artifacts from previous modules

Include results (good and bad paths); Correlations / regressions

Graphics / Visualizations

Discuss Insights Discovered
Discuss insights discovered (results from your diving deeper / going broader analysis). This is where you put your spin on what you’ve discovered

Discuss your hypotheses and any direct outcomes from whether you were right or wrong.  Did you change your hypotheses? Or create new ones?

Discuss any metrics you created and why?

Discuss discoveries about relationships in the data / themes discovered.

Recommendations and Actions
Summarize the insights you found and make recommendations on what your client should do. What is the next steps or the action that should be taken as a result of your analysis?

[Milestone 4](https://github.com/shaulamarquez/SportsStatsAnalysis/blob/main/Milestone_4.pdf)
