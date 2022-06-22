# Pewlett-Hackard-Analysis

## Project Overview

Bobby's manager has given us two assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. After completing the two items I am to write a report that summarizes the analysis and helps prepare Bobby’s manager for the “silver tsunami” when current employees reach retirement age.

## Resources

- Database Tool and Software packages: pgAdmin 4, PostgreSQL, Visual Studio Code

## Analysis

Below is a snippet of the code block written that retrieved the necessary items from the employee table.

![This is an image](https://github.com/Jahill17/Pewlett-Hackard-Analysis/blob/main/Queries/Deliverable1_Employees_Table_Retrieval.png)

After retreival from the employee table, the following code was run to create a mentorship elgibility table that is listed below it.

![This is an image](https://github.com/Jahill17/Pewlett-Hackard-Analysis/blob/main/Queries/Deliverable2_MentorshipQuery.png)

![This is an image](https://github.com/Jahill17/Pewlett-Hackard-Analysis/blob/main/Queries/Mentorship_Elgibility.png)

## Results

Overall the code writeen retrieved the number of retiring employees by title and write a query to create mentorship eligibility table.  The below items can be inferred from the queries:
- 25,916 senior engineers are eligibile to retire
- 24,926 senior staff are eligibile to retire
- 9,285 engineer are eligibile to retire
- 7,636 staff are eligibile to retire
- 3,603 technique leaders are eligibile to retire
- 1,090 assistant engineers are eligibile to retire
- In total, there are approximately 72k roles that should be backfilled soon due to the number of eligible employees who could retire.
- In total, there are over 1,500 individuals elgibility for mentorship.  It appears the company could push to improve those numbers to deal with future retirements.

![This is an image](https://github.com/Jahill17/Pewlett-Hackard-Analysis/blob/main/Queries/Eligible_Retirees.png)

