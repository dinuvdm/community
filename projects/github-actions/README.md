
## GitHub Actions Data Pipeline

We'll be developing a Python pipeline using [GitHub Actions](https://docs.github.com/en/actions) to add support for map layers with 30,000+ records, similar to Hack for LA's [Public Tree Map](https://neighborhood.org/public-tree-map/).  

Updates for [Farm Fresh - Federal USDA location data](../farmfresh) on maps - initially merged for Aglanta. 

Trigger our [FarmFresh Python](https://github.com/modelearth/community-data/tree/master/process/python/farmfresh) data pull nightly from the [community-data repo pipeline](https://github.com/modelearth/community-data/).  

Output [All the Places](https://www.alltheplaces.xyz/) into zip folders in our [zip/io/data repo](https://model.earth/zip/io/)<!-- generated by Kathryn Winglee. -->.  

**Our prior GitHub Actions samples**  
[Scrape city site and save json file using Python](https://github.com/abrie/atl-council-scraper) - Abrie  
[Pull from PDF to a CSV file using R script](https://github.com/bbrewington/ga.dph.data) - Brant and Abrie  