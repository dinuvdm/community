<h1 class="h1-home">Community Model&nbsp;Building</h1>

Prep for the EPA's sustainable community model building events in 2020.   

<!--
Supply chain "License to Operate" with the support of the community.

### Code for Atlanta Projects  

Slack #epa

<b>1. Teams</b>: Brainstorm Projects - [Review maps and charts](tools/), [Review inventory exchange](tools/#places)   

<b>2. GitHub</b>: Experiment with [GitHub Packages](https://help.github.com/en/github/managing-packages-with-github-packages/about-github-packages#supported-clients-and-formats)  
  Is it possible to pull just the [community](https://github.com/datascape/community) "tools" folder into [model.georgia](https://github.com/datascape/model.georgia) repo?   

<b>3. Leaflet</b>: [Place a round image](https://github.com/ilyankou/Leaflet.IconMaterial/issues/3) over a [Leaflet.IconMaterial](https://github.com/ilyankou/Leaflet.IconMaterial) map point, which allows for color assignment. [Test here](/community/hubs).  

<b>4. D3.js</b>: [Create charts](samples/dataset/) using [new csv file](samples/dataset/USEEIOv1.2_result_2007_impacts_final.csv) - [which Wes exported from API](resources/useeio/) with this [Python](python/produceUSEEIOimpactcsv.py).  
-->


<!--
	https://www.wrld3d.com/wrld.js/latest/docs/leaflet/L.DivIcon/
-->
 


[Starter samples](samples/) and [datasets](https://github.com/modelearth/community) for integration with the [US Environmentally-Extended Input-Output (USEEIO)&nbsp;API](https://github.com/usepa/useeio_api/wiki/Use-the-API).  


[Include your data](samples/feed) - Publish your material inventory and maintain a wishlist to share your needs.

### Schedule  

[<b>Spring 2020</b> - Georgia's Life Cycle App Ideas Challenge](https://model.georgia.org/)  

[<b>Fall 2020</b> - Code for America Sustainable Communities Hackathon](https://www.codeforamerica.org/) 
<br>

<a href="https://model.georgia.org/communities/">Learn more</a> and join our project at <a href="https://www.meetup.com/codeforatlanta/">Code for Atlanta</a> 

### Summary

1. Using the [USEEIO API](https://github.com/usepa/useeio_api/wiki/Use-the-API), CSV files will be [generated](resources/useeio) for demand vectors (Food System and Full System). 

2. Detailed [Goods & Services Report](samples/dataset) with economic value and environmental impact of production choices.   

3. [Maps of products and industries](samples/maps) - Regional hubs, industries by zipcode.  

4. [Visualizations](samples/charts/) of material flow and regional input-output.  


### Project Areas

1. Update CSV files on employment and industries using [Census industry data](industries) and [uszipcode](https://uszipcode.readthedocs.io/01-Tutorial/index.html) - [github](https://github.com/MacHu-GWU/uszipcode-project).  

1. Python and SQLite script to pre-process data for D3 charts. 
Data includes [income by zcta](prep/all)<!--[projections](prep/regression/)-->.  

1. Add D3 heatmap colors to USEEIO data on [Goods & Services Report](samples/dataset).

1. [Progressive Web Apps](resources/pwa) - use the PWA Starter to add an index.htmml page to the pwa folder.

1. Display [Georgia Recycling data](recycling/ga/) in Leaflet map layers.

1. Display industry and demographic data on [zip search](zip/#zip=30315) and [zip map](zip/leaflet/).  

1. Use a [JAMstack Editor](https://headlesscms.org/) to edit content on GitHub. 
And/or <a href="https://www.apollographql.com/docs/apollo-server/">Apollo</a> GraphQL for faster dev than<!--the point-to-point nature of--> REST endpoints.  

1. Highlight <a href="../community/tools/#data">Smart & Mobile Communities</a> on Leaflet map. 
Update Smart Georgia <a href="samples/routing/">driving tour routes</a>.

1. Deploy Leaflet in Widget. Include [windy.com](https://windy.com) weather layer using their [API for Leaflet](https://github.com/windycom/API).

1. Cross-relate industries to [Exports via Harmonized System (HS Codes)](https://georgiadata.github.io/display/products/) 

1. Display [Farm Fresh - Federal USDA location data](farmfresh/ga) on Leaflet map - initially merged for Aglanta.  

1. Add cascading category toggle to [Goods & Services Report](samples/dataset). 

1. Cross-relate NAICS industries and HS Codes.  

<!--
National Renewable Energy Laboratory (NREL) - alternative fuel stations 
	https://developer.nrel.gov/docs/transportation/alt-fuel-stations-v1/all/#ev-network-id-record-fields

13. Activate Netlify Identity or Firebase Hosting using [Google Cloud Build](https://medium.com/serverlessguru/aws-to-gcp-web-applications-89ed92070832) and/or [ERPNext](https://aws.amazon.com/marketplace/pp/B015GHHU7M) (MariaDB/Python/AWS EC2).

14. [Climate Change Action Plans](https://www.c2es.org/document/climate-action-plans/) - Incorporate how other states support information exchanges.  
-->

<br>
 
## Related Material

<!--
There is growing trend across industry to trace the entire supply chain. 
Responsible sourcing allows manufacturers to...
-->

[Sustainable Materials Management](https://www.epa.gov/smm) - US EPA  
<!--
[Recycling and Resource Recovery as a Tool for Regional Economic Development](https://www.epa.gov/smm/sustainable-materials-management-smm-web-academy-webinar-recycling-and-resource-recovery-tool) - Webinar: Nov 20, 2019, 1PM  
-->
[OECD - Organization for Economic
Co-Operation and Development](https://www.oecd.org/sti/ind/measuring-trade-in-value-added.htm) - France  

<!-- GEOD - Global Economic Open Database  -->

[Leyla Acaroglu on Life Cyle Assessment](https://medium.com/disruptive-design/a-guide-to-life-cycle-thinking-b762ab49bce3)   

[Knoema Infographics](https://knoema.com/infographics) - [Data Coverage Matrix](https://knoema.com/atlas/matrix) - Global models which could be reproduced locally.  

[World Input-Output Database (WOID)](http://www.wiod.org/otherdb)  

[EXIOBASE database](https://simapro.com/products/exiobase-database/) / [ImPlan Impact Analysis](https://implanhelp.zendesk.com/hc/en-us/articles/360039284273-Environmental-Data) 


<!--
USCSD Materials Marketplace - Seems to be members only. Wes has a contact that worked on it.
https://usbcsd.org/materials

Southern Regional Science Association
http://www.srsa.org/
-->

<br>

## Team Projects

<a href="https://poloclub.github.io/#cse6242">Georgia Tech project teams</a> will have an opportunity to contribute new data visualizations.  



<!-- Re-connect with Polo in early January. Provide: 

1) Description of problem (e.g., high level problems, opportunities for ML, vis, the combination, etc.)

2) Description of data (how students will access them, how large, etc.)

3) Ways to communicate with you over the course of project (e.g., use a Slack group, each project team in a separate private Slack channel)  

https://poloclub.github.io/cse6242-2019fall-campus/project.html


Create a Sankey chart with a return flow:
https://www.sciencedirect.com/science/article/pii/S0921344917301167
-->






