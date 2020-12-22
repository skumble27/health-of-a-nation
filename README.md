# project-2 - Data Visualisation

**Sumukh Kumble, Jia Na (Gina) and Sean Pei**

### Project Proposal

Given that the world is currently focussed on the events pertaining to COVID-19, there are many issues that are effecting many countries in different areas such as Agriculture, Environment and Healthcare (non-COVID-19 related). Whilst there are a number of interactive Dashboards available relating to Covid-19 rates in different countries and their regions, the purpose of this Dashboard is to provide users with information relating to other issues health, agricultural and environmental issues so that individuals can obtain the latest information related to various countries.  

**Project Objectives**

***Data Extraction***

The project will involve utilising various technologies in order to launch a web based application to visualise the data. The first step involves **Extraction-Transformation-Loading** **(ETL)** where CSV based datasets will be sourced from different organisations, transformed using Pandas Modules in Python and subsequently loaded onto a PostgresSQL server.

***Website development***

Utilising HTML and CSS languages, a website will then be developed in which to provide all the required data visuals that are related to Healthcare, Agriculture and the Environment. Users will have the option of selecting different industries of interest in which to view the statistics relating to each country. 

***Interactive Data Dashboard***

With the use of the JavaScript Language, an interactive web dashboard will then be developed wherein users will have the option of selecting a country of interest and then viewing the information pertaining to those regions. In this manner, users will have the opportunity to get a quick glimpse of the issues relating to various countries apart from the main focus on Covid-19. 

***Launching the website***

The website will be launched using the main Python Flask module wherein the PostreSQL database will be accessed through SQL Alchemy, converted into a json format that will then be loaded onto the website as an API. Once this has occurred, the users will be able to select the country of their choice, which in turn, will result in accessing the local SQL database to present the data onto the web dashboard. 

