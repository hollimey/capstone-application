# Capstone Project

**Created by Holli Meyers**, at the University of Washington.

Information architecture project inspired by Apple and Samsungs mobile weather app, which provide no information on the oceans for users residing in or visiting coastal cities. <br/><br/>


## Background

The effects of climate change are to only increase. Coupled with the impacts of other human caused issues, our environment is to continue facing extreme and variable patterns that will be life altering. Thus, it’s important the public has easily accessible access to the real-time data that’s gathered globally to stay informed and allow them to plan accordingly to their current or sought out location.

Real-time environmental data is collected from a variety of different sources and locations, only some of which can actually be easily found and understood by the general public. Yet, none provide a consolidated overview of the information. This is especially true for oceanic data, which at this time has yet to be fully integrated into traditional weather applications. Navigating between fragmented data sources can be difficult for the average user. It requires time and patience finding sites that not only hold the correct information they seek in relation to the desired location, but also an intuitive format that makes sense and doesn’t require special downloads or software.

As a result, this project organized, structured, and labeled traditional weather information from atmospheric resources and integrated new data from oceanic resources to centralize the information for users. To accommodate the fragmented data across government agencies, universities, research institutions, and other organizations, the platform will use schema mapping to draw data from its various structured information sources. Consequently, presenting the information systems into a unified, accessible format with features that allow users to quickly and easily, access an enhanced weather overview for their desired area.

The information presented in this project can be used in fields like web design, app development, user experience (UX) design, and content strategy.


### Current Applications

<img align="right" width="505" height="432" alt="Image" src="https://github.com/user-attachments/assets/4586b5aa-3417-4062-8d67-077be8ddb54e" />
The Weather Channel provides hourly, 5-day, and 10-day atmospheric forecasts. With more specialized readings of flu risk predictions from the CDC like influenza, allergy tracking of pollen density in the air, and air quality assessments of pollutions related to ozone, carbon monoxide, nitrogen dioxide, particulate matter less than 10 microns, particulate matter less than 2.5 microns, and sulfur dioxide. The Weather Channel also offers a radar map to visualize rain, snow, and fog, and a search feature to find locations globally by city (“Weather Forecast and Conditions,” 2025). <br/><br/>

AccuWeather
<img align="right" width="1416" height="1525" alt="Image" src="https://github.com/user-attachments/assets/58115b0e-3a15-46a6-bc4f-8ee1f9586946" />
AccuWeather provides similar information plus a health and activity feature, a global severe weather map, and a few live coverage weather notifications on the top of the site’s navigation bar. The health and activity feature allows you to view a bar graph of how the weather will impact certain health conditions like arthritis, migraines, asthma, and sinus pressure. As well as, monitoring pest levels like mosquitos, garden care like mowing and composting, and other outdoor activities like fishing and pool days which give readings of cloud cover, rain, UV index, and wind (“Beach & Pool,” 2025). <br/><br/>

The National Oceanic and Atmospheric Administration (NOAA) 
<img align="right" width="1562" height="1400" alt="Image" src="https://github.com/user-attachments/assets/3a945041-fbf5-4b49-8c23-090c5211c32b" />
NOAA has a National Weather Service site that is more simplified but less intuitive than the other applications. It offers a U.S. image loop radar map of tornados, severe thunderstorms, flash floods, special marine, and snow squall across the country. Additionally, it includes a static U.S. map of 30 weather warnings and advisories that could be showcased via different colors on the map (“National Weather Service,” 2025). <br/><br/>

Web application Earth
<img align="right" width="1393" height="1108" alt="Image" src="https://github.com/user-attachments/assets/3cdaa004-ac53-4097-b815-6292e5a70c6f" />
Earth provides a non-traditional layout. The site seems more intuitive given its clean user interface which lacks any navigation bar or featured news articles seen in the other popular sites provided. However, it may be less legible for the general public who aren’t familiar with certain data points like what the speed of an ocean current is and what dictates it as normal or not. While Earth allows users to navigate to different areas, it doesn’t provide a location search feature to ensure an accurate pinpoint of an area (“Earth,” 2025). 



## Overview
The repository contains a new portable information structure. <br/>

**Data Sources:** <br/>
Ocean buoy data map, list, guide, and description - https://www.ndbc.noaa.gov/ / https://www.ndbc.noaa.gov/data/latest_obs/latest_obs.txt / https://www.ndbc.noaa.gov/docs/ndbc_web_data_guide.pdf / https://www.ndbc.noaa.gov/faq/measdes.shtml <br/>

**TBD Data Integration Sources:** <br/>
Real-time data file list - https://www.ndbc.noaa.gov/data/realtime2/ <br/>
Global monitoring data map - https://viz.pmel.noaa.gov/osmc/?color_by=platform_type&platform_code=PTAW1 <br/>
US tide and current data - https://tidesandcurrents.noaa.gov/map/

## Methods
1. Download a code editor like Visual Studio (VS) Code to set up a development environment.
2. Download the files in the repository to a designated project folder on your computer.
3. Open the folder in VS Code.
4. Run the code to view the web application.

### TBD Methods -- IGNORE
+ Install React: https://nodejs.org/en/download
+ Open VS Code and navigate to 'View' then 'Terminal'.
+ Lauch the Command Prompt terminal:<br/>
<pre><code>*C:\Users\bmo\ocean_app>* **npx create-react-app my-app**<br/>
Need to install the following packages:<br/>
create-react-app@5.1.0<br/>
Ok to proceed? (y) **y**
  </code></pre>
+ *C:\Users\bmo\ocean_app>* **npm install @mui/material @mui/icons-material @mui/lab @emotion/react @emotion/styled @react-google-maps/api google-map-react @mui/styles**
+ *C:\Users\bmo\ocean_app>* **npm start**
+ 
