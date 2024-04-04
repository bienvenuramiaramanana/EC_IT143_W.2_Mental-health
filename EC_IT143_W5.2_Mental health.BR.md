# EC_IT143_W.2_Mental-health


/*****************************************************************************************************************
NAME:    IT143_W5.2_Mental Health 
PURPOSE: creating and answering questions...


MODIFICATION LOG:
Ver      Date        Author        Description
-----   ----------   -----------   -------------------------------------------------------------------------------
1.0     04/04/2024   BIENVENU Ramiaramanana     1. Built this script for EC IT143


RUNTIME: 
Xm Xs

NOTES: 
It is talk about script that i have created...
 
******************************************************************************************************************/
SELECT GETDATE() AS my_date;
use exercises

--Q1: Find all column of mental health community? Author is me
--A1--see the SQL command

SELECT *
FROM [Mental Health Dataset];

--Q2--: Give the country of the person ( affected of mental health) that the name  start with 'B'?  Author is me
--A2--see the SQL command

SELECT Country
FROM [Mental Health Dataset]
WHERE Country LIKE 'B%';

--Q3--:Print the details of person whose where the treatement = 'NO'?  Author is me
--A3--see the SQL command

SELECT *
FROM [Mental Health Dataset]
WHERE treatment = 'NO';

--Q4--:I wanna know if this person have been made an iterview or not. So could you help me to find that ?Author is me
--A4--see the SQL command

SELECT mental_health_interview
FROM [Mental Health Dataset]
WHERE mental_health_interview = 'Yes';
