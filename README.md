# Pewlett Hackard Analysis

## Overview
Our client, Pewlett Hackard, is interested in querying their employee database for a list of retiring employees and their eligibility to be mentors to younger employees. As the original data come in the form of various tables, it is of interest for the company to join these tables together using their commonalities. Because of this, SQL is chosen for this analysis project.

## Results

To prepare for an exodus of employees due to retirement, PH wants to know the job titles that are the most affected so they can adequately prepare for potential shortages. This following table provides the answer:
<img width="170" alt="Screen Shot 2021-08-14 at 3 40 36 AM" src="https://user-images.githubusercontent.com/84816495/129439032-9f069858-b951-4a3d-baea-a5be4f735945.png">

- As shown, the leading positions that are most affected by the retirement wave are the senior levels of engineers (29414) and staff (28254). 
- Coming close are the general engineers (14222) and staff (12243), which means that if PH plans to promote these cohorts to fill the senior employees leaving, a considerable effort needs to be made in hiring new general engineers and staff. 
- There are considerably less assistant engineers retiring (1761) so they can potentially fill the void caused by the exodus of engineers and senior engineers.
- Very few managers (2) will be retiring so efforts to fill in positions should be diverted from managerial positions.

PH is committed to also ensuring that its employees can receive mentorship throughout their time with the company. As such, with the new wave of people retiring, it is imperative that PH knows whether their mentorship program can continue to be feasible. The following table shows the employees eligible for the program:
<img width="836" alt="Screen Shot 2021-08-14 at 4 50 20 AM" src="https://user-images.githubusercontent.com/84816495/129440577-d11b798d-5583-433a-89c7-d86653639476.png">

## Summary

_How many roles will need to be filled as the "silver tsunami" begins to make an impact?_

From the retiring_titles table, there are 90398 employees retiring and that number of positions should be filled in order to maintain the current rate of productivity in the company.

_Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?_

