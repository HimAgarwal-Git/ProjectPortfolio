![image](https://github.com/HimAgarwal-Git/ProjectPortfolio/assets/146741762/b6c89e1a-7192-4bd1-bd55-5be0a1ae08c7)
# ABOUT THE DATA?🙋🏻‍♂️
Survey Monkey is an online survey analysis company that collects data and analyzes it. I found this data and I would like to thank Survey Monkey for providing the RAW file to make a great use case out of it. The data contained 198 rows and 100 columns approximately nearly 17000 entries. The data was in a ![*Wide Data*](        ) format.

# Business Objective
The data was to be converted into ![*Long data*](  ) from **Wide data**. The analyst was free to use technology that suited him. There were also many interstices and blank values throughout the data which were to be dealt with without losing the integrity of data. 

# Stack Used 💻⌨️
- Excel
- Python_Pandas
- PowerBI

# The Analytics Behind 📈
- The data was read and it was defined how to work across the project
- I first used Excel to clear out the Top headings and combust them as one
  
  Original:![image](https://github.com/HimAgarwal-Git/ProjectPortfolio/assets/146741762/e2238e22-5be4-4822-9d96-be604a8178b2)
  Converted:![image](https://github.com/HimAgarwal-Git/ProjectPortfolio/assets/146741762/c9b37820-4e0b-4b87-83fd-4ceb6bf93c6f)

- The format required was compared and the use of the Python library Pandas was required
   Required Format:![image](https://github.com/HimAgarwal-Git/ProjectPortfolio/assets/146741762/bee215ad-7313-4a76-bf8a-7c0038908720)

**-_ Pandas- Basic exploration done followed by the `melt` function through which the columns were melted down into observations according to the demographic attributes._**
- Join was performed to combine the data 
- Analysis was done which gained insight into the trends in the population. 
 -How many answered the same? (Total number of unique answers)
 -Total number of respondents who answered a particular question. 
 - Scaling each response to its parent question
 -  [Python Script Here](./DATA_MANIPULATION.ipynb)

# Improvisations
I further explored the data. I remember using Google Forms and how forms presented a summary of the data with some basic charts. I gained inspiration to provide some real analysis and use PowerBi to fetch the purpose:
- Analyzed the total number of Blank responses per question
- Analyzed the respondent's background and provided tooltips for an easier peek into the composition of the population.
The whole visualization was done with the motive to provide greater insight and help the viewer understand the data much better than viewing it on Google Forms or any other platform for say.
  [Visualizations Here](./Dashboard_GoogleAnalysis.pdf)
  [PDF file](./Dashboard_GoogleAnalysis.pdf)

# Output
### Raw File 
[SurveyMonkeyOutput_RAWDATA.xlsx](https://github.com/HimAgarwal-Git/ProjectPortfolio/blob/main/Survey_Monkey/SurveyMonkeyOutput_RawDATA.xlsx)

![image](https://github.com/HimAgarwal-Git/ProjectPortfolio/assets/146741762/0c707a8c-1b47-45b5-8b04-f47372d57c50)



### Cleaned File 
[Survey_Monkey/Data Survey Monkey Output Final.xlsx](https://github.com/HimAgarwal-Git/ProjectPortfolio/blob/main/Survey_Monkey/Data%20Survey%20Monkey%20Output%20Final.xlsx)

![image](https://github.com/HimAgarwal-Git/ProjectPortfolio/assets/146741762/29a07964-8d5c-40ba-a0b5-9d7e6d46089d)

