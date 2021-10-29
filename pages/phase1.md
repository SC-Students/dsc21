---
layout: page
title: "Phase 1 Project Details"
subheadline: ""
teaser: "Details for Phase 1 of the Competition, including the data sets are posted here!"
permalink: "/competition/phase1/"
---

# Phase 1
The first phase of the competition will revolve around a single source of data and broad topic area for students to work on. Students should focus on generating useful insights, visualizations, analytics, and/or predictive modeling as appropriate. Teams should use this time to work out all the hiccups in using the Oracle Platform, running code, gathering data, designing approaches, and 

## Agriculture in the St. Louis Area
Agriculture, AgTech, and Plant Sciences are all big in the greater St. Louis area, so this year we've chosen this topic area for students to work on. We'd love foyou to focus your efforts in the St. Louis area when downloading the data, but you are welcome to choose your own parameters. 

We hope that this experience will also inspire you to work on related projects in the future and that you'll learn a lot about how to work with this type of data. If you have absolutely any questions about this do ping us on Slack. 

## Accessing the data
The data is publicly available via the USDA website. This data must be used for Phase 1, but you do not need to use every available feature. We recommend you get started with downloading the data ASAP by reviewing references for accessing this data. If you are stuck with this reach out to the committee ASAP and we will help you get the subset of data from here that you need. There's a lot of possible data to work with here and it's up to each team to decide how much to use. 

- Data sources are here: 
  - <a href="https://www.nass.usda.gov/Data_and_Statistics/index.php">National Agricultural Statistics Services</a>
    - This is the easiest data to work with, as it is directly downloadable, however it may not suit your needs exactly
  - <a href="https://www.nass.usda.gov/developer/index.php">National Agricultural Statistics Services Developer Guide</a>
    - QuickStats data will allow you to pull many county and state level information together, but requires using an API. 
    - This data requires that you use an API to download the data. You'll need to sign up by email to get an API Key and that should arrive fairly quickly. 

You MUST use one or more of these datasets. We recommend starting with QuickStats and moving into the map-based data as you are comfortable. 
- QuickStats Database
- CropScape
- VegScape
- Crop Condition and Soil Moisture Analytics
- Crop Progress and Condition Gridded Layers
- Disaster analysis
- Land use Strata for Selected states

If you are unable to get this data for any reason, please let us know ASAP. If you've never worked with an API before, there are many resources and examples online for how to do so. In Python, you'll need the `requests` package. 

References:
- <a href="https://sc-students.github.io/dsc21/resources/educational/"> DSC Resources for GIS Data</a>
- <a href="https://www.dataquest.io/blog/python-api-tutorial/">Python APIs Tutorial</a>
- <a href="https://developers.arcgis.com/python/">ArcGIS API Developer Guide</a>
- <a href="https://content.ces.ncsu.edu/getting-data-from-the-national-agricultural-statistics-service-nass-using-r">Getting NASS Data with R</a>

## Supplemental data
If you're feeling ambitious or think that the data could use more features, here are a few potentially relevant open data sources that you can incorporate into the projects. You're not limited to these, but we wanted to help you get started with some ideas. Please try not to spend too much time trying to think of or find extra data to merge with the required data. Think about this deeply as you work on getting your required data. 

- <a href="https://www.usda.gov/content/usda-open-data-catalog">USDA Open Data</a>
- <a href="https://www.stlouis-mo.gov/data/datasets/">St. Louis Open Government Data</a>
- <a href="https://rdx.stldata.org/">St. Louis Open Data</a>
- <a href="https://www.ncdc.noaa.gov/cdo-web/">NOAA Climate Data</a>
- <a href="http://www.data.gov/">US Government Data</a>

## Reminders

### Make a game plan and split the work at each step
Try to make a game plan with your team on approaching this data. For example, kick things off by splitting each person or pair of people into topic areas to focus on so even if one thread isn't working as expected, you have multiple threads moving in parallel. 

Example Plan:
1. Students A,B focus on getting API access to QuickStats and making their API requests in Python
2. Students C,D focus on downloading the CropScape data and understanding the data format in Python
3. All students decide whether or not to pursue the rest of the data. If they say yes:
4. Students A,B begin working on exploring the data format and reviewing documentation to understand the data better
5. Students C,D begin working on accessing the disaster analysis data
6. Students regroup and decide on the next steps

### Ask for help when you need it
This is a learning experience for everyone, no matter your skill levels. Don't be afraid to do something for fear of failure, it's a fast way to learn. Ask questions of your teammate, your mentor, and our committee. I highly recommend limiting being stuck on a single issue for <b>only 15 minutes</b>. If you are stuck that long, ask someone. 

### Start small
Sometimes tasks can feel overwhelming. We recommend starting with just a small step to avoid analysis paralysis. If you start with something like "getting the API token for the data" and move into "run Python example code for getting API data", these steps are easier to accomplish in smaller chunks.  

## Mistakes and delays are okay 
Sometimes making a mistake that delays your results can feel devastating. Remember that this phase is <b>meant to be for you to practice</b> everything you need for Phase 2: data downloading, working on Oracle, working in Jupyter notebooks, installing relevant libraries, data cleaning, exploratory data analysis and visualization, modeling, and result summarization. While we are looking forward to your results, we hope that Phase 2 will be smoother once you've worked through this step and fixed any hiccups/issues. We are just looking for you to complete enough work on this project to move you into Phase 2, so do not fret if you feel behind. 

## Incorporate extra data only if it enhances the "story"
The time spend finding and generating ideas about the extra data you can incorporate into your project may be better spent focusing on making sure you have done some work on the required data. Time spent download, understanding, and cleaning new data is less time spent on generating insights. While data sourcing and cleaning make up a large chunk of the day-to-day of many data scientist careers, we want you to have enough time to understand the problem you want to solve!

## Use the tools you need to get the job done
Python is the primary tool for this competition, but you may need to run some data processing in R if you want to use certain statistical packages. R can be run in a Jupyter notebook. To do this on Oracle cloud, you may need a Docker container. Ping Lyudmil if this is a route you'd like to pursue.
