# Excel_Challange
Module 1 Homework
#Background

There have been multiple Crowdfunding platforms that have been used to introduce new products and events, respective to each company's goals and needs. The basic concept is that each project must reach or surpass a starting goal. To aid their efforts, this assignment is intended to sort and analyze previous data by using charts, graphs, tables, and a brief statistical synopsis. 

#Solution

-[Conditional formatting] was used to color coordinate the outcomes: red represents "failed," yellow means "canceled," blue shows "live," and green portrays "successful." Google search was used to aid my use of coordinating the colors for the cells. A new column was made to show how many funds were raised per campaign. The column was placed in G next to the outcome to better visualize the data. 
-Column G was made to portray the amount that every backer paid on avergage to move forward with the projects in hopes of attaining or exceeding their goals. 
-Two new columns were created, one called "Parent Category" at S and the other "Sub Category" at T, which used a formula that I found using Google Search to help separate column R called "Category &Sub Category."

-[Parent_Category_Outcomes] A new sheet was generated called "Parent Categories Pivot Charts" that was used to construct a pivot table and stacked-column pivot chart to organize the amount of projects that were "successful, failed, canceled," or currently "live" per "parent category." Moreover, the stacked-column chart has the option to be filtered by country respective to the data in table. 

-[Sub-Category_Outcomes] A new sheet was fashioned called "Sub Categories Pivot Charts." It contains a pivot table that counts how many campaigns were "successful, canceled, failed," or currently "live" per "sub category." A stacked-column pivot chart was fabricated using the data in the pivot table that can be altered by the country and parent category filters.
-[Timestamps_To_Dates] Referencing back to the data as a whole, the dates in "Launched_at" column L and "Deadline" column M were noted as timestamps. Using the suitable formula found on Google, they were converted to dates sorted by month/day/year. These converted dates were then entered in seperate columns N named "Date Created Conversion" and column O "Date Ended Conversion." I placed the refashioned dates next to the timestamps so that the data was easier to read.

-[Parent_Categories_By_Dates_Outcomes] A new sheet was created named "Parent Category by Dates Charts." In this sheet, a pivot table was made that has a column out "outcome", rows of "dates created conversion," values based on the count of "outcome," and filters based on "parent category" and "years." Next, a pivot chart line graph was generated to better visualize the data in the table. 
-[Conclusions_Based_On_Data]- [https://docs.google.com/document/d/1Vj-vKqx8BRo4snpo8soDR5Ub-9TC-pds/edit?usp=drive_link&ouid=104177162368467608734&rtpof=true&sd=true]

-[Crowdfunding_Goal_Analysis]- A new sheet was created names "Crowdfunding Goal Analysis," which was used to compare the count of successful, failed, and canceled campaigns to the company's goal using the "COUNTIFS()" formula. A line chart was used to help visualize the relationship of the figures generated.

-[Statistical_Analysis]- A new sheet was fabricated named "Backers_Count_Outcomes"  that compares the success and failures of the campaigns to the number of backers count. Additionally, the mean, median, minimum, maximum, variance, and the standard deviation of backers were calculated in repsect to successful and failed campaigns. Based on these figures and determining the outliers helped show the median best summarized the data. The mean showed that there was more variability in the successful campaigns than the unsuccessful campaigns.

-[Conclusion 1] Based on the sub-categories pivot graph, theater plays were the most successful form of campaign with a success value of 187, although it did have the most failures with a value of 132.

-[Conclusion 2] According to the parent-categories pivot chart, journalism was completely successful with a value of 4, and 0 failures. 

-[Conclusion 3] Based on the pivot chart comparing parent-categories to dates, campaigns were cancelled year-round, always under the value of 10 per month. The number of failures stayed between 20-40, and the number of successful campaigns remained consistent between 40-60.

-[Limitations] Some limitations include outside factors of the outcome of events, such as unforeseen weather, events being indoors/outdoors, commuting, cost, proper advertising, as well as the audience and number of population. The data was also gathered from different countries and computing different currencies. 

-[Possible Tables/Graphs To Create] A table I would be interested in seeing is one that includes the “staff pick,” “spotlight”, and comparing it to the outcomes. I am wondering if these events were organized based on the employee’s interests and if it had any effect on the outcome, such as advertising, attendance, and effort into the campaign management.  
-[Mean or Median] I believe the median would be best to summarize the data since the figures are affected by the variance in numbers and contains outliers. The mean would have been used if the data would have been more consistent and symmetrical.
[Variability: Successful or Unsuccessful Campaigns] Based on the data, there is more variability shown in successful campaigns. It makes sense due to the different amounts of money being pledged and whether the goal is reached or exceeded since each campaign sets respective goals to meet.   

