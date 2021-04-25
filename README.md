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

After plotting and annalzying the data 

### Age of Immigrants
<img src= https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/Age%20of%20Immigrants.png>



### Marital Status of Immigrants
<img src= https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/Marital%20Status%20of%20immigrants%20.png>

### Number of Immigrants (demographics)
<img src= https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/number%20of%20types%20of%20immigrants%20.png>

### State of Residency
<img src= https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/State%20of%20residency%20image.png>

### Age and Genders of Immigrants

<img src= https://raw.githubusercontent.com/greciasantana/Pinpoints-of-immigration/main/Ages%3Agenders%20of%20imigrants.png>



## Analysis

## Conclusions

