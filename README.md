# Springboard
Springboard Projects
This contains my Capstone project in which I perform several Data Wrangling steps

What is the problem you want to solve?
Understand the relationship between oil price, oil field location and field activity during 2015 ( when oil prices dropped). This will help to gain so sort of insight into how price sensitive different companies in different geographic location are.
Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?
My client will be in business development/commercial sector of an oil and gas company, looking to seek future acquisitions based on how active a certain field was before and after the price dropped. Decisions that come out of this analysis would be potential purchases and deals. It also supplements any current deals on the table. A client would want to purchase a company that had a lot of drilling activity (sunk costs) and then halted all operations. 
What data are you going to use for this? How will you acquire this data?
I will use all public DOGGR data which contains the number of wells, production and geographic location for all fields in California. 
In brief, outline your approach to solving this problem (knowing that this might change later)
I will first query all historic data for all of the fields in California from DOGGR. I will then group the data by county, company and year. Then I will get the oil price data from the NASDAQ website, and aggregate by type of crude as well as the year. Then I will go into the analysis of the number of new wells drilled (unique count) by company, by county.  


Data Wrangling Steps:
1.  Forward fill on the Lease Name
2. OG and OG,SC is filtered
3. Group by operator
4. Take out wells without spud date
5. Look at wells in Any Area separately
6. Convert spud date to date (right now it is a text)
