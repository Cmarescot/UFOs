# UFOs

## Overvew of Project 
### Purpose:
In this Analysis we helped Dana (a Data Journalist) create a HTML page that has includes information about UFOs sightings. This page includes a table and an article. Our job was to help with the creating of the websites. Specifically in the challenge we helped Dana create more filters to filter through the table based on criterias such as City, State and Shape. 

## Results 
### Using the Webpage:
Let's say a user is from the state or California and would like to get some information on UFO sightings in the state. The user would then use the Filter Search form by inputing (typing) "ca" (in that exact format) and then pressing enter. 
![caSearch](https://github.com/Cmarescot/UFOs/blob/main/static/images/caSearch.png) ![caSearchEnter](https://github.com/Cmarescot/UFOs/blob/main/static/images/caSearchEnter.png)

The user would then be able to see that there were quite a few UFO citings in the state and get some more information on those citings such as the shape of the UFO, the durating of the sighting and comments that were reported. 

Lets take a look at one:

![example](https://github.com/Cmarescot/UFOs/blob/main/static/images/example.png)

In this particular row we can see that there was a sighting on New Year 2010 (1/1/2010)in Le Mesa, where someone reported seeing "3 bright red lights hovering high in the sky in an elongated triangle pattern". Ouuu spooky right!

## Summary: 
### Drawbacks 
One drawback of this design is it's hard to go back and edit a search. You have to refresh the page to get a clean new slate and change the search that way. For example, lets say I filtred my data for the state of "ca" and a shape of "light". Cool okay got that filtered. But what if I want to go back and take out my light filter and just leave my "ca" filter . Even if I delete the data in the shape field and press enter my data will still show the results for both searches.
![drawback](https://github.com/Cmarescot/UFOs/blob/main/static/images/drawback.png) ![drawbackResult](https://github.com/Cmarescot/UFOs/blob/main/static/images/drawbackResult.png)

### Recommendations 
In the future:
1. Dana should look into fixing the drawback we discussed by making sure searches can easilly be updated without reloading the page
2. Dana can also think about returning the amount of signtings found for filtred data
3. Loosening up the criteria for the searches. For example is i type "ca" or "CA" I should still be able to get the same results. 
