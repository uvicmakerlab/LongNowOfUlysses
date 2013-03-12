##Changing from Google Maps to Exhibit

I have been making further progress in implementing the technological shift from Google Maps (using Spreadsheet Mapper 3.1) to SIMILE's Exhibit. I have cleaned up my data (e.g. merging Latitude and Longitude into one parameter, with the values being separated by a comma) and thus arrived at the following spreadsheet paradigm, influenced by the [data model](https://spreadsheets.google.com/pub?key=0Au7lliaEmIOcdDJrc0VybWU0bTN2NndwUmtKc0t5ZGc&hl=en&output=html) used for [Anouk Lang's project on John Glassco's Memoirs of Montparnasse](http://aelang.net/projects/glassco.htm): 
![](https://dl.dropbox.com/u/11381261/NetworkedUlyssesNewDataModel.png) 
The new labels for sorting, arranging, and searching the data are: {label}, {network}, {LatLng}, {person}, {description: single}, {reference: url}, {image: url}, {start: date}, and {end: date}. Using a [tutorial on Exhibit](http://www.simile-widgets.org/wiki/Getting_Started), I learned how to write a short HTML file in my text editor that directly gets the data feed from the spreadsheet:
![](https://dl.dropbox.com/u/11381261/CodeSimpleExhibit.png)

Once this .html file is dragged into the browser it immediately merges with the data from the spreadsheet to arrive at the following simple view:
![](https://dl.dropbox.com/u/11381261/ExhibitSimpleView.png)
In anticipating future interface issues I have already written a bit of code that activates a search function and allows me to sort my data by network and person; the first is necessary to enable a network-only view; the second sorting function will probably become necessary because I anticipate multiple entries for one particular person, e.g. Joyce or his brother Stanislaus. Exhibit does this through different "facets," e.g. for sorting, filtering, etc, that must be activated individually in the .html file.   

 
