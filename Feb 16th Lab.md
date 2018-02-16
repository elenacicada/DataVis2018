---
title: "Tableau Lab "
author: "Elena Meyer and Leigh Barber"
date: "February 15, 2018"
output:
  html_document:
    keep_md: true
---




## Tableau Practice


Let’s start by using the AllCountries dataset, which can be downloaded using this link: 
http://www.lock5stat.com/datasets/AllCountries.xlsx

__1.__ Save the file to your Data Visualizations folder on your computer. 

__2.__ Import it into Tableau:


![](/Users/elena/Documents/Import.png)



##First, let’s make a map showing the average military spending by country. 

__1.__ Select the map function from the visualization options on the left. 

__2.__ Add the dimension __“country”__ into the box labeled __“marks.”__ 

__3.__ Next, drag the measure __“armed forces”__ to the box labeled __“color”__ in the marks box.

__4.__ Adjust the color gradient to be readable and intuitive (for instance, a simple color gradient). 

![](/Users/elena/Documents/Map.png)





****
__5.__ Change the measurement from the __sum__ of the military spending to the __average__ military spending.


![](/Users/elena/Documents/AVGBox.png)


##Let’s add some features to our map! 

Let’s say we want to add to properties noted in the the box which appears when we hover over each country to include the population. 

__1.__ Drag the measure __“population”__ into the box labeled __“tooltip”__ in the marks box.
![](/Users/elena/Documents/PopulationMap.png)


Now, let’s add a new visualization to our set. Let’s name our visualization "Armed Forces by Country.” Add a new sheet, and we'll make a new visualization…

##Your turn! 

1. First, try to reproduce this graphic: 

![](/Users/elena/Documents/CO2 by pop.png)

***

2. Hover over the grapic you made, and look at the tooltip (as shown below). Can you edit the tooltip to display the data as shown below? 
![](/Users/elena/Documents/CO2 by pop 2.png)

***

3. What do these numbers on the tooltip mean? Why, when we scroll over to some other countries, is the field "Energy Use" left blank? What are the units on these measurements? What is actually being measured. Go back to the original data source to investigate... 

**Hint: more information about the AllCountries dataset can be found on CRAN!** 

4. Using the information we found about the variables in the AllCountries dataset, what does this tell us about the graphic "Armed Forces by Country?" Is this title misleading? How might we update this visualization to better suit our goal of showing armed forces per capita?

**Hint: making new fields is really easy in Tableau, and very similar to Excel calculations!** 

##Intermediate questions: 

1. Update the graphic "Armed Forces by Country" based on your conclusions from the previous question. 

2. Update the graphic "CO2 by Country" to account for population as well. 


