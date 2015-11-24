# FinalProjectWC: The True Co$t of War
![Cartodb](http://i.imgur.com/EoGaOds.jpg)
* [Cartodb—Demo Link](http://bit.ly/1MLv5x9).
* [Hosted on Github](http://penelopeaton.github.io/FinalProjectWC/)

## Description: 
This map illustrates the amount of expenditures and total population of Veteran's in the U.S., and Government Veteran Expenditure per capita.
## Project Procedure: 
* Describe your data processing
* Visualization selection 
* Analysis post-visualization

## Data Processing: 
The data set came from the [Veterans Affairs](http://www1.va.gov/vetdata/Expenditures.asp) website under the Expenditure tab. It is a 2014 data set that includes, by state, all the categories for expenditure totals. Before I opened the data, I read the "Description of the Data" section on the website that tells you what is included and that the Veteran population counts are estimates. I also pulled up the "Trends in the Geographic Distribution of VA Expenditures: FY2000 to FY2009," which included essentially, a lot of the same elects as the data sets that I'm working with have. It discusses how "each fiscal year the Department of Veteran Affair's (VA's) office of Policy and Planning publishes an annual geographic distribution of VA Expenditures (GDX) reports for the public and stakeholders." The report illustrates the estimated dollar expenditures for major VA programs at the state, county and Congressional District Level. This data set helped me understand the one that I used to create the interactive. I was able to see the break down and overall trends over a 9 year span. Then I looked at my set to start the parsing and filtering process. 

The data set includes these categories: Veteran Population, Total Expenditures, Compensation & Pension, Construction, Education & Vocational Rehabilitation/Employment, Loan Guaranty, General Operating Expenses, Insure & Indemnities, Medical Care and Unique Patients. Unique Patients means that number of patients that utilized the Medical Care program (this I discovered from the Data Dictionary on the page I read earlier).
 
First, I saved an alternate set of the data to make sure that any changes I made, I would still have a complete first copy available if need be. To answer my question, Which state receives the most VA money relative to their veteran population? I began by copying the data, and clicking edit—Paste Special—Paste—Values, so that I could delete some of the rows that I didn't need without skewing the data set. I deleted all the columns except for State, VA Population total and Expenditure. I than used the filter technique (Ascending to Descending) to find out that Texas and California had the highest population and highest expenditure rate. I than looked at my old data set to look at the values adding up the expenditure total for both Texas and California to notice where the majority of the money is coming from. It was then clear that Compensation and Pension were the highest categories that make up most of the expenditure totals with medical care as a close second. I than planned out how I wanted to visualize the data set. I thought a map would be the best way as it provides a visual for the viewer to see how many Veterans are within the U.S. and how much money they get based on different variables. I wasn't able to create a map with all the variables so I focused purely on the Population total and Expenditure total so that thew viewer could get the big idea of what places have the most VA population and VA expenditures. I concluded when I created the map that both expenditures and population add up based on states for the most part. 

### Step-by-Step Data Parsing: 

#### Step 1: 
picking the data set from the website and saving an extra copy to ensure that I have a extra one if I mess anything up. 

#### Step 2: 
Read the data dictionary located on the website to ensure that I understood what all the categories meant. Also the data set included notes, so before I deleted them I made sure to read them and leave them included in the extra copy. 

#### Step 3: 
Because I wasn’t using a lot of the variables (columns) I needed to do a special paste in order to make sure that the numbers weren’t skewed once I deleted a column. (Copied the data set, went to edit, clicked on paste special, and clicked “values” which essentially kept all the numbers the same but detached them from their equations.)

#### Step 4: 
I deleted all the rows that I didn’t need to use (including the notes, the title head “FY14 Summary of Expenditures by State Expenditures in $000s) so that I could filter my rows if I needed. I also deleted the total on the top, and left the total on the bottom. I also deleted these categories: Compensation & Pension, Construction, Education & Vocational Rehabilitation, Loan Guaranty, General Operating Expenses and Insurance & Indemnities. I kept State, Veteran Population, Total Expenditure, medical care and unique patients because these are the variables I want to analyze. 

#### Step 5: 
I than looked for a data set that had 2014 population estimates by state so that I could analyze the population of veterans in each state based on their average state population. I added the population estimates to the excel sheet and fixed up the header to look the same as the others.

#### Step 6: 
I than calculated the percentage of Veterans in each state based on each state's population (ie. Veteran Population/State Population). Once I got the numbers I clicked “Percentage” in order to make them all percentages.

#### Step 7: 
I calculated the total of expenditures per veteran (ie. Expenditure Total/Veteran Population)

#### Step 8: 
Than I calculated the total medical care cost per unique patient to find out how much each unique patient would get roughly (obviously these are dependent on the severity of medical services) (equation: Medical Care/Unique Patients)

#### Step 9: 
In order to visualize my data set I ended up making separate excel docs that included only the population numbers (ie. State, State Population & Veteran Population), I also did this for Expenditures (State & Expenditure) 

#### Step 10: 
I than used the excel resources and created line graphs and bar graphs to showcase my work, as well I created a map on Cartodb that illustrates the population and expenditure per state. 

### Step-by-Step Data Analysis Post-visualization: 

#### Step 11: 
I went back to my data set and wanted to make a few conclusions, so I used the filter tab (highlighted my rows and went to Data on the tab, and clicked Filter). I deleted my total as it generated to the top and clicked Ascending on the Veteran population filter (which essentially filtered the whole thing to placing the highest numbers on the top). From there I was able to conclude that California and Texas have the highest Expenditure and Veteran population rate across the board. But I noticed that they didn’t have the highest % of state population who are veterans so I than filtered that category to descending.

#### Step 12: 
After filtering “% of state population who are veterans” (descending) I was able to see that Alaska, Montana and Maine have the highest % of Veteran population based on their state population. Puerto Rico has the least. From there I just continued to understand the data set by filtering when necessary. 

## Visualization Process:
I created the map through [Cartodb](http://bit.ly/1MLv5x9) and made it choropleth map in order to show (through coloring and shading) the most dense population and most dense expenditure rate per state,as well as Veteran expenditure per capita. A choropleth map worked the best as it allows for an immediate conclusion visually. I picked a sequential color scheme with 5 shades because I believe the information suites it best in that it allows for an obvious immediate change within variables or filters. I picked the color green when filtering in Expenditures because it's having to do with money. And I picked the color blue for the population totals because I the main color for Veterans is blue, and I wanted to keep it easy for the viewer to decipher between the two different variables and coloring. I made the map have click menu's that include the population total info, when clicking on a state, as well as expenditure total (when you have the expenditure layer on).

## Analysis Post-Visualization: 
After visualization it I know am completely aware of the most populated Veteran states with the highest expenditures for those Veterans. To conclude my project, I ended up making my own dataset of state populations to figure out how many Veterans there are based on a states population, whether places like Texas and California have more Veterans solely based on their high population, or whether smaller states like Oklahoma, for example, have a Veteran population that is the majority of their sole population or whether it's not at all. I came up with this after looking at my final dataset. I was wondering whether the expenditures and Veteran populations coincide with each other or whether they are purely independent factors. I found that of course they are dependent on each other especially in cases like California and Texas, but I wanted to know whether that was solely because of their high population or something else.

## Sources:
* Visualization: [Cartodb](http://bit.ly/1MLv5x9)
* Data Sets: [U.S. Department of Veteran Affairs](http://www1.va.gov/vetdata/Expenditures.asp)
* Color Scheming: [ColorBrewer2](http://www.colorbrewer2.org)
* Article: [U.S. Department of Veteran Affairs](http://www.research.va.gov/currents/0915-2.cfm)
