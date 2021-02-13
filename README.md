# KickStarter-Excel-Analysis
## Background
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.
Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. I organized and analyzed a database of 4,000 past projects in order to uncover any hidden trends described in the "KickStarter Data Analysis Report.docx".

- Used conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

- Created a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.

- Used conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

- Created a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.

- Created two new columns, one called Category at Q and another called Sub-Category at R, which uses formulas to split the Category and Sub-Category column into two parts.

- Created a new sheet with a pivot table that analyzed the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

- Created a stacked column pivot chart that can be filtered by country based on the table.

- Created a new sheet with a pivot table that analyzed the initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

- Create a stacked column pivot chart that can be filtered by country and parent-category based on the table.

- Created 2 new columns named Date Created Conversion and Date Ended Conversion that used a formula to convert the data contained within launched_at and deadline into Excel's date format.

- Created a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.

- created a pivot chart line graph that visualizes the table.




Created a report in Microsoft Word called "KickStarter Data Analysis Report.docx" that answered the following questions.

- Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
- What are some limitations of this dataset?
- What are some other possible tables and/or graphs that we could create?
