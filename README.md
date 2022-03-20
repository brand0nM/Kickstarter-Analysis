# Kickstarting with Excel
## Project Overview

The Client had a play on Kickstarter that came close to its fundraising goals, but ultimately failed; now they now wants to understand how its launch date and funding goals will affect their new campaign.

### Purpose

Using Excel this project will visualize campaign outcomes based on their launch dates and funding goals.

---

## Analysis and Challenges

Two instruments were created to better uncover these data trends. The first is a chart of successful, failed and canceled kickstarter vs their respective launch months. The second groups fundraising goals into $5000 increments and compares them to their respective success rates. 

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/79609464/159175595-8b72e22d-a75e-4426-8cb9-752f9342ac43.png)

At first glance the seasonality of theater kickstarters is obvious. Summer months tend to not only have more theater kickstarters, but also more succesful theater kickstarter. This can be observed since the spread of successful to failed kickstarters widens around the months of April through July. 

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/79609464/159175580-dc11700f-186b-42dd-b2bb-df40a263ac89.png)

This graph is a little deceptive and should not be interpreted without also referencing its Table. It appears that the most successful kickstarters need funding between 40K-50K, but actually the most consistently successful campaigns asked for less than 15K. 

### Challenges and Difficulties Encountered

Though the results are relatively straight forward, our second vizualization paints a different picture from what occurs in reality. Since the graph does not overlay a normal distibution showing the total percentage of kickstarters in each category, it appears that the "less than 1K" and "45K-50K" categories have an equal weighting- or the same amount of candidates in each category. In reality the "less than 1K" category has 186 times the amount of entries, which skews how we vizualize it's results. None-the-less, in conjunction to our table many powerful conclusions can be drawn.

---

## Results

1. Summer months tend to not only have more theater kickstarters, but also more succesful theater kickstarter; observable through the graphs spread in the summer months. 
	- The amount of canceled kickstarters peaks in January, but remains relatevely staginate. 
	- A campaign is most uncertain if released in the Fall/Spring times
2. Campaign goals do not affect the outcome as much as other factors
	- Most campaigns have a goal of less than 15K and in general, the cheaper the goal the more likely they'll achieve it. 
	- More expensive campaigns between 35K-45K also have a good chance of success.
![Total_Percentage](https://user-images.githubusercontent.com/79609464/159178076-c2afb086-1bb1-445b-8f82-f9557941566d.png)
  -Interpreting the results with this normal distibution is best.
  
3. This data set is primarily limited by the amount of data. With more data a more accurate model could be created.

4. If I could change one thing to these models, I would normalize the second graph. This would eliminate the need for a second graph to help interpret the results.

---
