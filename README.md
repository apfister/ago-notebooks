# ago-notebooks
A collection of jupyter notebooks to work with ArcGIS Online and ArcGIS Hub

## Localize an ArcGIS Hub Site (along with its the Groups and Items)
(catchier title to come)

Go [here](Localize%20an%20ArcGIS%20Hub%20Site) for more info!

## Apply a Layout to a Hub Site from a Template
Quickly skin a Hub Site with JSON

Examples
- [hub-site-standard.json](resources/hub-site-templates/hub-site-standard.json) - The standard ArcGIS Hub Site layout you are provided with out of the box.
- [sdg-hub-standard.json](resources/hub-site-templates/sdg-hub-standard.json) - The standard SDG Hub Site layout [live link](http://sdg-template-sdgs.hub.arcgis.com/)
- [sdg-hub-standard-categories.json](resources/hub-site-templates/sdg-hub-standard-categories.json) - The standard SDG Hub Site layout, using Category cards to represent Ministries or Departments as well as the SDG Icons & Tiles. [live link](http://sdg-template-cat-sdgs.opendata.arcgis.com)
  - Note, this layout would depend on you creating a Page specifically to show the SDG Icons, which can be found at:
  - [sdg-hub-page-categories.json](resources/hub-site-templates/sdg-hub-page-categories.json) - SDG Hub Page template [live link](http://sdg-template-cat-sdgs.opendata.arcgis.com/pages/sdgs)
- [irl-sdg-geohive.json](resources/hub-site-templates/irl-sdg-geohive.json) - Ireland, Sustainable Development Goals [live link](http://irelandsdg.geohive.ie/)
- [sdg-dot-org.json](resources/hub-site-templates/sdg-dot-org.json) - SDG[dot]org [live link](http://www.sdg.org)
- [sdg-no-poverty.json](resources/hub-site-templates/sdg-no-poverty.json) - SDG1: No Poverty [live link](http://nopoverty-sdgs.opendata.arcgis.com/)

## Enable Open Data
Programmatically push the "Enable Open Data" button for your ArcGIS Online Organization. [more info](https://doc.arcgis.com/en/hub/get-started/enable-open-data-capabilities.htm)

## Get User Reports
This notebook will walk you through the process of querying the ArcGIS REST API to find out what Users have been created in the last 24 hours as well as what Users have logged in the last 24 hours. The time frame is adjustable in the code.

## Hub Items Report
Generate a CSV report of Items added to a Hub

## Share Content from Existing Public Group
Take content from a public group in ArcGIS Online and share it to another Group of your choosing.

## Update Feature Service from Feature Layer Collection
Update an existing Feature Service using a CSV, XLSX, etc.