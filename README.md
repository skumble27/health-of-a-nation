# project-2 - Health of a Nation

![Image1](https://raw.githubusercontent.com/skumble27/project-2/main/images/nationshealth.jpg)

**Sumukh Kumble, Jia Na (Gina) and Sean Pei**

### Project Proposal

Given that the world is currently focussed on the events pertaining to COVID-19, there are many issues that are effecting many countries in different areas such as Agriculture, Environment and Healthcare (non-COVID-19 related). Whilst there are a number of interactive Dashboards available relating to Covid-19 rates in different countries and their regions, the purpose of this Dashboard is to provide users with information relating to other matters relating to non-Covid-19 related issues such as health, agricultural and the environment so that individuals can obtain the latest information related to various countries.  

**Dashboard Design**

***Data Extraction***

The datasets were obtained from a number of different sources that was accessible in a CSV format. For all health related datasets pertaining to the human immune deficiency virus (HIV), obesity and mental health were all obtained from "Our World in Data". 

![Screenshot1](https://raw.githubusercontent.com/skumble27/project-2/main/images/Screenshot5.gif)

Datasets relating to agricultural output were obtained from the Food and Agriculture Organisation of the United Nations. 

![Screenshot2](https://raw.githubusercontent.com/skumble27/project-2/main/images/Screenshot6.gif)

In order to build the interactive maps on the webdashboard, a customised global polygon Geojson dataset was built and deployed onto the website (source:https://geojson-maps.ash.ms/)

![Screenshot3](https://raw.githubusercontent.com/skumble27/project-2/main/images/Screenshot9.gif)

The Datasets were subsequently transformed, cleaned and edited and loaded into the Heroku PostgreSQL cloud database, which in turn, can be accessed with the JavaScript applications which will be discussed later in this document. 

***Website development***

The HTML and CSS scripts were utilised in order to build and format the website for subsequent user interactivity. The animated heading of the website, as seen in the image below, was constructed using the **anime js** library for visual appeal. 

![Screenshot4](https://raw.githubusercontent.com/skumble27/project-2/main/images/Screenshot4.gif)

The Interactive map was developed utilising the Leaflet JavaScript library where users have the option to click on a country to obtain information on that nations performance in key areas. Continents and regions have been colour coded accordingly.

![ScreenShot1](https://raw.githubusercontent.com/skumble27/project-2/main/images/Screenshot10.gif)

***Interactive Data Dashboard***

With the use of the JavaScript Language, an interactive web dashboard was developed wherein users have the option of selecting a country of interest and then viewing the information pertaining to those regions. In this manner, users can get a quick glimpse of the issues relating to various countries apart from the primary focus that has been Covid-19. 

***Launching the website***

The web-based application was developed, compiled and launched through the Heroku Development Portal. In a streamlined process, the previously cleaned datasets relating to each country were loaded onto the Heroku PostgreSQL cloud database.

Through the Python Flask application, the Heroku PostgreSQL database was accessed, rendered into a Json object and dumped onto the web server for subsequent access through the files. 



The website will be launched using the main Python Flask module wherein the PostreSQL database will be accessed through SQL Alchemy, converted into a json format that will then be loaded onto the website as an API. Once this has occurred, the users will be able to select the country of their choice, which in turn, will result in accessing the local SQL database to present the data onto the web dashboard. 

