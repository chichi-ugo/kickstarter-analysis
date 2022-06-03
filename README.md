# An Analysis of Kickstart Campaigns
Analysis on Kickstarter data to uncover trends

## Overview of Project

### Purpose
This analysis is aimed to determine whether there are specifc factors that contribute to the success of a campaign and assist Louise in understanding the projection for her own crowdfunding campaign in order to set her up for her own success. 

With the initial analysis of the data, we were able to see that the parameters "Launch Date" and "Funding Goal" may have an impact, or indicaions, on the overall success of the campaign. The following is a summary of the results of looking at these parameter specifically.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
We looked specifically at the category "Theater" campaigns data, as that was what most benefited our client Luise. We compared the "Launch Dates" of the compaigns over the years to their "Outcome" (whether they were successful, failed, or canceled) and looked specifically at each month to determine a trend. The "live" outcome was filtered out of the data, as it was not pertinent to the overall comparison. 
 
![Image depicting line graph of Launch Date data](https://github.com/chichi-ugo/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_%20Launch.png?raw=true)

### Analysis of Outcomes Based on Goals
We further filtered our data to look specifically at the subcategory "Plays" to best align with our client's interest. The "Goals" parameter is in dollar amounts for the different currencies represented in our data (our client did not specify for us to filter the data further by country so all countries are represented). These dollar amounts were then grouped in ranges of 5000. The percentage of succcessful, failed, and canceled plays for each dollar range was calculated and plotted on the chart below.
 
![Image depicting line graph of Outcome vs Goal data](https://github.com/chichi-ugo/kickstarter-analysis/blob/main/Resources/Outcome_vs_Goal.png?raw=true)

### Challenges and Difficulties Encountered
A potential challenge that was encountered was in the latter half of our analysis. When we saw that there were zero canceled plays, we double checked our formulas and went back to our data to confirm this. With so many lines of data to check, this was a bit of an obsticle to overcome.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. From the data depicted in the line graph, we can predict that the best months to launch a campaign is in the summer months - May, June, and July.
  2. The curve for failed plays is relatively flat, but we can see a slight spike in the month of October, inddicating that this may not be a good month to launch a campaign.

- What can you conclude about the Outcomes based on Goals?
  1. We can see that a higher percentage of plays are successfull when their goal is less than about 5,000. There is a spike again in successful plays with goals 35,000 and 40,000, however the percentage of success drops immediately with the higher goals. We can also see that the highest percentage of failed plays peaks at goals between 25,000 and 30,000.

- What are some limitations of this dataset?
  1. There was little data for canceled theater projects, and none at all for the plays subcategory, so this limits the conclusions that can be drawn from them. 
 
- What are some other possible tables and/or graphs that we could create?
  1. We could analyze whether the length of the campaign has an effect on the Outcome. We would calculate the campaign length by converting the deadline date and finding the time length between the launch date and the deadline. Then we could plot this data in a line graph and analyze for trends.
  2. We could analyze whether the Staff Pick parameter has an effect on the outcome and depict this in a stacked bar graph.
  3. We possibly could run analysis to see what number of Backers could serve as the threshold for a successful campaign. On intial look at the data, it is clear that having more backers correlated with having a higher Pledged amount than Goal (which indicates a successful campaign). 

