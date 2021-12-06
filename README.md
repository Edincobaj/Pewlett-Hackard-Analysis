# Pewlett-Hackard-Analysis
## Overview
The goal of this analysis is to help Pewlett Hackard determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. This will help the team to determine a way forward and prepare for a large number of HP employees to retire.
## Results
To begin our analysis for Pwelett-Hackard we first had to start with creating an ERD so that we can visualize the connections between the six tables that we were given for this analysis.
# ![ERD table](https://user-images.githubusercontent.com/41974323/144906643-47bfdada-4bef-47e6-b33c-cb9cd9366a4f.png)
From there we created two tables, one to show the number of people retiring by their titles and another table to show eligibility for the mentorship program as shown below.
# ![retirement_count_by_title](https://user-images.githubusercontent.com/41974323/144917016-2afc70f2-801f-4745-9fc4-8b7fd94ccd19.png)
# ![mentorship_eligibility_chart](https://user-images.githubusercontent.com/41974323/144917121-368d27a4-e1b3-4457-a2d4-802897ad648f.png)
### Here are 4 big takeaways that we get from our analysis:
* There are 90,398 employees getting ready to retire. That is 30.13% of the entire Pewlett Hackward staff.
* Of the employees retiring, senior positions take up 64% or 57,668 of future retirees.
* We see that there are only 1,549 employees that are eligible for the mentorship program.
* The mentorship program will have to be expanded on as eligible employees for the program only take up 6.46% of the total retirees.
## Summary
From our analysis we can see that a total of 90,398 employees are eligible for retirement in the upcoming years. According to our mentorship program analysis it seems that there is not nearly enough employees to provide mentorship to fill the gaps that Pewlett-Hackard may be presented with. To combat this an expansion either including an additional year or two for program eligibility or taking into account the time spent within the company to add potential mentors will be necessary. An additional query that may give us more insight is to expand our mentorship program to two years(from 1964 to 1965). The results show that adding an extra year expands our potential mentors from 1,549 to 19,905.
# ![additional_query_1](https://user-images.githubusercontent.com/41974323/144920505-f0e8efa3-d66c-474c-b361-e5dd3bc97751.PNG)
Another additional query that I think would be helpful is a count by title for all active employees so that you can see how many total employees there are vs how many of them are retiring by each title. This would give managers a better idea of how hard each position will be hit by the silver tsuname.
# ![additional_query_2](https://user-images.githubusercontent.com/41974323/144922446-2f02baeb-ad2c-418b-8dd1-07d98eebef75.PNG)
