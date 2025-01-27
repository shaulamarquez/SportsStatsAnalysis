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
I would like to explore the athletes perticipation and permformance by gender distribution, partipation trends, performance outcomes (medals), and country rerpesentation over time.

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

