# Bring Banks

## Data Representation and Querying Project 2015

### Keith Langan

## Introduction

This project provides the design and documentation for the datasets "Bring Banks"
which is available at https://data.gov.ie/dataset/bring-banks
Although the data is only based on information from the Fingal county council I have suggested to data.gov.ie to upload other datasets of all major cities in the Fiangal county council's format.

The type of users I imagine would use the app are people who are concerned about the enviroment or have a surplus of recyclables in their household.

### About the data

This dataset was received in Comma Separated Values (CSV) format, and was downloaded from https://data.gov.ie/dataset/bring-banks.
The CSV file contains 80 rows, the first being a header row with the names of each field.

There are ten values on each line, which are as follows:

>    * id: the id of the row //primary key?
>    * GIS_ID: //Primary Key?
>    * ELECTORAL_AREA: 
>    * LOCATION: location
>    * AREA: district
>    * GLASS: true/false
>    * CANS: true/false
>    * TEXTILE: true/false clothes/fabric
>    * LAT: Lattitude
>    * LONG: Longtitude

##Design Idea##

The app should be user friendly, therefore I am thinking of using only 2 windows. 

###MENU###

Below is a link to a png file of a template I designed:

[Main Menu](https://cloud.githubusercontent.com/assets/8780936/10644662/c16f5df0-7821-11e5-9c0c-a085f82fa7a1.png)

The app should open straight to the menu, where you have 2 options:
####Area####
 
This would consist of a drop down list where you choose what area you are in.
 
####Materials####

This would consist of a drop down list where you choose what materials you want to recycle.

###RESULT###

Below is a link to a png file of a template I designed:

[Result](https://cloud.githubusercontent.com/assets/8780936/10644566/494ae54c-7821-11e5-8d50-8372affcca19.png)

This page will consist of the data including:

>    * Area (String)
>    * Location (String)
>    * Glass: True/False
>    * Cans: True/False
>    * Textiles: True/False

####MAP####

The App could also have a map considering that there are co-ordinates in the 'Latitude' and 'Longtitude' column's which could be accessed by clicking on the location section in the results page

###URL's###

####List of bring banks in a given area####
This will give a list of the bring banks in a given area. it will also show what materials the bring bank accepts

```markdown
*http://bringbanks.com/area/[area]*
where you replace [area] with the location.
For example, the URL:
*http://bringbanks.com/area/swords*
will return a list of bring banks located in swords.
```

####List of bring banks that accept glass####
This will give a list of the bring banks that accept glass. It will also show what other matreials are and their locations.

```markdown
*http://bringbanks.com/glass/[glass]*
where you replace [glass] with the glass.
For example, the URL:
*http://bringbanks.com/glass*
will return a list of bring banks that accept glass.
```

####List of bring banks that accept cans####
This will give a list of the bring banks that accept cans. It will also show what other matreials are accepted and their locations.

```markdown
*http://bringbanks.com/cans/[cans]*
where you replace [cans] with the cans.
For example, the URL:
*http://bringbanks.com/cans*
will return a list of bring banks that accept cans.
```

####List of bring banks that accept textiles####
This will give a list of the bring banks that accept textiles. It will also show what other matreials are accepted and their locations.

```markdown
*http://bringbanks.com/textiles/[textiles]*
where you replace [textiles] with the textiles.
For example, the URL:
*http://bringbanks.com/textiles*
will return a list of bring banks that accept textiles.
```

####List of bring banks in a given area that accept glass####
This will give a list of the bring banks in a given area that take glass. It will also show what other matreials are accepted and their locations

```markdown
*http://bringbanks.com/area-glass/[area]glass*
where you replace [area] with the area.
For example, the URL:
*http://bringbanks.com/location-glass/swords-glass*
will return a list of bring banks located in swords that accept glass.
```

####List of bring banks in a given area that accept cans####
This will give a list of the bring banks in a given area that take cans. It will also show what other matreials are accepted and their locations

```markdown
*http://bringbanks.com/area-cans/[area]-cans*
where you replace [area] with the area.
For example, the URL:
*http://bringbanks.com/area-cans/swords-cans*
will return a list of bring banks located in swords that accept cans.
```

####List of bring banks in a given area that accept textiles####
This will give a list of the bring banks in a given area that take textiles. It will also show what other matreials are accepted and their locations

```markdown
*http://bringbanks.com/area-textiltes/[area]-textiltes*
where you replace [area] with the area.
For example, the URL:
*http://bringbanks.com/area-textiles/swords-textiles*
will return a list of bring banks located in swords that accept textiles.
```

####An example of a URL that would be country wide####

```markdown
*http://bringbanks.com/[county]/[town/city]/[area]*
For example, the URL:
*http://bringbanks.com/Galway/Galway/Renmore*
will return a list of bring banks located in Renmore.
```


The clip arts I used in the result window, I found at the following website:
> https://openclipart.org/
