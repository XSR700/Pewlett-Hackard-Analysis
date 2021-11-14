# Pewlett-Hackard-Analysis

## Overview of the analysis: Explain the purpose of this analysis.
This analysis uses Sequel (SQL) programming tool to help review employee databases for a big company. Pewlett-Hackard will soon undergo a "Silver Tsunami" which is where employees born during the baby boomer generation will start to retire and create a labor shortage vacuum in the company. This analysis will identify and display exactly how many employees will start retiring and which positions will need to be filled for the incoming labor shift. 

## Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.

### Point 1:

According to retiring_titles.csv, the majority of employees who are retiring hold a Senior Engineer title.

![Retiring Titles](https://github.com/XSR700/Pewlett-Hackard-Analysis/blob/main/retiring%20titles.PNG)


### Point 2:

The second most held title of employees who are retiring is Senior Staff. The difference between retiring Senior Engineers and Senior Staff is a relatively close statistic in comparison (1,160 employees). 

### Point 3:

1,549 employees are eligible for the Mentorship Program. 

![Mentorship Count](https://github.com/XSR700/Pewlett-Hackard-Analysis/blob/main/Mentorship%20Count.PNG)

### Point 4:

Of all the employees who are eligible for the Mentorship Program, the majority holds the Senior Staff position. 

![Mentorship Count by Title](https://github.com/XSR700/Pewlett-Hackard-Analysis/blob/main/Mentorship%20Count%20By%20Title.PNG)

## Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?

A total of 90,398 employees will soon retire from PH. This includes employees who are born between 1952 and 1955. The current retirement age in the U.S. is 66 years old, therefore all the employees in this pool are currently eligible for retirement. The vast majority of the retiring employees hold positions as Senior Engineer and Senior Staff. These titles will be the most impacted. However, PH can promote its current employees to fill these senior positions. After combining the employees with the title table we can see the total employees each title holds in the image below. 

![Total Title Count Summary](https://github.com/XSR700/Pewlett-Hackard-Analysis/blob/main/all%20title%20count%20summary.PNG)

We see that there is a total of 105,710 engineers. If we subtract 14,221 engineers who are about to retire, then that leaves 91,489 engineers to potentially be promoted. If We apply the same math to the staff, we get 28,881 staff employees who could potentially be promoted. This will profoundly help fill in the positions of Senior Engineer and Senior Staff. 

As for the rest of the titles in the list, we don't see who can be shifted around or promoted to fill these gaps. After adding up all of the employees who are retiring in these positions (Engineer + Staff + Technique Leader + Assistant Engineer + Manager) we get a result of how many roles will need to be filled. Therefore we can conclude that at least 32,728 positions will need to be filled. 

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

According to the Mentorship Elegibility.csv there are not enough retirement-ready employees to mentor the next generation. The query result below illustrates all the eligible mentor count by title. We see that majority of them are Senior Staff and Engineers. Senior Engineers are ordered third with a wide difference. Ideally a Senior Engineer would mentor a lower lever engineer but there is 1 Senior Engineer for every 625 engineers. Even If all the mentor engineers were promoted that would leave 1 for every 157. This is unpractical and inefficient to manage this many employees. PH should consider increasing the eligibility of the mentorship program.


![Mentorship Count by Title](https://github.com/XSR700/Pewlett-Hackard-Analysis/blob/main/Mentorship%20Count%20By%20Title.PNG)
