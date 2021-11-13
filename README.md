# Pewlett-Hackard-Analysis

## Overview of the analysis: Explain the purpose of this analysis.
This analysis uses Sequel (SQL) programming tool to help review employee database of a big company. Pewlett-Hackard will soon undergoe a "Silver Tsunami" which where employees born during the baby boomer generation will start to retire and create a loabor shortage vacuum in the company. This analyis will identify and display excatly how many employees will start retiring and which positions will need to be filled the most in the aftermath. 

## Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.

### Point 1:

Acording to retiring_titles.csv, the majority of employees who are retiring hold a Senior Engineer title.

![Retiring Titles](https://github.com/XSR700/Pewlett-Hackard-Analysis/blob/main/retiring%20titles.PNG)


### Point 2:

The second most held title from employees who are retiring is Senior Staff. The difference between retiring Senior Engineers and Senior Staff is 1,160 employees which is a relativly close statistic in comparison. 

### Point 3:

There are 1549 employees who are eligable for the Mentorship Program. 

![Mentorship Count](https://github.com/XSR700/Pewlett-Hackard-Analysis/blob/main/Mentorship%20Count.PNG)

### Point 4:

Of all the employees who are eligable for the Mentorship Program, the majority hold the Senior Staff position. 

![Mentorship Count by Title](https://github.com/XSR700/Pewlett-Hackard-Analysis/blob/main/Mentorship%20Count%20By%20Title.PNG)

## Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?

A total of 90,398 employees will soon retire from PH. This includes employees who are born between 1952 and 1955. The current retirement age in the U.S. is at 66 years old, threfore all the employees in this pool are eligable for retirement. The vast majority of these retiring employees hold positions as Senior Engineer and Senior Staff. These titles will be the most impactful. However PH can promote its current employees to fill these senior positions. After combining the employees with the title table we can see the total employees each title holds in the image below. 

![Total Title Count Summary](https://github.com/XSR700/Pewlett-Hackard-Analysis/blob/main/all%20title%20count%20summary.PNG)

We see that there is a total of 105,710 engineers. If we subtract 14,221 engineers who are about to retire, then that leaves 91,489 engineers to potentially be promoted. If We apply the same math to the staff, we get 28,881 staff employees who could potentially be promoted. This will profoundly help fill in the positions for Senior Engineer and Senior Staff. 

As for the rest of the titles in the list, we dont see who can can be shifted around or promoted to fill these gaps. After adding up all of the employees who are retiring in these positions (Engineer + Staff + Technique Leader + Assistant Engineer + Manager) we get a result of how many roles that will need to be filled. Therefore we can conclude that at least 32,728 positions will need to be filled. 

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
