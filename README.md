# **UFO Finder**
## **Overview**
The purpose of this analysis is to be able to effectively parse through and review UFO sightings using a variety of different criteria, including date of sighting, country, city, state and shape of sighting. 

## **Results**
The UFO Finder website is designed to filter UFO sightings by multiple criteria. The webpage is heavily filterable so that the viewer can narrow down and analyze results using several search criteria. Some examples of search criteria and data are listed below. Though this summary outlines a few options, search parameters are highly customizeable depending on the viewers goals for analysis. 

**1. Data can be filtered by location - state and city**
As seen in the snippet below, the webpage has the ability to be filtered by multiple criteria. In this example, UFO sightings could be narrowed by location. This could be a broad location analysis (i.e. by state) or one could create a more narrow scope and search by city. In the instance below, the webpage was filtered by city and state, though, if filtering by city, state criteria might not be necesarry. If, however, there are city names that exist in multiple states, it could be possible to apply the additional criteria. 

!["Filtered by Location"](https://github.com/mhenson1989/UFOs/blob/main/static/images/filteredlocation.PNG)

**2. Data can be filtered by datetime** 
Another option for filtering data would be by relative datetime. Within this data, it is likely that you would pull a larger subset of data, however, if your goal in your analysis would be to assess the frequency of UFO sightings on any given day in time, this might be a good starting place. In the snippet below, UFO sightings were filterd by the date: 1/4/2010.

!["Filtered by Date""](https://github.com/mhenson1989/UFOs/blob/main/static/images/filtereddate.PNG)

**3. Data can be filtered by shape**
Using the same data set from the datetime filter above, I would then notice the frequency of "light" shapes within my dataset. At this point, you could narrow your search even further to just analyze light shape UFO sightings. An example of this search is included below.

!["Filtered by Shape""](https://github.com/mhenson1989/UFOs/blob/main/static/images/filteredbyshape.PNG)

## **Summary**

*Major Drawback*
- Though I believe this website is helpful, one major drawback is the length and detail of the data set to be filtered and analyzed. Firstly, the UFO sightings data only utilizes data from 2010 (which is now highly dated). Additionally, the quality of the data is inconsistent, especially the comments. A more robust and clean data set might be a good next step if we wanted this website to have evergreen functionality.  

*Next Steps and Recomendations*
1. I would recommend addding back the filter button into the design, in addition to having the functionality of hitting enter. I think it's possible that review of certain data subsets is going unseen with the current filtering process and would be more clear to the user if the button existed. Additionally, I would add a "Reset Filters" button instead of having to manually delete and clear the filter fields, in order to optimize efficiency. 
2. Secondly, I would make the table a smaller box with a scroll function, as opposed to scrolling completely down the home page. I think this creates a cleaner look to the webpage and allows the user to scroll to the bottom of the page and navigate without having to scroll through the entire dataset. This will be especially helpful if this dataset ever grew. Additionally, if/when this dataset grows to include additional years, I would add a year filter, in addition to the datetime filter, for quick filter access. 