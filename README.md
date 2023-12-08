# MIST 4610 Project 2

## Group Information
Class Section: 
- 9:35am - CRN 20242
Members:
- Aden Dragulescu [@adendrag](https://github.com/adendrag)
- Adam Parent-Herzog [@parentherzog](https://github.com/parentherzog)

## Dataset Overview
 The dataset that we selected to analyze for this project details real estate sales completed by the United States government between the years 2001 and 2020. We obtained this from [data.gov](https://data.gov), a website that provides public access to data and information collected by the government. This dataset contains a wide array of attributes, with each having a specific data type for identification and representation within a database containing 14 columns and approximately 1 million rows. Some of the main attributes of the dataset include serial number, listing year, date, address, assessed value, sale amount, sales ratio, property type, residential type, and more. Serial number and list year are integer while sales ratio is double. Date is of type date (format mm/dd/yyyy), and exact coordinate location is the type geography (coordinates). The rest of the data is held in strings. This dataset contains a plethora of information that will allow us to gain a better understanding of the government's real estate transactions and their implications on the economy’s real estate market.
## Question 1
- Which property types have had the most property sales since the beginning of this dataset? How do the average sales ratios for these property types compare year-over-year?

\
<img width="1131" alt="Screenshot 2023-12-07 at 7 42 11 AM" src="https://github.com/adendrag/MIST4610Project2/assets/25353210/5ccabbfb-e842-4087-89a3-d5d1383dd790">
<img width="1137" alt="Screenshot 2023-12-07 at 7 43 00 AM" src="https://github.com/adendrag/MIST4610Project2/assets/25353210/39baafc4-5916-429d-a6ce-37c2ad7f7df2">

\
This question poses a need for analysis because it looks at how the sales prices of government-owned properties compare to their estimated values. By checking the sales ratios for the most commonly sold property types from 2001 to 2021, we can see if the government tends to sell their properties for more or less than their currently estimated values and if/how this trend has changed over time. This information is helpful to the people who internally manage government-owned real estate and for the policymakers who decide on funding/selling these properties. This question also helps researchers and people interested in the real estate market understand how the government's selling patterns could affect or impact the economy. For example, if the government usually sells houses for more than their estimated value, this could tell us something about the housing market during that time. Understanding these trends can help us all make better informed decisions when buying or selling similar properties in the future.

## Question 2
- In which year did the highest number of real estate sales occur in the dataset of U.S. government-owned properties? And what was the predominant property type sold in that year?

\
<img width="1137" alt="Screenshot 2023-12-07 at 7 43 13 AM" src="https://github.com/adendrag/MIST4610Project2/assets/25353210/cb009d96-2160-4a79-8e24-6210dcf881af">
<img width="1136" alt="Screenshot 2023-12-07 at 7 43 32 AM" src="https://github.com/adendrag/MIST4610Project2/assets/25353210/df58bdd6-0f4e-4e8c-b9f2-e0f03dbdf451">

\
This question is important because it can help us understand trends in how/why/when the US government sells properties as well as what kind of properties, in specific, are being sold. By figuring out which year(s) had the most sales, and the type of properties that were being sold (residential, commercial, etc), we can begin to get a good idea of how the government's selling habits change over time. Information like this is really useful for people who manage the government's property, as well as for those who make policies about these properties. They can use this information to make better decisions in the future about when and what to sell. This question is also great for researchers who are interested in how the government's actions affect the overall real estate market, such as stock traders or economists. By knowing when the government sells the most and what they sell, these researchers can understand better how big of a role the government plays in the country’s real estate market. This can help everyone plan better for times when we face economic difficulty or want to predict when the government may plan on selling a lot of properties.
