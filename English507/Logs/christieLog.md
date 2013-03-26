#Mar25
##Worked on tactile map worlfow
* Produced displacement map from map scan (imported into Photoshop>exported layer with highest contrast>increased contrast of layer and saved as .tiff).
* Sculped plane in Mudbox using displacement map.
* Scaled map to emphasize sculpted features.
* Sculpted temporal deformations using bulge tool. I referenced Katie's quantified temporality data in order to scale the deformations appropriately.
* Exported prototype from Mudbox as turntable movie and uploaded to Google Drive.

#Mar24
##Worked on georeferencing historical maps
* Installed ArcGis (trial edition).
* Imported historical map image and used georeferencing tool to geolocate map.
* Exported as GeoTiff and .gif files.

##Worked on streaming maps using geoserver
* Configured WMS on geoserver.
* Added neatline workspace.
* Added .gif file as stores (the GeoTiff data from ArcMap appears to be formatted in a way that GeoServer doesn't like--so it refuses to import the GeoTiff files).
* Converted .gif stores into layers.
* Streamed layers from geoserver to nealine maps using WMS.

##Issues with map streaming
* Geoserver doesn't play nice with ArcGis GeoTiffs (partially resolved by using .gif instead).
* Neatline wasn't pulling the maps from Geoserver (resolved by adding /wms? to GeoServer URL).
* The coordinates for the maps I'm streaming from Geoserver are wrong. My historical map layers are showing up in the wrong locations (unresolved).

##Next steps
* Try GIS work with another Gis program (instead of ArcGis). I'm currently looking at GRASS GIS.
* Look into geoserver hosting. I remember stumbling across free trail hosting for 30 days on a geoserver site. I need to track that down again.

#Mar23
* Still no work from helpdesk. No surprise. We'll use the local instance of Neatline for our final draft iteration.
* On the problem of historical maps: the issue with deploying them as items is that they will be improperly georeferenced if we take this approach.
* Downloaded and installed local instance of geoserver. Installed Neatline Maps.
* Looked at documentation for GIS work needed to prepare historical maps for neatline. This is something we could most likely do. That said, if we cannot use an instance of an online geoserver for our final project (and this will only ever run locally), then we should not spend time doing GIS work now. If we're able to access or deploy an online geoserver, we could certainly come back to this.

#Mar21
* Received reply from sysadmin directing me to helpdesk. Requested db creation.
* Looking into working with map layers in Neatline. Requires a geoserver and (I believe) some GIS work to locate our historical maps. This may fall beyond the current scope of our project, so implementing the map layers as neatline records seems like the most feasible solution at present.

#Mar20
* Looked into sqlite for installing Omeka on webspace. No go.
* E-mailed sysadmin to request access to MySQL db through phpmyadmin.

#Mar 19
##Met with Katie
* Two options for web hosting: getting mysql on my webspace (via mysql lite or requesting acces through uvic php).
* Will we have to do GIS for map layers?
* locate assets (objects) for Neatline map,
* A bit more work to do on method for quantifying temporality (largest issue is how much time we have to implement the method we set).

#Mar 12
##Experimented with Neatline
* Installed Omeka on my local MySQL server.
* Installed Neatline plugin for Omeka (I discovered that Neatline currently *does not* work with Omeka 2.0. Version 1.5 is needed instead.)
* Experimented with importing and displaying placemark data from our .kml files.
* As Katie and I discussed, the main constraint of Neatline is that it doesn't allow us to use anachronistic map layers to frustrate traditional cartographic representation. That is, items and layers can (as far as we know so far, anyway) only be viewed chronologically. (The start and end visible date fields *may* provide a way around this.)


#Mar 4-5
##Generated draft of Tactile Map using Mudbox
#Worklfow

* Stitch scanned images of historical map using Photoshop

* Create plane in Mudbox
* Overlap stitched map using Projection tool ![](https://docs.google.com/file/d/0BwJCaLpJjnXccmpRRTdsdHlOZFk/edit)
* Use sculpt tool to deform plane (elevations represent larger temporal)
![](https://docs.google.com/file/d/0BwJCaLpJjnXcQTV3cVJlUHdKYTg/edit)
![](https://docs.google.com/file/d/0BwJCaLpJjnXcSmVVMmU0cGFIaVU/edit)
* Export movie of map using Render>Create Turntable Movie
* Export layer as .stl file for printing

* see video of prototype [here] (https://docs.google.com/file/d/0BwJCaLpJjnXcLWJXaEJ6cHhUcDQ/edit )

##Revised documentation
* christieNeedsAssessment.md
* christieLog.md
* ChristieTanigawaIterationOne.md

#Mar 2-3
##Stitched scanned maps using Photoshop
* The sections of the map don't align perfectly when I stitch them
* I like the fact that the correspondence is imperfect--the breakages and anachronisms reveal the image's status as representation

##Overlaid maps on Dublin using Google Earth
* This is particularly difficult since I'm unfamiliar with the geography of Dublin
* The layers are currently not perfectly aligned with the base layer provided in Google Earth. This will take further work; for the time being, I do like the fact that these slight anachronisms frustrate the map's status as a reliable representation of geographic space.
* Trying to align the maps requires stretching and skewing them to fit Google's base layer.
* We want users to be able to drill down through the layers using each place mark,   to see how that item resonates historically (although this admittedly relies on the false assumption that the map layers represent history, rather than being historicized representations).

##Generated Test place marks with images
* Martello tower
* Sweny's pharmacy

##Exported layers and placemarks as .kml files

##Next steps
* Generate more place marks
* Read documentation on Google Maps API to determine how we will make this map available online
* Think through the links between the tactile map and the Google Map (both maps digitize Dublin through different modes of 'digital' representation).


#Data Model
##Three components
* Data for items that appear in exhibit (ask 560 folks to input this data—saves time)
* Data for temporality (character count/total char. count)
* Do we need a data model for : historical maps & tactile maps??
