# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project is to compare fare of different campaigns in relation to their launch dates and their
funding goals. With the Kickstarter dataset, campaign outcomes will be visualized. According to the background,
"Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how 
different campaigns fared in relation to their launch dates and their funding goals."

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Dates
First, I gathered the years from the converted launch dates, and created a pivot table featuring theater outcomes based
on their launch date, with filters of parent category and years and showing outcomes that are successful, failed, and 
canceled. With theater as parent category, I formed a line chart of the outcomes. Although I placed the fields in the
right areas, I was worried about the date created conversion at first, because it was not in the proper format that
time. However, I just needed only the months, so it was no longer a problem.

![Outcomes Based on Launch Dates] (https://github.com/rjchiang/kickstarter-analysis/blob/master/Outcomes%20based%20on%20Launch%20Dates.png)
### Analysis of Outcomes Based on Goals
As a starting point, I created a new sheet featuring outcomes based on goals, featuing wide dollar-amount ranges for
the goals. With the countifs function, I managed to collect how much of the theaters have on the goals and based on
the outcome, and add them all up. I also discovered there's nothing for the cancelled column. At first, I thought the
percentage format is unnecessary until I formed the line chart, and that's when the percents are required.

![Outcomes_vs_Goals](https://github.com/rjchiang/kickstarter-analysis/blob/master/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
As mentioned earlier, I was worried if I have misplaced some parts of the data especially at the beginning.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?

For the Outcomes based on Launch Date, it seems the month of May has the most amount of opportunity due to the peak
as shown in the line graph. As for October, there are no canceled outcomes of theater, along with a high peak on
failed. As for Outcomes based on Goals, the percentage canceled on theaters is a flat zero line, because there are 
no canceled theater outcomes. As for the successful and failed curves, they appear symmetrical, almost as if they\
could cancel out. Limitations of this dataset could be possible outside influences, such as a global pandemic,
negatively affecting interest in theaters. Other possible tables and/or graphs could be Kickstarter outcomes on 
other subcategories, such as technology.
