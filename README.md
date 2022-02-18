# Pewlett Hackard Analysis

## Overview
In this analysis we ran queries on the status of employees at PH. We assembled lists of employees according to their tenure at the company, and saw that many were on track to retire soon, especially ranking employees. This prompted the construction of lists to aid with the creation of a mentorship program to facilitate a smoother transfer for mid level employees.

## Results
* The first table we generated, retirement_titles.csv, showed how many important employees are on track to retire soon. This table contains 133776 rows. This means there are that many ranking employees retiring soon.
* The other table created in this section focused on the titles, and showed which departments had the most retiring employees. Senior engineers and staff had the most, with 25916 and 24926 respectively.

![retire_titles_capture](https://user-images.githubusercontent.com/95315957/154603155-3b323bf5-e76d-4f42-acdd-644b352967c4.PNG)

* In the next section we focused on how to mitigate the losses of so many experienced employees with a mentorship eligibility table. This table shows how many employees could serve as mentors for their replacements. There are 1549 rows to this table, indicating there are that many eligible employees. 

## Summary
There are approximately 133776 roles which will need to be filled in the near future. The number of potential mentors, 1549, is not nearly enough to replace employees on a one to one basis. However, it could be beneficial to assign multiple mentees to mentors. We could create an additional query to narrow the potential mentee field (focusing on a particular age range). Another query could be created to sharpen our field even more if we focus on solid mentee candidates from departments which will be the most effected by the 'silver wave' (i.e. engineering and staffing).
