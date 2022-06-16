# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

#Purpose of the analysis
 - Plainly stated, this is a project that aimed to dsiplay the trends in data for Kickstarter Campaigns in various fields. 

#Analysis and Challenges
 - The way that I decided to analyze the graphs and data was probably custom for how others would do it. Instead of just looking at the graphs we built, I would filter on certain sheets in the Kickstarter workbook and make note of it for later on. Thus, when I would go back to the graphs (and praying they were designed correctly) I could follow the data and see exactly where it was triumphant or where it failed. 
   *Challnges* One of the hardest things for me during this specific challenge was being confident in my abilities as a "coder". On the "Outcomes Based on Goals sheet", the numbers canceled kept saying "0" so I thought there was no possible way that not ONE SINGLE PLAY was canceled. I thought I was making a mistake somehwere but then I realized I could make a pivot chart to check to see if there were any plays under it when I filtered for "canceled". Naturally there were not. (Hooray).

-------- *Side note, my descriptive statistics sheet became all messed up when I deleted box and whisker and "successful" and "failed" kickstarter sheets. My coding knowledge does not know how to fix that currently*


#Outcomes based on launch date
 - For theater parent-categories, there are a few things to observe. First, the trend of launching the campaign around the month of may. This tends to have a higher success ratio than those that started in or around October and the following months after. 
  *Second analysis* 
  It can also be seen that the fail to success ratio is not really correlated. In fact, they both have almost the same highs and lows. But starting the campaign in the Winter is not the right time to do it based on this data.
 
 ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107223178/174111133-46b8da44-f00c-4c67-8978-2e28fc4dfbcc.png)




#Outcomes based on goals
Unlike the Outcomes based on launch date graph, the Outcomes based on goals line graph shares a negative correlation between the percentage success and percentage failed lines. As one goes up, the other goes down, "mirroring" its every shift in angle. 
  *Second analysis* 
  From 15k to 19999k, 50% of all plays are successful here. Naturally the other 50% fail at that price range. However, any play priced below that has a better chance at success based on the percentages displayed. At 35k to 39999k, we have a higher priced kickstarter but it only lasts until 50k and anything after that has no success percentage.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107223178/174111283-2f4449cc-5d63-4f1d-b615-7ef7424b0ac9.png)


#Limitations
- As far as limitations go, one thing that stands out to me the most is that there is only a select time frame of the years 2009-2017. If we truly wanted to see how Kickstarter campaigns fair in the summer months, maybe we should have looked at two decades instead of just 8 years. The more data you get, the more robust your visualizations will be, the better analysis you'll get. 
  *Suggesting graphs*
  I think that a pie chart of the parent categories and sub categories AFTER using a pivot table, would be super informative just to see the what exactly the most successful campaigns are based on.
