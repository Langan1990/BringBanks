# BringBanks
## Data Representation and Querying Project 2015
### Keith Langan

## Introduction

This project provides the design and documentation for the datasets "Galway City Recycling Bring Bank Locations"
which is available athttps://data.gov.ie/dataset/bring-banks

## About the data

This dataset was received in Comma Separated Values (CSV) format, and was downloaded from https://data.gov.ie/dataset/bring-banks.
The CSV file contains 80 rows, the first being a header row with the names of each field.

There are ten values on each line, which are as follows:

>    * id: the id of the row
>    * GIS_ID: 
>    * ELECTORAL_AREA: 
>    * LOCATION: location
>    * AREA: district
>    * GLASS: true/false
>    * CANS: true/false
>    * TEXTILE: true/false clothes/fabric
>    * LAT: Lattitude
>    * LONG: Longtitude

##URL's##

###List of bring banks in a given area###
This will give a list of the bring banks in a given area. it will also show what materials the bring bank accepts

```markdown
*http://bringbanks.com/location/[location]*
where you replace [location] with the location.
For example, the URL:
*http://bringbanks.com/location/swords*
will return a list of bring banks located in swords.
```

###List of bring banks that accept glass###
This will give a list of the bring banks that accept glass. It will also show what other matreials are accepted

###List of bring banks that accept cans###
This will give a list of the bring banks that accept cans. It will also show what other matreials are accepted

###List of bring banks that accept textiles###
This will give a list of the bring banks that accept textiles. It will also show what other matreials are accepted

###List of bring banks in a given area with glass###
This will give a list of the bring banks in a given area that take glass. It will also show what other matreials are accepted

###List of bring banks in a given area with cans###
This will give a list of the bring banks in a given area that take cans. It will also show what other matreials are accepted

###List of bring banks in a given area with textiles###
This will give a list of the bring banks in a given area that take textiles. It will also show what other matreials are accepted
