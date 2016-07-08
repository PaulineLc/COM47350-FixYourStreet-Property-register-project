# COM47350-FixYourStreet & Property Price Register Project
Project realized for COMP47350 Data Analytics (University College Dublin) in collaboration with [harneyp2](https://github.com/harneyp2)

##Problem

Finding out whether all Dublin neighborhoods equally benefit from Dublin City Council resources when it comes to fixing common street problems (broken traffic light, graffiti, etc).

##Aim

Fairer distribution of public services. Determine if the fault reporting systems need to be better advertised or made more available in areas of social deprivation.

##Explanation

Most common street problems such as potholes or broken lights are now reported directly by the population through website like fixmystreets.ie. City councils monitor these websites in order to fix any issue reported. Our aim is to assess whether all neighbourhood receive an equal treatment depending on their wealth. We will assess each neighborhood's wealth based on the average house price in that neighbourhood.

##Data

**Street fix requests:** We aim to use the data from fixmystreet.ie. They have an API which provides the geographical location of a fault, the category of fault, report time, response time, etc.

**Property price:** we aim to use data from the property price register. They provide a CSV file with the list of properties bought and their price. Outliers in a geographical area will be removed and an average property price will be used as an indicator of wealth/prosperity.
