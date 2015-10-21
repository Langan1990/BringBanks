# Bring Banks
## Data Representation and Querying Project 2015
### Keith Langan

## Introduction

This project provides the design and documentation for the datasets "Bring Banks"
which is available at https://data.gov.ie/dataset/bring-banks
Although the data is only based on information from the Fingal county council I have suggested to data.gov.ie to upload other datasets of all major cities in the Fiangal county council's format

## About the data

This dataset was received in Comma Separated Values (CSV) format, and was downloaded from https://data.gov.ie/dataset/bring-banks.
The CSV file contains 80 rows, the first being a header row with the names of each field.

There are ten values on each line, which are as follows:

>    * id: the id of the row//primary key
>    * GIS_ID: ???
>    * ELECTORAL_AREA: ???
>    * LOCATION: location
>    * AREA: district
>    * GLASS: true/false
>    * CANS: true/false
>    * TEXTILE: true/false clothes/fabric
>    * LAT: Lattitude
>    * LONG: Longtitude

##Design Idea##

The app should be user friendly, therefore I am thinking about using only 2 windows. 

###MENU###



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
This will give a list of the bring banks that accept glass. It will also show what other matreials are and their locations.

```markdown
*http://bringbanks.com/glass/[glass]*
where you replace [glass] with the glass.
For example, the URL:
*http://bringbanks.com/glass*
will return a list of bring banks that accept glass.
```

###List of bring banks that accept cans###
This will give a list of the bring banks that accept cans. It will also show what other matreials are accepted and their locations.

```markdown
*http://bringbanks.com/cans/[cans]*
where you replace [cans] with the cans.
For example, the URL:
*http://bringbanks.com/cans*
will return a list of bring banks that accept cans.
```

###List of bring banks that accept textiles###
This will give a list of the bring banks that accept textiles. It will also show what other matreials are accepted and their locations.

```markdown
*http://bringbanks.com/textiles/[textiles]*
where you replace [textiles] with the textiles.
For example, the URL:
*http://bringbanks.com/textiles*
will return a list of bring banks that accept textiles.
```

###List of bring banks in a given area that accept glass###
This will give a list of the bring banks in a given area that take glass. It will also show what other matreials are accepted and their locations

```markdown
*http://bringbanks.com/location-glass/[location]glass*
where you replace [location] with the location.
For example, the URL:
*http://bringbanks.com/location-glass/swords-glass*
will return a list of bring banks located in swords that accept glass.
```

###List of bring banks in a given area that accept cans###
This will give a list of the bring banks in a given area that take cans. It will also show what other matreials are accepted and their locations

```markdown
*http://bringbanks.com/location-cans/[location]-cans*
where you replace [location] with the location.
For example, the URL:
*http://bringbanks.com/location-cans/swords-cans*
will return a list of bring banks located in swords that accept cans.
```

###List of bring banks in a given area that accept textiles###
This will give a list of the bring banks in a given area that take textiles. It will also show what other matreials are accepted and their locations

```markdown
*http://bringbanks.com/location-textiltes/[location]-textiltes*
where you replace [location] with the location.
For example, the URL:
*http://bringbanks.com/location-textiles/swords-textiles*
will return a list of bring banks located in swords.
```
