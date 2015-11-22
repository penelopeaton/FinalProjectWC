# FinalProjectWC: Where Does The VA Money Go? 
![Cartodb](http://i.imgur.com/m83erfi.jpg)
* [Cartodb](https://penelopeeaton.cartodb.com/viz/2343d818-916c-11e5-88ba-0e3ff518bd15/map).

## Description: 
This map illustrates the amount of expenditures and total population of Veteran's in the U.S. With a close look at
## Project Procedure: 
describe your data processing, visualization selection, and analyses post-visualization
## Data Processing: 
The data set came from the [Veterans Affairs](http://www1.va.gov/vetdata/Expenditures.asp) website under the Expenditure tab. It is a 2014 data set that includes, by state, all the categories for expenditure totals. Before I opened the data, I read the "Description of the Data" section on the website that tells you what is included and that the Veteran population counts are estimates. I also pulled up the "Trends in the Geographic Distribution of VA Expenditures: FY2000 to FY2009," which included essentially, a lot of the same elects as the data sets that I'm working with have. It discusses how "each fiscal year the Department of Veteran Affair's (VA's) office of Policy and Planning publishes an annual geographic distribution of VA Expenditures (GDX) reports for the public and stakeholders." The report illustrates the estimated dollar expenditures for major VA programs at the state, county and Congressional District Level. This data set helped me understand the one that I used to create the interactive. I was able to see the break down and overall trends over a 9 year span. Then I looked at my set to start the parsing and filtering process. 

The data set includes these categories: Veteran Population, Total Expenditures, Compensation & Pension, Construction, Education & Vocational Rehabilitation/Employment, Loan Guaranty, General Operating Expenses, Insure & Indemnities, Medical Care and Unique Patients. Unique Patients means that number of patients that utilized the Medical Care program (this I discovered from the Data Dictionary on the page I read earlier).
 
First, I saved an alternate set of the data to make sure that any changes I made, I would still have a complete first copy available if need be. To answer my question, Which state receives the most VA money relative to their veteran population? I began by copying the data, and clicking edit—Paste Special—Paste—Values, so that I could delete some of the rows that I didn't need without skewing the data set. I deleted all the columns except for State, VA Population total and Expenditure. I than used the filter technique (Ascending to Descending) to find out that Texas and California had the highest population and highest expenditure rate. I than looked at my old data set to look at the values adding up the expenditure total for both Texas and California to notice where the majority of the money is coming from. It was than clear that Compensation and Pension were the highest categories that make up most of the expenditure totals with medical care as a close second. I than planned out how I wanted to visualize the data set. I thought a map would be the best way as it provides a visual for the viewer to see how many Veterans are within the U.S. and how much money they get based on different variables. I wasn't able to create a map with all the variables so I focused purely on the Population total and Expenditure total so that thew viewer could get the big idea of what places have the most VA population and VA expenditures. I concluded when I created the map that both expenditures and population add up based on states for the most part. 
## Visualization Process:
I created the map through [Cartodb](http://bit.ly/1MLv5x9) and made it choropleth map in order to show (through coloring and shading) the most dense population and most dense expenditure rate per state. A choropleth map worked the best as it allows for an immediate conclusion visually. I picked a sequential color scheme with 5 shades because I believe the information suites it best in that it allows for an obvious immediate change within variables or filters. I picked the color green when filtering in Expenditures because it's having to do with money. And I picked the color blue for the population totals because I the main color for Veterans is blue, and I wanted to keep it easy for the viewer to decipher between the two different variables and coloring. I made the map have click menu's that include the population total info, when clicking on a state, as well as expenditure total (when you have the expenditure layer on). 
## Analysis Post-Visualization: 
After visualization it I know am completely aware of the most populated Veteran states with the highest expenditures for those Veterans. To conclude my project, I ended up making my own dataset of state populations to figure out how many Veterans there are based on a states population, whether places like Texas and California have more Veterans solely based on their high population, or whether smaller states like Oklahoma, for example, have a Veteran population that is the majority of their sole population or whether it's not at all. I came up with this after looking at my final dataset. I was wondering whether the expenditures and Veteran populations coincide with each other or whether they are purely independent factors. I found that of course they are dependent on each other especially in cases like California and Texas, but I wanted to know whether that was solely because of their high population or something else.

