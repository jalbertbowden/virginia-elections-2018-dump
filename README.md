# Virginia Elections 2018 Data Dump  

Virginia elections 2018 precincts GIS data collection.

**virginia-precincts-2018-11-06** directory contains Virginia Precincts for 2018-11-06 election; original format .topojson, converted to .geojson and .shp.  
**2018-11-06-elections** directory contains various VPAP datasets used during 2018-11-06 election.  

## Individual Precincts Original Sources
![Screenshot of Partially Complete 2018 Virginia Elections Dataset](https://raw.githubusercontent.com/jalbertbowden/virginia-elections-2018-dump/master/2018-virginia-elections-precincts-partially-complete-screenshot.png)  

**json** directory is the original files found on AWS.  
**geojson-as-right-hand-rule directory** has been rewritten to adhere to the ["right hand rule"](https://mapster.me/right-hand-rule-geojson-fixer/) and passes as valid GEOJSON. this dataset is broken into **polygon** and **multipolygon** directories.  
**merged-as-multipolygons** directory has a merged dataset, where the polygon GeoJSON files have been converted into multipolygon for the sake of merging/having a completed dataset.

There are multiple precincts missing...
