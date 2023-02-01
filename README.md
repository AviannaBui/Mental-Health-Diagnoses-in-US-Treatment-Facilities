# Mental Health Diagnoses and Substance Use Characteristics of Clients in US Mental Health Treatment Facilities
###### Author: Avianna Bui & Kaylee Do 

## Note on Running the .rmd File
Due to the large data set size, I am currently unable to upload the Mental Health Dataset we use on github. To run the file, users should download the SPSS version of our data set from this link, https://www.datafiles.samhsa.gov/dataset/mental-health-client-level-data-2019-mh-cld-2019-ds0001, and save it in the same local repository as the .rmd file under the name "mhcld-2019-sav"

## Data Context 
This project draws from the Mental Health Client-Level Data (MH-CLD) in 2019 by the U.S. Department of Health and Human Services. With over 6 millions observations, this data set provides information on mental health diagnosis, treatment services, demographic of patients as well as substance use characteristics. For the specific purpose of our analysis, we only keeps a subset of variables from the original MH-CLD, including variables on mental health diagnosis and number of diagnosis, substance use, age, educational level, employment levels, living situation, race, gender and veteran status. In addition, we re-categorized the substance use disorders variable into 4 main categories: alcohol use, cocaine use, opioid use and cannabis use disorders. Within the alcohol use category, we included alcohol abuse, alcohol dependency, alcohol-related disorders and alcohol intoxication. The other three variables include disorders regarding substance use dependence and abuse.

The second data set we use is the 2019 Census US Population Data By State dataset from Kaggle. This population data derives from the 2019 US Census, collected by the US Census Bureau, along with latitude and longitude data for each states' capital city. We combine this data set with the US state variable in the Mental Health Client-Level Data to explore the percentage of clients with substance use disorders per state population.  

## Research Questions
Our research topic centers on the relationship between substance use disorders, mental health problems, and demographics within the US. More specifically, our group aims to explore whether there is a particular type of substance misuse that bears a higher correlation with a specific diagnosis of mental illness, and whether there are any trends or patterns within certain demographics or regions of those with substance use disorders

## Limitations
Regarding the data analysis, while a client might have multiple mental illnesses, we only account for the first mental health diagnoses in our graph. As a result, there would be disparity between the numbers displayed on the graphs and the real statistics. We also either combined multiple variables together in the case of substance use disorders, or filtered out many mental health diagnoses from the original data set, so the graphs are limited in their capability to exhibit the full picture of mental health and substance use disorders in the US.

Due to the fact that there are some states information missing from the Mental Health Client-Level Data, our map visualization of the rate of cannabis use disorder per state population remains incomplete. We hope to be be able to perform a more comprehensive analysis regarding this research question if further data is available.

In addition, since the scope of the data set is limited within the data recorded in mental health facilities in the US in 2019, it is not possible to examine the correlation between substance use disorders, mental health problems, and demographics over time or across countries. We also acknowledge the limitations of this data set in categorizing certain variables e.g. gender, which only composes of three classifications Male, Female, and Missing, without including other gender identities. As a result, we are aware that the data might facilitate biases and potential harm to marginalized communities

## Appendix
Substance Abuse and Mental Health Services Administration, Center for Behavioral Health Statistics and Quality. Mental Health Client-Level Data 2019. Rockville, MD: SAMHSA, 2022. 
https://www.datafiles.samhsa.gov/dataset/mental-health-client-level-data-2019-mh-cld-2019-ds0001

Peretz Cohen. 2019 Census US Population Data By State. Adapted from US Census Bureau, State Population Totals: 2010-2019 and US State Capital location dataset on Jasper Debie's github. 
https://www.kaggle.com/datasets/peretzcohen/2019-census-us-population-data-by-state?resource=download

Zagorski, N. (2017). Many Prescription Opioids Go to Adults With Depression, Anxiety. Psychiatric News.
https://psychnews.psychiatryonline.org/doi/10.1176/appi.pn.2017.8a13

Winklbaur, B., Ebner, N., Sachs, G., Thau, K., & Fischer, G. (2006). Substance abuse in patients with schizophrenia. Dialogues in clinical neuroscience, 8(1), 37–43.
https://doi.org/10.31887/DCNS.2006.8.1/bwinklbaur

U.S. Department of Health and Human Services. (2022, March 22). Prescription Opioids and Heroin Research Report. National Institutes of Health. Retrieved December 7, 2022. 
https://nida.nih.gov/publications/drugfacts/prescription-opioids
