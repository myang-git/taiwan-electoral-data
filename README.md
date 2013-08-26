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
