# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 5: Client Project

### Overview

We've organized for you to complete a client project. This is a great opportunity for you to be exposed to a **real organization** doing **real work** with **real data**.

**The Organization**:

- [New Light Technologies](https://newlighttechnologies.com/) is a small, award-winning organization based in Washington, D.C. that provides solutions to government, commercial, and non-profit clients. NLT is a team of dedicated technologists, scientists, engineers, designers, and strategists working on some of the most interesting, challenging, and important assignments in the world, ranging from disaster response to enabling growing telecommunications networks to providing healthcare to Americans. Some of the organizations they work with include FEMA (the Federal Emergency Management Agency), USAID (the United States Agency for International Development), the U.S. Census Bureau, and The World Bank.

- [Ran Goldblatt](https://newlighttechnologies.com/staff/ran-goldblatt/), our contact with NLT, is a remote sensing scientist and senior consultant. He has a strong background in geographic information systems (GIS) and leverages this knowledge when solving problems facing various agencies.

**The Work**:

For this project, you will be doing work that focuses on:
- preparing for emergencies,
- rapidly responding to emergencies, and/or
- estimating the economic impact of disasters.

The goal is for you to leverage your skills to help solve real-world problems. NLT has identified twelve potential prompts of value to them. You may pick one and attempt to solve it. Alternatively, if you would like to edit the problem slightly (for example, picking a different data source) or combine multiple prompts together, you may do that as well!

1. Leveraging Social Media to Map Disasters.
2. Leveraging News and Media for Situational Awareness.
3. Optimizing Evacuation Routes using Real-Time Traffic Information.
4. Using Google Street View to retrieve (pre-event) photos of structures.
5. Using news outlets and/or social media to identify areas/neighborhoods with power outages.
6. Using live police radio reports for real time identification of people needing assistance.
7. Using Indeed or Glassdoor platforms together with number and type of affected businesses to estimate the expected economic loss (wages) due to a disaster.
8. Crowdsourcing Damage Photos
9. Finding Tents and Other Emergency Housing Through Exploitation of Satellite Imagery
10. Updating Shelter Status
11. Identifying Misinformation in Disaster-Related Social Media Posts
12. Extracting Flood Depths from Imagery
13. Improve Slum Area Identification through Real-Estate Data
14. Sentiment Analysis of COVID-19 Social Media Posts
15. Mapping Hotspots of COVID-19 Cases
16. Identifying Areas At Risk for COVID-19 and Other Natural Disasters
17. Mapping Available Commodities During the COVID-19 Pandemic
18. Chicago Case Study: Hotel Availability for Quarantine

**The Data**:

For this project, you aren't given any data! You are given *possible* sources for data, but don't feel limited by this. Be creative in where and how you gather data!
- Is there data easily downloadable into a .csv or .json file?
- Can you get access to a database of data?
- Can you access an API?
- Do you need to build a scraper?
Be sure to consider any legal, regulatory, and ethical issues when accessing data!

As with the Reddit project, it's important to identify source(s) for your data early and gather as soon as possible, as this might be a large bottleneck toward completing a project.

**This is where you come in**:

For the next three weeks, our class will tackle various projects related to emergency preparedness and economic analysis. On **Friday, June 19**, we'll present our findings and deliver:
1. A clean GitHub repo containing our reproducible results and analysis.
2. A real-world demonstration of the product.
3. Any documentation for running the code.

> This is an exciting opportunity to identify and solve a problem relevant to the real world problems. Using your data science skills in this practical, _pro bono_ capacity reflects well on you and gives you a great story as you embark on interviews! (The fact that we'll be using open data also gives you free reign to publicly publish your findings and to freely discuss this in interviews.)

### Problem Summaries

**Problem 1: Leveraging Social Media to Map Disasters**

*Problem Statement:*
- When responding to disasters (e.g. damage and casualties caused by hurricanes, tornadoes, floods, fires etc.), it is critical to map and identify locations of survivors needing assistance.
- Currently, satellite and aerial imagery, ground surveys and modeled hazard data are the primary tools used to assess damage and to identify areas where survivors may need assistance.
- Often, survivors will resort to using social media to call for help or share information about their location and the current situation. In many cases they will also include useful images showing water levels, amount of damage etc. which could indicate on the intensity of the disaster.
- This information can be leveraged to track the event in real-time. Social media can help identify isolated communities at risk, locations of survivors and areas where assistance teams should be sent for search and rescue, levels of damage, help map depths of flooding, identify where additional imagery/information needs to be collected and plan when and where resources should be allocated.
- This project will discover new ways to leverage social media (including from Twitter, Facebook, Instagram, Snapchat, or others) to supplement current tools and methodologies used when responding to disasters.
- The tools developed in this project will also help leverage social media to locate hot spots of where people are needing assistance, using, for example, geolocated posts/tweets containing keywords such as “flood”, “fire”, “damage”, “destroyed” or anything else that could be related to the specific disaster event, including searching for images tagged with  relevant keywords. A main challenge will be, of course, removing irrelevant information that may happen to contain similar keywords.

*Desired Deliverables:*
- A short write-up describing the project.
- Open source code to allow for implementation of this big data search process during a
disaster.
- The code should be flexible enough and allow the end user to change certain keywords
which would correspond to different disaster types, e.g.: “flood”, “water”, “depth”, for a
flood event and “burn”, “fire”, “smoke” for a wildfire event. Possible disaster events
include floods, fires, hurricanes, earthquakes, tornadoes, tsunamis and volcanoes.
- Output of this code should be a geolocated dataset (a GIS shapefile or json with lat/long
reference, or a KML file) with relevant information acquired from the tweet as attribution
- A preliminary proof of concept using a real-world example.

*Descriptions of data used as input:*

- Geo-referenced disaster-specific social media posts (with or without images).

- [Github Link for DSI-ATX students' past work.](https://github.com/skshenoy/disasters-and-social-media)
- [Github Link for DSI-ATX (2) students' past work.](https://git.generalassemb.ly/nlac10/project-5-on-hurricane-harvey)
- [Github Link for DSI-CHI students' past work.](https://github.com/alexlshon/MNDT-Project)
- [Github Link for DSI-DC students' past work.](https://github.com/belencito27/Map_Disasters_Twitter)
- [Github Link (2) for DSI-DC students' past work.](https://github.com/TungPhung/Twitter-Natural-Disaster-Mapping)
- [Github Link for DSI-BOS students' past work.](https://github.com/dawngraham/power-outages)
- [Github Link (2) for DSI-BOS students' past work.](https://github.com/TengCXXI/Mapping-Disasters-with-Social-Media)
- [Github Link for DSI-LA students' past work.](https://github.com/csinatra/Twitter-Disaster-Repo)
- [Github Link for DSI-LA (2) students' past work.](https://github.com/dae-han/disaster_tweet_map)
- [Github Link for DSI-NYC students' past work.](https://github.com/cameronbronstein/Project-4-New-Light-Technologies-Client-Project)
- [Github Link (2) for DSI-NYC students' past work.](https://github.com/ondovj/mapping_natural_disasters)
- [Github Link (3) for DSI-NYC students' past work.](https://github.com/Preeya0225/disaster_map)
- [Github Link for DSI-SEA students' past work.](https://github.com/ukm5/ClientProject_NewLightsTechnologies)
- [Github Link for DSI-SF students' past work.](https://github.com/sgodfrey66/Camp_Fire_Analysis)
- [Github Link (2) for DSI-SF students' past work.](https://github.com/pwalesdi/Mapping_Disasters)
- [Github Link (3) for DSI-SF students' past work.](https://github.com/Ishan16D/TwitterDisasterMapping)
- Feel free to use this as a reference or to build on top of it. **Make sure to provide credit where credit is due!!**


**Problem 2: Leveraging News and Media for Situational Awareness**

*Problem Statement:*
- During a major disaster, it is essential to provide the public and responders with relevant local news updates in order to gain situational awareness during the event.
- During a disaster, news updates are coming from tens to hundreds of different sources, all in different formats, available from different websites, news channels etc., and it is often difficult to find what would be most helpful amid the chaos of other non-disaster related news and media.
- There is currently no forum for rounding up and archiving relevant news for a live disaster event.
- This project will leverage news feeds relevant to specific disasters, gathered from multiple sources, to create a webpage that presents these live feeds under one umbrella (on one page). This is similar to the Google News feature.

*Desired Deliverables:*
- A short write-up describing the project.
- An open source code that allows to create a disaster-specific webpage, which “pulls” relevant news articles relevant to a specific event. The code should only pull the title of the article/post, an abstract/summary (if available) and an image/ thumbnail (if available) and include a link to the original source.
- An example (proof of concept) of a disaster event-specific web page which is populated by a real-time feed of relevant news articles, journals, blog posts, videos, etc. pertaining to a live event such as “Hurricane Lane”, or “Hurricane Harvey”, etc.

- A user accessing this web page should have the ability to filter the search query by date, media type and certain keywords such as “evacuation”, “fire”, “damage assessment”,
name of a city, etc.
- The tool should also allow the website editor to set these keywords and search queries (i.e. the page will always show the relevant news feeds set by the editor/admin).
- This web page can be integrated with other methods to provide situational awareness to the disaster response community such as being featured on a disaster response website with relevant disaster data.
- Map files, toolboxes, data and any other supporting files are needed as deliverables to test and run the code.

*Descriptions of input data:*
- News articles, journals, blog posts, videos from external media websites
- Online forms of relevant disaster media

- [Github Link for DSI-BOS students' past work.](https://github.com/keencyclist/disaster)
- [Github Link (2) for DSI-BOS students' past work.](https://github.com/mariellemarcus/New-Light-Technologies-Project)
- [Github Link for DSI-NYC students' past work.](https://github.com/RMExe/disaster-web/)
- [Github Link for DSI-SF students' past work.](https://github.com/surajsakaram/NLT-Client-Project)
- [Github Link for DSI-SF (2) students' past work.](https://github.com/billypyu/Project-4-Disaster-Classification-Leveraging-News-and-Media-for-Situational-Awareness)
- [Github Link for DSI-SF (3) students' past work.](https://github.com/tmckee35/Team-4-Client-Project)
- Feel free to use this as a reference or to build on top of it. **Make sure to provide credit where credit is due!!**

**Problem 3: Optimizing Evacuation Routes using Real-Time Traffic Information**

*Problem Statement:*
- During disasters, search and rescue teams must be able to search for and get to survivors as fast as possible (in terms of travel time and distance)
- Current GIS and navigation systems allow responders to calculate travel time and
distance between origin and destination and propose an optimal route to the destination.
- However, many of the current platforms do not rely on real-time data (e.g. road closures, damaged roads etc.) and can produce inaccurate or inefficient results.
- This project will leverage social media, news feeds and other datasets (e.g. Waze, Here.com) to identify real time road closures or damaged roads, power outages and other blocked routes that may affect traffic lights, travel time, travel safety and more.
- The system should allow the user (the public or rescue teams) to search for any of these conditions and identify if and where they exist in a specific location (street, neighborhood, city etc.)

*Desired Deliverables:*
- A short write-up describing the project.
- An open source code that pulls live information from social media and/or news feeds about road closures, road conditions, damaged roads, power outages etc. which may
affect travel and accessibility.
- The output can be either tabular (e.g. allow for search of names of closed roads) or geospatial (e.g. produce a map of real-time road closures).

- [Github Link for DSI-ATX students' past work.](https://github.com/DCapella/evacuation-routes)
- [Github Link for DSI-BOS students' past work.](https://github.com/rkelsey1207/Project5_evacroutes_BOS)
- [Github Link for DSI-DC students' past work.](https://github.com/Celis1/Project-5)
- [Github Link for DSI-DC (2) students' past work.](https://github.com/ariellem2/Disaster_Response_Maps)
- [Github Link for DSI-DC (3) students' past work.](https://github.com/templecm4y/GA-Twitter-Road-Closures-Client-Project)
- [Github Link for DSI-DC (4) students' past work.](https://github.com/rwstewart0302/evacuation_routes)
- [Github Link for DSI-DEN students' past work.](https://github.com/stuckeyj/DenProject4HurricaneFatalities)
- [Github Link for DSI-DEN (2) students' past work.](https://github.com/giffordtompkinsiii/Evacuation_Twitter_Client_Project)
- [Github Link for DSI-LA students' past work.](https://github.com/rachelkoenig10/Mapping-Road-Closures-Using-Real-Time-Traffic-Information)
- [Github Link for DSI-NYC students' past work.](https://github.com/jasminevasandani/Road_Closures_NLP_Modeling_Social_Media_News)
- [Github Link for DSI-NYC (2) students' past work.](https://github.com/fmanon/Road_Closures_Evacuation_Routes)
- [Github Link for DSI-SEA students' past work.](https://github.com/balak4/Optimizing-Evac-Routes)
- [Github Link for DSI-SF students' past work.](https://github.com/st-tse/miami_road_closure)
- Feel free to use this as a reference or to build on top of it. **Make sure to provide credit where credit is due!!**


**Problem 4: Using Google Street View as a baseline for damage assessment.**

*Problem Statement:* During the recovery phase immediately following a disaster, FEMA performs damage assessment “on the ground” to assess the level of damage caused to residential parcels and to critical infrastructure. To assure an accurate estimation of the damage, it is important to understand the condition of the structures prior to the event. To help and guide the damage assessment efforts following a disaster and to assist the surveyors identify the structures of interest, this tool (a web-app or a mobile app) will expect to get, as an input, a list of addresses. It will retrieve screen shots of the structures from Google Street View. The students will design a damage assessment form, which, in addition to relevant information about the level of damage to the structures, will also provide a pre-event photo of the assessed structure.

- [Github Link for DSI-ATX students' past work.](https://github.com/DataPointChris/newlight_satellite_image_detection)
- [Github Link for DSI-BOS students' past work.](https://github.com/nmcalow/Project_5_FEMA)
- [Github Link for DSI-DC students' past work.](https://github.com/Mauriekathan/Image_Geo_Team_Street_View)
- [Github Link for DSI-DC (2) students' past work.](https://github.com/wkarney/street_viewing_for_FEMA)
- [Github Link for DSI-DC (3) students' past work.](https://github.com/opacichjj/FEMA-PDA-and-Route-Optimizer)
- [Github Link for DSI-DC (4) students' past work.](https://github.com/ebpalmer17/fema-damage-assessment)
- [Github Link for DSI-LA students' past work.](https://github.com/valarn/FEMA-Damage-Assessment-API-Python)
- [Github Link for DSI-SF students' past work.](https://github.com/miecky/project-client_project)
- Feel free to use this as a reference or to build on top of it. **Make sure to provide credit where credit is due!!**

**Problem 5: Using news outlets or social media to identify areas or neighborhoods with power outages.**

*Problem Statement:* During a disaster, residential areas often experience massive power outages, that in many cases last for days. Traditional methods to map power outages include live feeds and data that is provided by major utility companies as well as on satellite data that capture the extent of light emitted at night.  This tool will utilize news feeds and/or posts on social media to identify “hot spots” of concern and areas suffering from power outages (assuming that these posts are reported via social media apps on mobile phone). Following an event, the tool will scan relevant news or social media websites to identify localities likely to suffer from power outage.

- [Github Link for DSI-LA students' past work.](https://github.com/CreightonAshton/Power_Outages)
- [Github Link for DSI-NYC students' past work.](https://github.com/boom-deva/FEMA-Power-Outage-Hotspot-Detection)
- [Github Link for DSI-NYC (2) students' past work.](https://github.com/jenrhill/Power_Outage_Identification)
- [Github Link for DSI-NYC (3) students' past work.](https://github.com/iceberg425/Client_Project)
- [Github Link for DSI-NYC (4) students' past work.](https://github.com/PeterGarcia95/DisasterRelief)
- Feel free to use this as a reference or to build on top of it. **Make sure to provide credit where credit is due!!**

**Problem 6: Using live police radio reports for real time identification of people needing assistance.**

*Problem Statement:* Currently, FEMA identifies areas that require immediate attention (for search and rescue efforts) either by responding to reports and requests put directly by the public or, recently, using social media posts. This tool will utilize live police radio reports to identify hot spots representing locations of people who need immediate attention. The tool will flag neighborhoods or specific streets where the police and first-respondents were called to provide assistance related to the event.

- [Github Link for DSI-ATL students' past work.](https://github.com/delvakwa/police_radio_to_mapping)
- [Github Link for DSI-DEN students' past work.](https://github.com/jaelynn624/Mapping_Emergency_Calls_Project)
- [Github Link for DSI-SF students' past work.](https://github.com/GWilson97/san_francisco_dispatch_audio_mapping)
- Feel free to use this as a reference or to build on top of it. **Make sure to provide credit where credit is due!!**

**Problem 7: Using Indeed or Glassdoor together with number and type of affected businesses to estimate the expected economic loss due to a disaster**

*Problem Statement:* This tool will rely on websites that provide employment information and sector-specific wage estimations (such as Glassdoor and Indeed) to project the economic loss (wage loss) due to a disaster. Based on the type of businesses and services in a given affected area and/or using supplementary demographic data (for example, from the Census Bureau of Statistics), the tool will provide an estimation about the projected economic loss in a given locality based on the reported or estimated wage loss in the locality.

- [Github Link for DSI-BOS students' past work.](https://github.com/EricPmWong/NewLightTechQ11)
- [Github Link for DSI-DC students' past work.](https://github.com/whiteashleye/EconomicLoss_NaturalDisaster)
- [Github Link for DSI-SF students' past work.](https://github.com/mitchdshawn/disaster_income_loss)
- Feel free to use this as a reference or to build on top of it. **Make sure to provide credit where credit is due!!**

**Problem 8: Crowdsourcing Damage Photos**

*Problem Statement:*
Imagery is scarce at the start of a disaster. FEMA and partners rely on photos and other imagery to understand the disaster impacts and validate reports of damage. However, it is almost impossible to systematically acquire imagery the first day. Within the first few days, FEMA typically receives several types of satellite data. Within a week, other aerial imagery becomes available. Photos posted to social media can help fill in gaps in the interim, but these images are not captured systematically. The entire emergency management community would benefit from an app or service that anyone in an impacted area could use to take and submit photos. Ideally, these photos could be attained with cameras people may have on them (e.g. iPhones) or low-cost cameras. We need a systematic image capture workflow in order to conduct AI/ML/edge computing to conduct damage assessments. (Doing this from the ground would probably be quicker/easier than waiting on the winds to dissipate so you can fly planes.)

*Proposed Deliverables:*
- A short write-up describing the project, results, and next steps or proposal to scale.
- A list of technical requirements for an app that allows anyone in an impacted area to upload disaster photos. Examples include:
     - Must work in a low-connectivity environment (e.g. phone-to-phone mesh networks)
     - Includes geolocation of upload
     - Allows user to annotate or tag photos
     - Service/app can be deployed through email, social media, emergency messaging systems, or other common platforms
- Open source code for a “crowdsourcing app” that meets the defined requirements.
- A pilot or proof of concept.

**Problem 9: Finding Tents and Other Emergency Housing Through Exploitation of Satellite Imagery**

*Problem Statement:*
During disasters, emergency management agencies and humanitarian organizations need to know where survivors are congregating in order to provide emergency supplies and services. Sometimes, as was the case during the January 2020 earthquakes in Puerto Rico, local communities set up tents as informal shelters. State and national-level organizations may not know about these shelters for days. How can satellite imagery be used to identify informal shelters? Can the same imagery be used to observe changes in the number of tents or occupants? Can we see when a tent shelter is taken down?

*Proposed Deliverables:*
- A short write up describing the project, results, and next steps or proposal to scale
- Open source code for exploiting open source imagery
- An example or case study (e.g. Puerto Rico earthquakes)

*Descriptions of input data:*
- Sentinel data
- Digital Globe imagery
- Google Earth imagery
- Other imagery from earth-observing satellites

**Problem 10: Updating Shelter Status**

*Problem Statement:*
During disasters, shelters provide supplies and services to disaster survivors. Informal shelters can often be identified through social media and other internet sources; shelter operators are efficient at messaging about resource availability. However, this information is highly perishable, and it is difficult to know when a shelter is closed. How can social media or an app be used to allow any person visiting a shelter to record changes about the shelter status?

*Proposed Deliverables:*
- A short write up describing the project, results, and next steps or proposal to scale
- List of requirements for a system to track shelter status. For example:
     - Tracks changes in shelter status over time
     - Allows survivors or emergency managers to update shelter status
     - Moderator rights to approve changes
- Open source code for managing shelter status

*Descriptions of input data:*
- Social media, news outlets

**Problem 11: Identifying Misinformation in Disaster-Related Social Media Posts**

*Problem Statement:*
While social media increasingly becomes the first source of information about disasters, this information is not always correct. Posts can be misleading or mistaken. On rarer occasion, users intentionally spread misinformation. How can emergency management agencies identify incorrect information before, during, and after disasters?

*Proposed Deliverables:*
- A short write up describing the project, results, and next steps or proposal to scale
- Open source code for identifying rumors among relevant social media posts
- Proof of concept or pilot from a recent disaster

*Descriptions of input data:*
- Social media

**Problem 12: Extracting Flood Depths from Imagery**

*Problem Statement:*
Floods cause damage to infrastructure and homes. The depth of flood waters is a good indicator of the severity of damage. Floods are incredibly difficult to model, and while model outputs are useful to emergency managers, it is crucial to know the actual depth. Social media and news outlets often present pictures of floods. How can this imagery be used to estimate the depth of water in a given area?

*Proposed Deliverables:*
- A short write up describing the project, results, and next steps or proposal to scale
- Open source code for estimating flood depths from ground-based imagery
- Example from flooding after a recent hurricane (e.g. Imelda, Florence, Harvey)

*Descriptions of input data:*
- Social media
- News (TV, internet, etc.)
- Traffic cameras
- Google Street View (“normal” imagery)

**Problem 13: Improve Slum Area Identification through Real-Estate Data**

*Problem Statement:*
Mapping of informal settlements with satellite imagery is a long-standing practice, but such methods could be enhanced through web-scraped real-estate data. This project would build a web scraper to house and apartment adverts for a selected city in Africa/Latin America/Middle East. The scraper should download all adverts in the city during a recent period (ideally 3 years or more); and map all the adverts. The project should test the feasibility of estimating informal tenure from this information. Using gridded population estimates (e.g. from Facebook), the team would calculate the ratio of real estate adverts with population density. This ratio could serve as an input to machine learning models aimed at mapping informal settlements.

*Proposed Deliverables:*
- A short write up describing the project, results, and next steps or proposal to scale
- Open source code for full process from gathering data to calculating and mapping the real estate to population density ratio
- Proof of concept or pilot from a city or collection of cities.

**Problem 14: Sentiment Analysis of COVID-19 Social Media Posts**

*Problem Statement:*
The COVID-19 response has been largely regional and state-based in nature. Some states have enacted strictly enforced stay-at-home policies, while others have provided guidelines. It would be worthwhile to compare the sentiment analysis of social media posts across geographic regions and compare them to both the local policies on social distancing and the occurrences of the pandemic in those areas.

*Proposed Deliverables:*
- A short write up describing the project, results, and next steps or proposal to scale
- Open source code for identifying social media posts from specific regions and conducting a sentiment analysis or topic extraction on that data

*Descriptions of input data:*
- Social media
- Government data on social distancing policies
- Health related data on COVID-19 occurrences in that region

**Problem 15: Mapping Hotspots of COVID-19 Cases**

*Problem Statement:*
The data released regarding instances of the COVID-19 pandemic is aggregated before it is released to (legally and ethically) protect the privacy of those involved. Unfortunately, this takes away some of the utility of the data.  Using social media, the location of cases can be narrowed further while still protecting privacy rights. Social media data can provide a heat map for potential COVID-19 risk.

*Proposed Deliverables:*
- A short write up describing the project, results, and next steps or proposal to scale
- A shape file or other GIS visualization of potential heat map of COVID-19 cases.

*Descriptions of input data:*
- Social media
- Health related data on COVID-19 occurrences in that region

**Problem 16: Identifying Areas At Risk for COVID-19 and Other Natural Disasters**

*Problem Statement:*
The COVID-19 pandemic, in some areas of the globe, will exacerbate the ongoing risk/exposure to other natural disasters. There is little understanding of the coupling of the pandemic risk and the risk of these other occurrences. A case study will show, via geospatial analysis, an overlay of the severity of the COVID-19 pandemic and the risk of floods, hurricanes, earthquakes, drought, etc.

*Proposed Deliverables:*
- A short write-up describing the project.
- The output should be geospatial with layers of the different disaster exposures.

*Descriptions of input data:*
- Current and/or historic natural disaster risk data
- Health related data on COVID-19 occurrences

**Problem 17: Mapping Available Commodities During the COVID-19 Pandemic**

*Problem Statement:*
On a daily basis, news and social media highlight the shortage of certain commodities in local stores. There are limited ways for stores to indicate the availability of commodities that may be in demand (paper products, cleaning supplies, hand soap and sanitizer, etc). People, and stores, post on social media when they have availability. This project would be to create a geospatial layer that pulls in real-time social media posts to highlight where items are available in a given geographic location.

*Proposed Deliverables:*
- A short write-up describing the project.
- A geospatial output that shows the location of social media posts and available commodities, with a time stamp on those posts.

*Descriptions of input data:*
- Open source code to automatically identify a commodity and its availability at a given location.

**Problem 18: Chicago Case Study: Hotel Availability for Quarantine**

*Problem Statement:*
The City of Chicago was the first in the United States to coordinate the use of available hotel rooms as a location for safe quarantine during the COVID-19 pandemic. The hotels participating aren’t readily known to those who may need to use them for quarantine purposes. This project would be to create a tool to visualize in a geospatial layer the hotels used for quarantine, as well as their capacities.

*Proposed Deliverables:*
- A short write-up describing the project.
- A geospatial output that shows the location and capacity of hotels used for quarantine in real-time.

*Descriptions of input data:*
- Open source code to automatically identify nearby hotels and their capacity for quarantine.


### Supplemental Code from GA DSI Alumni

Students in the past have completed projects that are no longer offered, but may be of interest to you. Feel free to use this as a reference or to build on top of it. **Make sure to provide credit where credit is due!!**

##### Extracting building values from Zillow

- [Github Link for DSI-ATL students' past work.](https://github.com/katychow/DSI_Project4_Zipcodes)
- [Github Link for DSI-BOS students' past work.](https://github.com/hixjas/Project-4-Zillow)
- [Github Link for DSI-DC students' past work.](https://github.com/tbacas/Zillow-Disaster-Estimates)
- [Github Link for DSI-DC students' past work.](https://github.com/zeeemo/Disaster-Estimates)
- [Github Link for DSI-DC students' past work.](https://github.com/jhuessy/ga_client_project_zillow)
- [Github Link for DSI-NYC students' past work.](https://github.com/cbratkovics/damage_estimator)
- [Github Link for DSI-NYC students' past work.](https://github.com/rows317/DSI-8-Client-Project/blob/master/README.md)
- [Github Link for DSI-SEA students' past work.](https://github.com/dsteffan/mount_rainier_disaster_estimate)
- [Github Link for DSI-SF students' past work.](https://github.com/justinaugust/what-value-what-damage)

##### Utilizing social media to alert about new disasters and their nature

- [Github Link for DSI-ATX students' past work.](https://github.com/eamonious/disaster-tweet-classification)
- [Github Link for DSI-ATX students' past work.](https://github.com/newtonsspawn/project_4)
- [Github Link for DSI-DC students' past work.](https://github.com/katerdowdy/twitter_disaster)
- [Github Link for DSI-LA students' past work.](https://github.com/mayjordata/Project-TeamAlert)
- [Github Link for DSI-NYC students' past work.](https://github.com/EdithIyer/Harnessing-ML-for-Natural-Disaster-Alerts)
- [Github Link for DSI-NYC students' past work.](https://github.com/klejohnson/Client_Project)
- [Github Link for DSI-SEA students' past work.](https://github.com/bkumar33/Group_client_project)
- [Github Link for DSI-SF students' past work.](https://github.com/rkkwan/disaster-rapid-alert)

##### Utilizing Yelp cost estimates for estimating neighborhood affluency

- [Github Link for DSI-BOS students' past work.](https://github.com/taylorjsimpson/GA_DSIBos_Yelp_Project5)
- [Github Link for DSI-CHI students' past work.](https://github.com/brmcdonnell/estimating_affluence)
- [Github Link for DSI-DEN students' past work.](https://github.com/rbkim1990/yelp-client-project)
- [Github Link for DSI-LA students' past work.](https://github.com/jlian014/Clientproject_DSI_LA6)
- [Github Link for DSI-LA students' past work.](https://github.com/hovikgas/hovieco)
- [Github Link for DSI-LA students' past work.](https://github.com/irinhwng/Yelp)
- [Github Link for DSI-LA students' past work.](https://github.com/aejsong/Predicting-Neighborhood-Affluence-with-Yelp)
- [Github Link for DSI-NYC students' past work.](https://github.com/twludlow/ga_project_4)
- [Github Link for DSI-NYC students' past work.](https://github.com/Shaddyjr/predicting_affluence_using_yelp)

##### Utilizing Yelp data to estimate the number of businesses in a given locality and categorizing them according to FEMA's seven lifelines

- [Github Link for DSI-ATL students' past work.](https://github.com/awharmon/FEMA-Lifelines-Categorization-for-Disaster-Response)
- [Github Link for DSI-ATX students' past work.](https://github.com/adriancampos1/GA_DSI8_FEMA_Lifelines)
- [Github Link for DSI-BOS students' past work.](https://github.com/micahluedtke/FEMA_lifelines)
- [Github Link for DSI-CHI students' past work.](https://github.com/jwasham12/Client-Project)
- [Github Link for DSI-DEN students' past work.](https://github.com/meldev00/FEMA_disaster_tool)
- [Github Link for DSI-DC students' past work.](https://github.com/k10jo01/fema_lifeline_impact)

##### Leveraging News Sources and Social Media to Identify Major Historic Flood Events

- [Github Link for DSI-CHI students' past work.](https://github.com/bethpadera/CHI-DSI9-PROJECT-FLOOD)
- [Github Link for DSI-NYC students' past work.](https://github.com/Chana-T/historic-flooding-in-social-media)


## Requirements
For the purposes of a DSI project, you must meet a few technical requirements. They are:
1)  A `README.md` file in your project repo. Note that `README` files are automatically rendered by GitHub when you view a repo. Your README should contain:
    - A problem statement.
    - A succinct formulation of the question your analysis seeks to answer.
    - A table of contents, which should indicate which notebook or scripts a stakeholder should start with, and a link to an **executive summary**.
    - A paragraph description of the data you used, plus your data acquisition, ingestion, and cleaning steps.
    - A short description of software requirements (e.g., `Pandas`, `Scikit-learn`) required by your analysis.

2) Your notebook(s) should be **reproducible** and **error-free**. This means:
    - You should set a random seed at the start of every notebook, using `np.random.seed(...)`. This will ensure that the random numbers generated in your notebook will be the same every time.
    - You need to provide a _relative path_ to your data, so that if I clone your repo to my machine I can run everything in your repo without error. (You also provide links to any publicly accessible data.)
    - I should be able to `Restart & Run All` in your notebook(s) and see that the _exact same_ results are reproduced.
    - To check that everything worked properly, you may consider forking your own repo to a different location on your computer and checking that all notebooks can run properly from top to bottom.

3) Bear in mind that the value you provide to New Light Technologies may come from data ingestion, data cleaning, EDA, and/ or a dashboard, etc. While a model may not be immediately apparent, be creative. *Without us telling you exactly what model to build, how could you build a model to increase performance or generate better insights when answering the problem you are facing?*

**Deadline**: June 19, 2020.

**Questions**: Questions should be sent to your instructors; questions that need to go to the client should be directed to Adi Bronshtein via email (adi.bronshtein@generalassemb.ly). **Questions should be specific, brief, and formatted so that they can be directly sent to our contacts at NLT.**
> This is a good practice to develop! When contacting a boss or a client, you should make your question as easy as possible to answer. Consider the following two examples:

> Example 1: "Hey, I have a question. I'm writing a blog post about TensorFlow but got stuck. This part was confusing: https://www.tensorflow.org/api_docs/python/tf/tanh Can you help?"

> Example 2: "The TensorFlow tanh documentation says 'Computes hyperbolic tangent of x element-wise.' What does hyperbolic tangent mean? The link to see more is: https://www.tensorflow.org/api_docs/python/tf/tanh"

> The first example spends about 20 words before mentioning what is going on. The question "Can you help?" is unspecific. The boss/client is required to go to a link in order to get any information about the problem.

> The second example quickly calls out 'Tensorflow tanh documentation,' the explicit quote that is confusing, the explicit question being asked, and a link for additional context. Both examples attempt to get the boss/client/whomever to explain hyperbolic tangent, but imagine how much more quickly someone could answer the second query than the first.

> A helpful way to consider this: When you ask a question, you are basically asking for a favor. You're asking a person to give their time, their brainpower, and their knowledge to you. Every time you ask them to hunt around for more (i.e. they _have_ to travel to a link to get context or they struggle to understand the question you're asking), you're asking a bigger and bigger favor from them.

---

### Teams

We will divide you into teams based on your prompt preferences that you submit here: https://forms.gle/HqWjd3aJyAMXKDZe6 (DUE: end of lunch on Tuesday, June 2)

---

### Presentations

Each group will present their findings.

Your presentation must include:
- A summary of the problem you tackled.
- A walkthrough of how you set out to solve the problem.
- A demonstration of your solution. (i.e. You may demonstrate an app you developed, an example of how a model may be used, etc.)
- A summary of any models you fit and, if applicable, their performance.
- A brief discussion of limitations to your process. (i.e. data collection issues, missing values)
- A brief discussion of next steps.

Presentation requirements:
- *Consider the audience!*
- *As with presentations in the "real world," there is no required time limit.* Your presentation should be long enough to cover all relevant aspects of the problem, but not so long that it obscures the takeaways of the presentation. (Your group should likely aim for somewhere between 15 and 20 minutes, but it is possible that you may need a different amount of time for your presentation.)
- Your presentation must include slides. (Google Slides, PowerPoint, Keynote, etc.)
- Use visuals that are appropriately scaled and interpretable.
- Make sure you provide clear conclusions/recommendations that follow logically from your analyses and narrative and answer your data science problem.
- *Your presentation must also be recorded so that it may be shared with the client.*

---

### Consulting Project Feedback + Evaluation

Data science is a field in which we apply data to solve real-world problems. Therefore, projects and presentations are means by which we can assess your ability to solve real-world problems in a data-driven manner.

When evaluating projects, there are four areas on which your instructors focus.
1. **Project Requirements: Did you meet all project requirements?** In answering this question, your instructors want to assess how well you met the project requirements as established. These will generally be laid out in the project readme.

2. **Audience: Is your presentation appropriate for the stakeholder?** In answering this question, your instructors want to assess how well you present your results to stakeholders. For example:
  - Did you frame the problem appropriately for the audience?
  - Did you use the appropriate level of technical language for your audience?
  - Did you effectively use your time, or did you encounter an issue such as going significantly beyond or under the allotted time or rushing to conclude the presentation in the allotted time?
  - Did you present effectively, or were there things that detract from the overall presentation such as not speaking loudly enough for the audience or repeating oneself?

3. **Methods: Are your methods appropriate for solving the problem?** In answering this question, your instructors want to assess how well you have applied data science methodology to the problem at hand. For example:
  - Did you make well-reasoned modeling choices, or is there clear evidence that the model is inadequate or improper?
  - Are you able to clearly defend your methodological decisions and results?
  - Did you generalize your results properly, or were your conclusions/inferences improper or fallacious?

4. **Value: Have you provided value to the stakeholder through clear, data-driven recommendations?** In answering this question, your instructors want to assess the value you provide to the stakeholder as a data scientist. For example:
  - Did you answer the problem posed to you?
  - Did you make your recommendations clear, or were the recommendations unclear?
  - Were your recommendations data-driven and based on the results of your work?

You will earn a score for each of the four areas mentioned above.
1. Project Requirements: You may earn a score of 0 or 1. You will earn a score of 1 if all project requirements are met. Otherwise, you will earn a score of 0.
2. Audience: You may earn a score between 0 and 3. A score of 0 indicates that your presentation is inappropriate for the stakeholder. A score of 1 indicates that at least part of your presentation should be non-trivially reworked to be more appropriate for the stakeholder. A score of 2 indicates that there are few to no areas of your presentation that should be reworked. A score of 3 indicates that your presentation is consistently appropriate for the stakeholder and serves as a model for future presentations.
3. Methods: You may earn a score between 0 and 3. A score of 0 indicates that your methods are inappropriate. A score of 1 indicates that your methods are somewhat inappropriate, that justification for methodological decisions is lacking, and/or that your conclusions do not follow from the methods. A score of 2 indicates that your methods are appropriate, justification is sufficient/strong, and your conclusions follow well from the methods. A score of 3 indicates that your methods are excellent, strongly defended, and serves model for future presentations.
4. Value: You may earn a score between 0 and 3. A score of 0 indicates that you provide little to no value to the stakeholder. A score of 1 indicates that the value you provide to the stakeholder is substantially less than expected by not answering the problem, not providing clear recommendations to the stakeholder, and/or providing recommendations that were not data-driven. A score of 2 indicates that the value you provide to the stakeholder is on par with the expectation of providing clear, data-driven recommendations that directly answer the problem posed. A score of 3 indicates that the value you provide to the stakeholder is beyond what is expected and serves as a model for future presentations.

Your final grade will be calculated as follows:
- If any project requirement is not met, the final grade is 'Fail' with a score of 0.
- If all project requirements are met, then the final grade is 'Pass' with a score calculated by summing the above scores. Therefore, if all project requirements are met, the final score will be between a 4 and 10.
