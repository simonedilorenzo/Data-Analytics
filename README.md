# Market Research: Mechanical Watches
In this project I developed a hypothetical market reasearch report for TradWatches, an hypothetical company in the traditional watches marekt, that want to understand whether smartwatches may pose a threat to their market share. In the report I tried to understand whether there is still room for “old-style” watches and whether there is competition between the old-style and the smartwatches, and/or between mechanical and quartz watches. 

## Goal of the Report
The primary goal of the study is to determine which characteristics and attributes influence traditional watches’ perceptions, as well as smart watches’ perceptions. Then I tried to establish whether these two types of watches are actually competitors on the same market. Furthermore, In order to identify possible customer segments I attempted to highlight similarities and differences in terms of socio-demographic characteristics and lifestyle among consumers of the various types of watches under question.

## Techniques used
In order to develop this project I used R and Rstudio as IDE. 

To understand what caracteristics of the watched impacted more their perception I developed a **multiple regression model** using responses to question 4 (V8-V40), where an higher score implies a better perception. 
Then I tried to understand if each caracteristics were independent or if they could be reduced to common factors. To do so I developed a **factor analysis** in order to group correlted carachteristics under a common variable. Then I used this new factors in a **cluster analysis** with socio-demographic variables to try to segment the market. This way I could evidence whether customers could be splitted in different segments based on their preference on specific watches' carachteristics. 

Anotehr question I have tried to answer is if characterisJcs and percepJon of watches affect the willingness to buy of customers. To do so I developed a **logistic regression model** in order to quantify the increase in willingness to buy for a one point increase in perception. 


## Sampling Description
The group was gathered from the members of a watch forum. The survey was administered online and collected 237 responses. The questionnaire was composed of 16 questions, mainly divided into a first section about watches characteristics, a second section about socio-demographic characteristics, a question about how respondents came in possession of their watches, and questions about willingness to buy, to account for any remaining market share.
