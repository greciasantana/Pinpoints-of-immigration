# Understanding Immigration 

Statistics on Immigration into the United States. Immigration is a huge political phenomena to the United States residents; mostly because of generalization. They mostly tackle on the illigal side of immigration arguing that it is unlawful--which it is no rebuttle there-- but struggle to comprehend the 'why' as well the type of people behind illigal immigration. It is not just adults coming into the United States. There are also children and teens coming alone or with distant family. The general incentive to come into the United States is to start over with a clean slate; to have a better life in the 'Land of Opportunity'. To immigrate one has to go through the legal process and paperwork which takes a long time and money. As a result, there is a substantial amount of people that just skip that step and immigrate illegally. 

### Figure One
<img src= "https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/Screen%20Shot%202021-04-04%20at%208.18.13%20PM.png">

Caption: Small pie chart (created in Excel) of the place of origin people come from when immigrating into the United States unlawfully. 


## Motivation
Comming from a family of immigrants, I find it intersting the different points of view that people have against these families. They quickly generalize the issue towards one race without substantial evidence while disregarding that they too were from immigrant families as well. I do not want to sugarcoat the topic rather open a new light to those who are not open minded of these issues that do not have to be entirly political. 

I wanted to analyze all types of immigration data from how many of each race immigrate into the United States, 
what the purpose of these fmailies and how many of them make it to the other side permantly. I mostly want to compare the negative or disagreement points of view of immigration with datasets on how many and why these people come here. 

### Big Question(s)
At what age is it optimal for immigrants to come into the United States illegally?

Supplemental questions: 
 - Why do people immigrate illegally?
 - where do people reside in? why? 


## Reasons of Immigration

I did some external research to get an accurate general idea of why people leave their country of birth and immigrate to the United States. The article [The Most Common Reasons Why People Immigrate to US](https://sandiegoimmigrationlawcenter.com/the-most-common-reasons-why-people-immigrate-to-us/) gives broad reasons and elaborates them. 

In general, the United States has more "freedom" for their citiznes and for the most part have things that are "better" in the sense of financial coverage, success rate, and flexibility: 
- Education: Public schools allow any child to enroll for free with many resources that the child may need to help them learn. 
- Jobs: There a lot of different types of jobs that pay minimum wage to all employees; for the most part, immigrants find jobs in cosntruction or agriculture since that requires less background check so as to not get deported. 
- Lifestyle: Rent a small place or a house to live in for the meantime of financial stability or in the long-run. As well as people not having to live "looking at their backs" for protection. 

Many families sacrifice their old lifestyle to start new and lead a better one for their children to improve by. Since the education standards are higher in the United States than in Mexico, or other Hispanic parts of South America, they have an idea of getting the best education for a career. Another reason that deals with life endangerment is that sometimes in their country of birth there are bad people such as cartels that kill people trying to get more money for their families. As a result these people run away to protect their lives and start a new one in the United States. 

Most of the time, these families consist of different genders and age groups that affect when and how many people migrate into the United States. I took some data and analyzed the different demographics to find the most optimal age of migration based on the main reasons for immigration.

## Data Processing

I used kaggle and the google dataset search engine to loook for relevan data that would help me in complething an analysis. There was a lot of data but for the most part it was not very raw. Most of the data was very clean and short; when reading through the external website where the downloadable data was there as either an xlsx or a csv, the data had been processed already. However, When downloeded, there were still some voncersion errors where the formatting of data had to be fixed. 

### Extra Sheets 

A lot of the excel files contained an extra sheet where it contianed the websites information and summary as well as other links with more information about the data. Since saving the excel file with more than one sheet would affect its conversion to a csv I decided to omit that sheet entirly. In the end there was no effect on the removal of the sheet as the information was also availabe on the website. 

### Formating
 
Although all of the data (whethere they were xlsx or csv) were mostly cleaned, I still had to reformat the cells so that the file conversion was simpler and so that when the data was imported into R studio, it would be easier to create plots for future analyses. 

One main formatting I did to the data was that there were extra rows before the data that included the title of the dataset. This affected how R woul read and organize the data into columns so I simply ommitted it as it was rendundant in the file name. Also, numbers was a huge change in all of the data set files since all data sets included large numbers of millions and thousands, I decided to reduce them two 2 digits and one decimal place. 

For example:
- 200,000,000 = 200.0 (million) 
- 100,500,000 = 100.5 (million)
- 45,300 = 45.3 (thousand) 

In all of the files I made sure to include labs on the plot's axis to ensure that the data was correct after reducing and reformatting. This overall helped to see the data better and understand the overall numbers. 

## Data

After importing the data, I could begin creating plots to better visualize the data and see what the numbers are trying to explain about the people that are immigrating into the United States. Overall, I did basic scatter plots and line graphs to understand easily the large quantitites of numbers. On some occasions I used Tukey's 5 numbers of data summary to help me understand a general idea of the data. 

### Age of Immigrants

In this dataset, I was provided with the values of how many immigrants according to their age are recorded living in the United Stetes after migrating. The ages include from below 16 to people over the age of 55. There is a clear visual cue that more people of prime time age migrate over the United 
States. 

<img src= https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/Age%20of%20Immigrants.png>

caption: Data was plotted in Excel for better visual representation. 

#### Analysis 

It is evident that crossing the border takes a lot of effort from all parties: young, adults, and old people. Based on anecdotal evidence of many people who are in the professional work force as well as family and freinds have explained the "scary and the most memorable experience of my life" where "memorable" was not a good feeling. Overall, it is complicated for people or families to bring along their non-walking children or their frail elders. This is all in the short run of the immigration process. 

In the long-run, immigrants have to think about sustainability; if these families were not financially stable in their country of birth with all of their family members, it would be almost impossible for them to start a new life in the United States with a low income. Many families start by coming in alone or in pairs to make the transition smother and then the rest of the family comes along and joins them. 

There is also in the need for a position and responsibilities the individual that is immigrating have to take in order for a successful transition. A small child would counterintuitively make sense in the best transition as they can get great free edcuation and learn quickly based on the plasticity of their brains to accomidate easily. However, if the child cannot speak english or does not have the proper care, there will be no progress. Usually the child is accompanied by an adult or immigrates to an already-living family in the United States> 

Overall, the highest age range of immigrants are between 25 to 34 alongside 35 to 44. We can assume that this is the most common age where the immigrants can easily find a job and begin working full-time right away to earn income the fastes possible way. Although teens can work in the US from the age of 16, the state would begin to regulate laws of education and that takes away from the possibility of income. But the age range is still relatively higher than the 45 to 54 age group. 

### Marital Status of Immigrants

When immigrants immigrate into the US, they usually come with their families which includes their spouses or partners. Sometimes, they migrate as a single persona and find other people here in the US and get married. Or sometimes these people just stay focused on other things than finding a loved one. 

<img src= https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/Marital%20Status%20of%20immigrants%20.png>

caption: Excel bar (horizontal) graph of the different types of marital status of immigrants in the United States in millions. 

#### Analysis

Based on the graph, there are more people--almost double fro those who are married to non-US citizen-- that are single and have never been married. There are a lot of presumptions from non-immigrant people that immigrants come in and try to find anyone who is a legal US resident to get married and get papers of their own. Although this is not entirly false, the numbers are less exagerated; the number of immigrants who are married to non-US residents is way higher than those who are married to legal US residents. 

The common age to engage in a strong committed relationship with another person is usually above 18 and below 40. Many people engage in relationships beacuse of mutual feeling but also for mutual support. It helps them advance in their new lives as well as to gain better financial stability. 

### Number of Immigrants (demographics)

The images below are taken from R studio within my markdown file where I created a matrices scatterplot of the different columns and also used Tukey's 5 number summary to better understand and see the data. 

<img src= https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/number%20of%20types%20of%20immigrants%20.png>

caption: In R, since the matrices scatter plot includes a square pannel figure, I ommited the bottom half as it is redundant. I also rounded the numbers to millions for better visuals and included the column of years. 

There is a very clear constant increaseo of naturalized citizens (which are immigrants who are legally converted to US citizens after time and legal paperwork) over the course of 14 years. 

<img src= https://github.com/greciasantana/Pinpoints-of-immigration/blob/main/Immigraiton%20Population%20summary.png>

caption: Summary of the data using Tukey’s 5 numbers to get a general idea of the datset. Under the column of unaothorized immigrants, there are less people based on average but we have to take into account that there was lack of data in some rows and also assume that because so many come into the US illegally, there are no record of those people. 

#### Analysis

Evidently there are so many people that migrate into the United States. Based on the visuals, both legal and unauthorized immigrants are increasing by the million over the a decade. People do try to abide the law but because there are so many “in line” it is difficult to wait what takes years and months to process without opportunities and just come in illegally. In all graphs the data decreases unexpectedly and that can be because no data was recorded.

### State of Residency

There is also the need to understand where in the overall country of the United States people choose to live in. The data only included the top states that immigratn families choose as their state of residency but I felt that a simple country map of the US with color code of density would represen the datat better. 

<img src= https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/State%20of%20residency%20image.png>

caption: Excel US country map density graph of the data to show the most populated areas that immigrant families chose to reside according to state by millions. 

#### Analysis

In this density graph shows by blue color shades, the number of immigrants that reside in the top most populated states. There is a lot of darkness on the states that are closests to the border of the United States and Mexico. Because of the difficulties to cross the border illegaly, many families simplify their voyage to the closests states possible. Washingotn and other parts of the north are also lightly dense in population.

In the article [The 10 Best States in America](https://www.usnews.com/news/best-states/slideshows/10-best-states-in-america?slide=11) shows that Washington is one of the best states in America to live in with external infomration as to why. But in summary of common knowledge, Washington has the best: 
- Education 
- Low crime rate levels
- Weather conditions (home to the Hanford Nuclear Site becasue of no natural disasters)

### Age and Genders of Immigrants

Similar to the bar graph about the age groups that immigrate into the US, this graph includes the genders of these immigrants with similar age grouping and the axis values are in millions. 

<img src= https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/Ages%3Agenders%20of%20imigrants.png>

caption: Image scatter (x,y) plot from R where I compared the age grouups of female and male immigrants. 

#### Analysis

The age of males and females is almost correlated in the idea that gender is not a big factor in who immigrates into the United States. More males come in than females but only by a small difference. This can be because of the difficulty of migrating across the border as well as traditionally, families test out by having the male figure in the household migrate into the US before having the rest of the family move in.

## Conclusions

Overall and according to the data, the optimal age for immigration to a new country [United States] is around young adult to middle age adults. These people have the capacity to get across the border--legally or unauthorized-- and a start a new life for vast improvement. They are able to find a job and work for their income and sustainablity from where they can send their savings to their country of birth where its value is much higher. This allows for a more smoothe segue of change in lifestyle as well as being able to provide for themseles and family. 

## References

Immigration Population (dataset): https://usafacts.org/data/topics/people-society/immigration/immigration-and-immigration-enforcement/immigrants/

Nisanth. "International Migration Data (dataset)". https://www.kaggle.com/nishanthsalian/international-migration-data-2000-2020?select=migration_2020.csv

Statistica Research Department. "Estimated number of Illegal Immigrants in the United States(statistics)". https://www.statista.com/statistics/257783/estimated-number-of-illegal-immigrants-in-the-us-by-age-and-sex/

Fabio, Elizabeth. "Immigration Deported". https://www.kaggle.com/ekayfabio/immigration-deported

Golchin, Ali. "The Most Common Reasons Why People Immigrate to US" https://sandiegoimmigrationlawcenter.com/the-most-common-reasons-why-people-immigrate-to-us/

Adame Pineda, Minchap. _Personal Experience_. 1982-1990.

Davis, Elliot. "The 10 Best States in America". https://www.usnews.com/news/best-states/slideshows/10-best-states-in-america?slide=11
