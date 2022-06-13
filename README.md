# UFOs

## Overview of the Analysis:

The purupose of this analysis was to be able to display UFO sighting data clearly in a webpage and also allow the person using the web page to enter different filters based off criteria they wanted to see.

## Results:

By updating our app.js and our html files we were able to create a webpage with multiple UFO search criteria options. As seen in the image below we have the following filter search criteria options:
- Date
- City
- State
- Country
- Shape

When entering criteria into one or multiple filters the page will automatically return all UFO sightings that fit that criteria on the right hand side of the page. In the image below we can see all UFO sightings for Colorado. 

![image description or alt text](https://raw.githubusercontent.com/charlotterotner/UFOs/main/UFO_page_CO.png)

## Summary:
One drawback of this webpage for the purposes of UFO analysis is that the filter searches are unrestricted text boxes. Someone could enter a criteria that they would like to filter by and it could return 0 results, just because they didn't enter the criteria on the exact way the data is set up. For example, if someone typed "California" in the state filter it would not return any UFO sighting results, while "ca" would.

There are a number of things we could do to make this webpage better. For one, we could add an additional filter search to show duration so users could enter a number of minutes. This would return UFO sightings based off the amount of minutes they lasted. Additionally, we could update our code so the filter searches showed a dropdown instead of a textbox. This way web page users would be able to see all possible options for each filter before selecting one and they wouldn't be at risk for misspelling and getting false negative results returned. 

