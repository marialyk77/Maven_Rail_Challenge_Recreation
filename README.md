# Maven Rail Challenge - Recreation 

This report was created as part of my commitment to continuous self-improvement.

After submitting my first report for the Maven Rail Challenge, I reviewed the work of other contestants. Some of their reports were truly admirable.

Inspired by their work, I decided to recreate my own report, incorporating new techniques that I observed from the other participants.

## New techniques:
1. I added a white-filled shape behind all the visuals to create white space, giving them a cleaner look and better contrast with the background.
2. I created a line graph highlighting the Max and Min values by applying custom formatting.
3. I combined the line graph with a table focusing on financial aspects.
4. Inspired by: https://www.youtube.com/watch?v=hmk6PxDtbNs
  
![image](https://github.com/user-attachments/assets/c71e98ed-4f27-4aaf-b977-c76902c784b3)

+ Dax used for the conditional formatting:
![carbon](https://github.com/user-attachments/assets/bea8344b-e003-4d32-90c5-bc4be51b5252)

4. Leveraging the visual impact of white space, I created a cluster of two different visuals: a pie chart and a bar graph. This approach helps visualize the question of which ticket class and ticket type are most common in a cohesive unit.
   + Inspired by: https://www.youtube.com/watch?v=v6fP8gyCLLc

![image](https://github.com/user-attachments/assets/8f2258d2-d103-4c1e-a42d-4bbb08a001e3)

5. I extracted the hour from the original Departure Time and formatted it in a 12-hour clock, adding AM or PM to indicate the part of the day.
   + Inspired by:https://mavenanalytics.io/project/15628 
  
![image](https://github.com/user-attachments/assets/2ad3b2fa-3c27-4efb-b436-7482f9103bd7)

6. Then I created an interactive bar graph and a matrix that, with the help of bookmarks, switch between AM and PM hours.

7. I created two overlapping visualizations and inserted related bookmarks to toggle between them.
   
![image](https://github.com/user-attachments/assets/f263c31b-5f9e-4fb5-b0e5-136110f88380)

![image](https://github.com/user-attachments/assets/2e0703e3-fec9-44c2-85f8-41da4a887ab3)

 + Inspired by: https://mavenanalytics.io/project/15628 and https://www.youtube.com/watch?v=_HTF7Ph7Eqc&t=406s

## Key Findings:
+ 580 passengers received refunds even though they did not experience any delays.
  
I am not sure whether this is an actual fact or a mistake in the database documentation.

I am suspicious of this observation and lean towards the idea that it may be a documentation error. The reason is that similar inconsistencies were observed in the [Journey Status] column:

+ 18 trips, which actually arrived on time, were falsely recorded as delayed: 
    
![image](https://github.com/user-attachments/assets/d247ef05-6bdb-48ee-903e-05e83cd4ff67)

## Recommendations 

+ Discussion with Stakeholders: These findings should be discussed with relevant stakeholders to confirm the accuracy of the data. Understanding the root cause of these discrepancies is crucial.
  
+ Data Cleaning: If these inconsistencies are due to documentation errors, the database needs thorough cleaning and validation to ensure accuracy.
  
+ Reexamine Refund Criteria: If it is confirmed that passengers with no delays received refunds, we need to reexamine and possibly revise the refund criteria and processes to prevent unwarranted refunds in the future.







  
