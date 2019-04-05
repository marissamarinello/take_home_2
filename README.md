#THA3

#Data used for THA3:
* syrianpop_jordan.xlsx
* syrianpop_lebanon.xlsx
* syrianpop_turkey.xlsx
* ftsdata.xlsx
* major_polittical_violence.xlsx


# THA2

# Information About This Folder:

* This folder contains a Colab notebok with code for reading files in pandas, extracting specific columns and observations, listing headings, creating new dataframes, and merging data.

* A discription of each data source is provided in this README.

* Links are provided to access the CSV and Excel files used for each source. 

## About data sources:
The following data is from three different sources: the Human Development Index from the United Nations, the World Values Survey, and the World Bank. This data is accessible online via the links and directions provided.
 
## HDI
The Human Development Index data is compiled ever year and ranks countries from around the world. Countries area assessed on the main demensions of health, knowledge, and standard of living. There are multiple subcategories within each category to better asses each country. Countries that have a HDI score closer to 1 means they are more developed. Countries are categorized by score in the broad categories of "Very High Human Development," "High Human Development," "Medium Human Development," and "Low Human Development." 

The data used in the colab notebook is from the complete HDI 2018 data, and Jordan for 2018

* **A composite of all HDI 2018 scores/data is found [here](http://hdr.undp.org/en/composite/HDI).**


* **Jordan data is found [here](http://hdr.undp.org/en/countries/profiles/JOR).**

* All of the data provided is in CSV form. 


## World Values Survey
The World Values Survey asks individuals questions that assess the state of a given country from a more socio-cultural perspective that represents the actual sentiments of the population towards a given topic. The questions vary some from year to year, but a record of the questions asked is provided. 

Data is collected over time in a series of waves. As such, this data will likely be used in research to analyze changes over time. 

Data for Jordan is analyzed in the most recent wave, Wave 6 which is from 2010-2014 and comes has data for Jordan for 2014. Also used is data from Wave 5 which is 2005-2009 and has Jordan data for 2007.

*Important Notes:* The links will take you to the WVS page. On the right hand side, you will be prompted to select a country. 
* Type in "Jordan" in the search box, and when you see it appear click it rather than pressing enter. 
* Once you are on the Jordan profile page, scroll to the bottom and the different data sets are provided. 
* The data set used in the code notebook is the first one listed that has "text_text" in the title. 
* These are excel files.

**Wave 6 data is available [here](http://www.worldvaluessurvey.org/WVSDocumentationWV6.jsp).**

**Wave 5 data is available [here](http://www.worldvaluessurvey.org/WVSDocumentationWV5.jsp).**


*Data from the Human Development Index and the World Values Survey is particularly useful because it is gathered over time, and generally utilizes the same variables - so they are excellent for tracking changes in a population over time.*

## World Bank

The World Bank provides data on their poverty headcount ration (% of population) for 2011. Each country is listed along with its region and its income level. This is of use to see how levels of income correlate with the above HDI and WVS data. 

**The data can be downloaded [here](https://data.worldbank.org/indicator/SI.POV.DDAY?end=2015&locations=1W&name_desc=false&start=1981&view=chart).**

*Important Note:* The data set used the CSV file. It will download in a zip file. 
* Select the file that in the zip folder titled "Metadata_Country_API_SI.POV.DDAY_DS2_en_csv_v2_10474275.csv" 
* Rename it as "WorldBank".



