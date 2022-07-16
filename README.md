# pewlett_hackard_analysis

# Overview of Analysis

## Background & Purpose

This analysis was initiated by Bobby, an HR analyst working at the company Pewlett Hackard, who is attempting to prepare for a predicted wave of retirements among Pewlett Hackard staff. The purpose of this analysis is to identify how many employees in what roles are eligible to retire, and how many employees may be eligible to participate in a mentorship program to prepare them to fill vacancies created by retiring staff. 

## Process

I created a database in PostgreSQL, using the SQL query language, and some data provided by Bobby at Pewlett Hackard. To identify how many employees would be retiring in each role, I first create a table of all employees eligible to retire and their titles. I then used the DISTINCT ON method, along with ORDER BY their end date, to find current employees and their most recent title. I then identified staff about ten years from retirement who may be eligible for a mentorship program. Full data can be found [here](https://github.com/ehalprin/pewlett_hackard_analysis/tree/main/data).

!['Distinct On' Method](https://github.com/ehalprin/pewlett_hackard_analysis/blob/main/Distinct_On.png)

# Results

## Results from Analysis

The analysis revealed the following:
- Over 70,000 staff currently working at Pewlett Hackard are eligible for retirement in the near future.
- The bulk of these staff (around 35%) are Senior Engineers, and another 34% are Senior Staff.
- However, not many managers are eligible for retirement (only 2).
- Only 1,549 staff were identified as potentially eligible for a mentorship program

# Summary

## The "Silver Tsunami"

Pewlett Hackard will need to fill over 70,000 positions as a huge number of their employees become eligible for retirement in the coming years. However, only 1,549 staff members were identified as eligible for a potential mentorship program to mentor the next generation of employees, leaving a sizeable gap and many vacant positions. 

## Additional Queries

In order to continue to "future proof" Pewlett Hackard, additional analysis should be completed. As many of the positions being vacated are Senior Engineers or Senior Staff, another table that should be created is a table of current Staff and Engineers earlier in their careers who may be potentially eligible for promotion, to fill in the gaps by senior leadership leaving. Another potentially important aspect to look at is salary information; are staff getting regular salary increases during their time at Pewlett Hackard? Employee retention should be a top priority for the company, and making sure staff are getting regular raises is a great way to make sure that they're happy, and that the company doesn't lose more people than they already are going to.
