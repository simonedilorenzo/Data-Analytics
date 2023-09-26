# Market Research: Mechanical Watches
In this project, I developed a hypothetical market research report for TradWatches, a hypothetical company in the traditional watches market that wants to understand whether smartwatches may threaten their market share. In the information, I tried to understand whether there is still room for “old-style” watches, whether there is competition between the old-style and the smartwatches, and between mechanical and quartz watches. 

## Goal of the Report
The study's primary goal is to determine which characteristics and attributes influence traditional watches’ perceptions and smart watches’ perceptions. Then, I tried to establish whether these two types of watches are competitors in the same market. Furthermore, To identify possible customer segments, I attempted to highlight similarities and differences in socio-demographic characteristics and lifestyles among consumers of the various types of watches under question.

## Techniques used
To develop this project, I used R and Rstudio as IDE. 

To understand what characteristics of the watched impacted their perception more, I developed a **multiple regression model** using responses to question 4 (V8-V40), where a higher score implies a better perception. 
Then, I tried to understand if each characteristic was independent or could be reduced to common factors. To do so, I developed a **factor analysis** to group correlated characteristics under a common variable. Then, I used these new factors in a **cluster analysis** with socio-demographic variables to segment the market. This way, I could evidence whether customers could be split into different segments based on their preference for specific watches' characteristics. 

Another question I have tried to answer is if the characteristics and perceptions of watches affect the willingness to buy from customers. To do so, I developed a **logistic regression model** to quantify the increase in willingness to buy for a one-point increase in perception. 


## Sampling Description
The group was gathered from the members of a watch forum. The survey was administered online and collected 237 responses. The questionnaire comprised 16 questions, mainly divided into a first section about watch characteristics, a second section about socio-demographic characteristics, a question about how respondents came in possession of their watches, and questions about willingness to buy, to account for any remaining market share.

# Files Description
* Watches questionaire.pdf: includes the pdf of the questionnaire that was provided to the sample;
* Watches.txt: is a text file with the complete datasets;
* Watches.xlsx: is an Excel file with the complete datasets and the labels for the coded variables;
* Watches_Case Study_Code.Rmd is the RMarkdown file of the report;
* Watches_Case_Study_Report.pdf is the final report knitted from RStudio.
