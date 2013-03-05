#Dislocating Ulysses

# Needs Assessment
## Working Title: Dislocating Ulysses
## Project Description: 

### Project 1 Description
This portion of the project rethinks a linear progression of both space and time by situating Ulysses in a past and present Dublin. For the first segment, three [historical maps of Dublin](http://voyager.library.uvic.ca/vwebv/holdingsInfo?bibId=2283456) from the UVic Library's Special collection, including a map of Dublin during the Anglo-Norman invasion that situates Ulysses’ Dublin in a long colonial history, an 1876 map, and a 1925 map that represents Dublin around the time of Ulysses’ publication, are layered over one another to give a sense of how the path of the novel translates through time. The project will also map objects in the exhibit that represent objects locateable in Ulysses’ Dublin in order to re-situate the dislocated objects in their geotemporal location as suggested by the novel. 

### Project 2 Description
The second component of the project represents the time spent in each place relative to the amount of time the novel is situated in specific areas of Dublin. Using a scanned image of Special Collection's 1925 Dublin map, we will 3D model the map using Mudbox to render the map malleable to distortion. We will then raise the topography of the map in proportion to the number of words locatable in a region in Dublin over the number of words in the novel (roughly 265,000).  To determine this proportional relation, the number of total words in the novel are divided by the number of words anchored in a specific area of Dublin.  

## List of Materials: 

### Software: 
Google Earth
Mudbox 

### Documents: 
* Physical [maps of Dublin in Special Collection] (http://voyager.library.uvic.ca/vwebv/holdingsInfo?bibId=2283456) 
* OCR of 1922 edition of Ulysses
* Acquisition List from 560
(https://docs.google.com/forms/d/1s2x6fDXLZdqvK7QKayPYWm0JuYo0FuCbh4NIl9M5mkM/viewanalytics )

### Data: 
* a chart of the journey in Ulysses
* the total words count in the 1922 edition
* a division of the novel based on place and a calculation of words locatable in each place-based segment or a detailed timeline of the novel's movement through Dublin
* a list of the exhibit objects and a list of where the text locates these objects in Dublin (where applicable)

##Bibliography
*[Lovecraft in Providence](http://lovecraft.scholarslab.org/neatline-exhibits/show/lovecraft-in-providence/fullscreen)
*[The Knotted Line](http://knottedline.com/) (for creating navigable, interactive environments), Alain Liu, “Transcendental Data”
[*Media *Archaeology*](http://books.google.ca/books?id=aSlQ8z1uslwC&printsec=frontcover&dq=media+archaeology&hl=en&sa=X&ei=FfQHUcicNcSQiALProGADQ&redir_esc=y) Ed. Erkki Huhtamo.
* Khadem, Amir. [“Annexing the unread: a close reading of 'distant reading’.”](http://link.springer.com.ezproxy.library.uvic.ca/article/10.1007/s11059-012-0152-y/fulltext.html) Neohelicon. 39:2 (2012). 
* MacDonagh, Donagh. ["Ulysses: Map of Dublin."](http://voyager.library.uvic.ca/vwebv/holdingsInfo?bibId=2619075) Dublin: Signa Ltd.: 1963. 
* Moretti, Franco. ["Conjectures on World Literature."](http://newleftreview.org/II/1/franco-moretti-conjectures-on-world-literature) New Left Review. Feb. 2000.
* Moretti, Franco. [Graphs, Maps, Trees: Abstract Models for a Literary History.](http://voyager.library.uvic.ca/vwebv/holdingsInfo?bibId=1386108) London: Verso. 2005.  
* Benjamin, Walter. ["On the Concept of History."](http://www.marxists.org/reference/archive/benjamin/1940/history.htm) 
* [The Spatial Humanities: GIS and the Future of Humanities Scholarship.](http://voyager.library.uvic.ca/vwebv/holdingsInfo?bibId=2181054) Ed. David J. Bodenhamer, et al. Bloomington: Indiana UP. 2010.

##Scope
Temporally, the project spans 1400 to 2013 and is spatially located in Dublin. The online Google Map will represent temporality across different time periods, by mapping items from the Year of Ulysses exhibit in 2013 on three layered historical maps (from 1540, 1876, and 1925). The tactile map will represent shift in temporality within Joyce's 1904 Dublin.


##Deliverable
An interactive Google Map embedded in a webpage that allows users to switch between the three historical maps as layers and locate items from the Year of Ulysses exhibit in the geography (and changing time periods) of Dublin. The tactile map will deliver a printed 3d map that 'digitizes' the temporality of Joyce's Dublin by feeling deformations in elevation to the terrain of Dublin (which correspond to the time spent reading narrative events which occur in each area of the city).

##Risks and Constraints
The largest risk is that our online map will not be interoperable with the other Google Maps from 507. Other risks are that users will find it difficult to read the historical maps; they may be able to see changes to Dublin over time, but may have difficulty seeing how areas change over time (this is largely a result of the detail of each map being different). The largest constraint for representing temporality using the tactile map is that word count indicates time spent reading each section of the novel, rather than the amount of time each scene in the novel represents. However, since measures of narrative temporality are inherently subjective, using word count as a metric for time spent reading provides a consistent and quantitative methodology for representing the *reader's* rather than the character's temporal experience of the city.

#Benefits
Our maps could ideally be modified repurposed, and expanded by others. Additionally, our datasets (including Joyce’s correspondance and the novel’s afterlives) will likely be incomplete, leaving room for future contribution. Our workflow could also be replicated to produce other maps for the exhibit space (those currently being proposed in 560). Other projects could replicate our workflow to produce similar maps/layers that could be connected to our Google Map. This would open a space for scholars to collaboratively map transnational networks (and then deconstruct the stable temporal and historical contexts in which those networks are immediately located). The tactile map provides a venue for working through alternative ways of digitizing maps, by rendering them tactile (digital) rather than digitizing them onscreen.

##Timeline
###Feb. 11: Collect list of items for exhibit, have scanned images of 19th century map and data from text analysis of the novel for time/space representation
###Mar. 4: Have working prototype for small section of map
###Mar 11:
*Produce second iteration of Layered Maps (Google Earth) and tactile map (Mudbox)
###Mar 18:
*Commit final draft of 3d map in Mudbox (ready to be exported as .stl file)
*Commit final draft of layered maps (with placemarks) in Google Earth (ready to be exported using Google Maps API)
###Mar 25:
*Finish reading documentation on Google Maps API
*Prototype publishing Google earth map using API (https://developers.google.com/maps/documentation/javascript/styling, https://developers.google.com/maps/documentation/javascript/tutorial )
###April 7:
*Review final draft of tactile map (.stl file) and Google Map (using Google Maps API)
###April 16:
*Print tactile map
*Push Google Map to website

##Support
Katie and I may need help using Mudbox to represent geographic features from our digitized map on a 3d plane. Is the stamp tool the best solution for this? We will also need help printing the 3d model. Should we export our model from Mudbox as an .stl file?

We may need technical support as we work through the documentation for Google Maps Javascript API and use the API to publish an interactive version of our map (embedded in a website).

##Project Goals
*Produce a working, interactive map of Dublin that uses visual distortion and layered maps to move material from *Ulysses* beyond its immediate context in the novel (this argument must be articulated clearly in or map design). Goals for the map are:
*that visitors see and interact with it and that our interface
*the design clearly articulates our proposed theoretical intervention.

*Print a 3d map that uses distortions in map elevation to represent time spent reading narrative events that occur in each section of the city.

##Professional Development Goals
*One of my ongoing goals is to develop content using a workflow that accounts for both production and theoretical intervention (or, meaninigful connections between the technical and the theoretical). Successfully prototyping and delivering a product that uses interface to levarage arguments about the temporal experience of geography and the historical and political contexts for transnational literature would fulfill this goal.

*Working with Mudbox and Google Maps APIs to author deliverable 'digital' content.
