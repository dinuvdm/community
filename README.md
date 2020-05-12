<h1 class="h1-home">Community Model&nbsp;Building</h1>

Prep for the EPA's sustainable community model building virtual events in 2020.   

<!--
Supply chain "License to Operate" with the support of the community.

### Code for Atlanta Projects  

Slack #epa

<b>1. Teams</b>: Brainstorm Projects - [Review maps and charts](tools/), [Review inventory exchange](tools/#places)   

<b>2. GitHub</b>: Experiment with [GitHub Packages](https://help.github.com/en/github/managing-packages-with-github-packages/about-github-packages#supported-clients-and-formats)  
  Is it possible to pull just the [community](https://github.com/datascape/community) "tools" folder into [model.georgia](https://github.com/datascape/model.georgia) repo?   

<b>3. Leaflet</b>: [Place a round image](https://github.com/ilyankou/Leaflet.IconMaterial/issues/3) over a [Leaflet.IconMaterial](https://github.com/ilyankou/Leaflet.IconMaterial) map point, which allows for color assignment. [Test here](/community/hubs).   
-->


<!--
	https://www.wrld3d.com/wrld.js/latest/docs/leaflet/L.DivIcon/
-->
 


[Starter samples](samples/) and [datasets](https://github.com/modelearth/community) for integration with the [US Environmentally-Extended Input-Output (USEEIO)&nbsp;API](https://github.com/usepa/useeio_api/wiki/Use-the-API).  

---

### Fall 2020

<a href="challenge" style="font-size:18px">2020 Sustainable Commuities Web Challenge</a>  

$10,000 in awards! Join a project at <a href="https://www.meetup.com/codeforatlanta/">Code for Atlanta</a> with [Code for America](https://www.codeforamerica.org/) 


### Overview

1. A collection of [EEIO widgets](https://modelearth.github.io/eeio/charts) is being created using the [USEEIO API](https://github.com/usepa/useeio_api/wiki/Use-the-API). Charts are loaded from JSON files [generated](resources/useeio) 
for Goods & Services demand vectors (Food System and Full System). 

2. Detailed [Goods & Services Report](samples/dataset) with economic value and environmental impact of production choices.   

3. [Maps of products and industries](samples/maps) - Regional hubs, industries by zipcode.  

4. [Visualizations](samples/charts/) of material flow and regional input-output.  


### Dev Areas

1. [Data visualizations](samples/dataset/) displayed from [static csv files](samples/dataset/USEEIOv1.2_result_2007_impacts_final.csv) - [exported from the USEEIO API](resources/useeio/) with [Python scripts](resources/useeio/python/produceUSEEIOimpactcsv.py). 

1. Preprocess data using the [uszipcode programmable database (Python)](https://uszipcode.readthedocs.io/01-Tutorial/index.html) - [Github](https://github.com/MacHu-GWU/uszipcode-project).  

1. Update CSV files on employment and industries for D3 charts using [Census industry data](industries) and [income by zcta](prep/all)<!--[projections](prep/regression/)-->.  

1. Add D3 heatmap colors by row to USEEIO data on [Goods & Services Report](samples/dataset) - [sortable version](samples/dataset/sortable.html).

1. Add cascading category toggle to [Goods & Services Report](samples/dataset). 

1. Display [Farm Fresh - Federal USDA location data](farmfresh/ga) on Leaflet map - initially merged for Aglanta.  

1. Use [PWA Starter](resources/pwa) to add an index.htmml page and thumbnails to the pwa folder.

1. Display [Georgia Recycling data](recycling/ga/) in Leaflet map layers.

1. Display industry and demographic data on [zip search](zip/#zip=30315) and [zip map](zip/leaflet/) below [Census Reporter map](https://censusreporter.org/profiles/86000US30313-30313/).

1. Use a [JAMstack Editor](https://headlesscms.org/) to edit content on GitHub. 
And/or <a href="https://www.apollographql.com/docs/apollo-server/">Apollo</a> GraphQL for faster dev than<!--the point-to-point nature of--> REST endpoints.  

1. Highlight <a href="../community/tools/#data">Smart & Sustainable Communities</a> on Leaflet map. 
Document Georgia Technology <a href="samples/routing/">driving tour routes</a>.

1. Deploy Leaflet in Widget. Include [windy.com](https://windy.com) weather layer using their [API for Leaflet](https://github.com/windycom/API).

1. Cross-relate Goods & Services NAICS industries with Harmonized System (HS Codes) for [International Trade](https://georgiadata.github.io/display/products/)

1. [Jobs and Economic Development Impact (JEDI) models](https://www.nrel.gov/analysis/jedi/models.html) - convert from Excel to an interactive Web Page

1. Use the [Install Notes](resources/censusreporter) for our [fork of Wazimap]( https://github.com/modelearth/wazimap) - a Python 3.0 version of [Census Reporter](https://censusreporter.org/profiles/86000US30313-30313/).  


<!--
International postal codes
https://pypi.org/project/zipcodes/

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

<!-- https://simapro.com/products/exiobase-database/-->
[EXIOBASE database](https://www.exiobase.eu/) - Registration is free for downloading files  

[ImPlan Impact Analysis](https://implanhelp.zendesk.com/hc/en-us/articles/360039284273-Environmental-Data) - 8 broad categories using USEEIO model data  


<!--
USCSD Materials Marketplace - Seems to be members only. Wes has a contact that worked on it.
https://usbcsd.org/materials

Southern Regional Science Association
http://www.srsa.org/
-->

<br>

## Team Projects

<a href="https://poloclub.github.io/#cse6242">Georgia Tech Data and Visual Analytics</a>  
Data science students are contributing new data visualizations during Spring 2020 coursework.  



<!-- Re-connect with Polo in early January. Provide: 

1) Description of problem (e.g., high level problems, opportunities for ML, vis, the combination, etc.)

2) Description of data (how students will access them, how large, etc.)

3) Ways to communicate with you over the course of project (e.g., use a Slack group, each project team in a separate private Slack channel)  

https://poloclub.github.io/cse6242-2019fall-campus/project.html


Create a Sankey chart with a return flow:
https://www.sciencedirect.com/science/article/pii/S0921344917301167
-->






