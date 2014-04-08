Taiwan Electoral Data
====================

Electoral data collected from public domain. Preprocessed to machine readable format (currently JSON).

Data Files
====================
1. Electoral Districts for Legislator Election

  The file has the electoral districts for 2012 Legislator Election. Data is organized in the following hierarchy:
    * city
      * township / district
          * village
        
  If an entire township belongs to the same electoral district, the village will be set to null

2. Legislator

  The file has the information for current active legislators. Data is organized in the following hierarchy:
    * city
      * electoral district
          * legislator

Sources of Data
====================
[公民監督國會聯盟] (https://sites.google.com/site/ccwdata/monitoring/whosmylegislator)

[立法院全球資訊網] (http://www.ly.gov.tw/03_leg/0301_main/legList.action)

Links to Faceook are from Google search
