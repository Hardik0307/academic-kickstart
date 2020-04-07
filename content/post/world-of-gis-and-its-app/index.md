---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "World of GIS and Its Applications"
subtitle: ""
summary: ""
authors: []
tags: [GIS,Geospatial,Visualization,Data Science]
categories: []
date: 2020-04-07T17:46:36+05:30
lastmod: 2020-04-07T17:46:36+05:30
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---


> _“Impossible to map the world–we select and make graphics so that we can understand it” ~_ **Roger Tomlinson**

Don't google , **Roger Tomlinson** was an English geographer and the primary originator of modern computerised [geographic information systems](https://en.wikipedia.org/wiki/Geographic_information_system "Geographic information system") (GIS), and has been acknowledged as the **father of GIS.**

Before let's see our TODO.
- [ ] What is GIS ?
- [ ] Geospatial data
- [ ] Types of data in GIS
- [ ] Application of GIS software
- [ ] Available software in Market

Try to check that box! <br/> 
That's power of the markdown. <br/>
Anyways let's start. :smiley:

### What is GIS??

- A **geographic information system** (**GIS**) is a system designed to capture, store, manipulate, analyze, manage, and present **geospatial** data.
 
-  GIS applications are tools that allow users to create interactive queries (user-created searches), analyze spatial information, edit data in maps, and present the results of all these operations.

### Wait but what is geospatial data??

The term geospatial is relatively new and has been gaining popularity since the 1980s. Data which contains geographic content in it is classified as geospatial data. This includes coordinates, postal codes, city, or address. But only coordinates are not enough to understand the whole dataset. There must be some notation about that coordinates, for example, the name of the location which the coordinates represent. We call it _attribute data_.

Not getting? Have a look at data.
   
| VOLCANX020 | NAME | LOCATION |LATITUDE  | LONGITUDE |
|--|--|--|--|--|
|509  | Baker | US-Washington | 48.7767982 | -121.8109970   |
| 511 | GlacierPeak | US-Washington | 48.1118011 | -121.1110001  |
| 513 | Rainier | US-Washington  | 46.8698006 | -121.7509995   |

Here, the number and name of the volcanoes are attribute data and the location, latitude, and longitude are geospatial data. 


### Types of data in GIS
 - Vector data<br/>
	 Vector data consists of individual points which are stored as pairs of (x,y) coordinates. These points further can be joined in a particular order to create lines or joined in closed rings to create polygons.
	 
	1.  Point data<br/>
		**Point data** is commonly used to represent separate data points and nonadjacent (not next to each other) features. To represent point data we can use the radius and different colors to differentiate features from each other.
		**Example** is maps with point/marker on it.
		
	2.  Line data<br/>
		**Line data** is, of course, used to represent linear features. These features have both starting and ending points. We commonly use solid lines versus dotted lines or a combination of colors or even line thickness to distinguish features from one another. 
		**Primary examples** would be roads, rivers or metro lines. 

		![from GIS map](https://www.igismap.com/wp-content/uploads/2019/02/line.gif)
	3.  Polygon data<br/>
		When lines are connected into enclosed shape then this type of data termed as polygon data. Polygon should be closed. The start and end point should have the same coordinates. 
		**Examples** of vector polygon feature are school boundary, city or any political line.
		  ![HDI](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0f/Indian_States_%26_Union_Territories_by_HDI_%282018%29.png/393px-Indian_States_%26_Union_Territories_by_HDI_%282018%29.png)
		  HDI(Human Development Index) in India Polygon data.
 - Raster data <br/>
    its simplest form, a raster consists of a matrix of cells (or pixels) organized into rows and columns (or a grid) where each cell contains a value representing information, such as temperature. Rasters are digital aerial photographs, imagery from satellites, digital pictures, or even scanned maps.
![Raster data](https://docs.safe.com/fme/html/FME_Desktop_Documentation/FME_ReadersWriters/!FME_Geometry/Images/raster.png)

Now what to discuss:
- [x] What is GIS ?
- [x] Geospatial data
- [x] Types of data in GIS
- [ ] Application of GIS software
- [ ] Available software in Market

Let's jump into GIS applications.

### GIS Application
Many disciplines can benefit from GIS technology.
Usage in fields of,
- Science
- Government 
- Business
- Industry
#### Aplication includes,
-  Real estate
-  Public health 
-  Crime mapping 
-  National defense
-  Sustainable development 
-  Natural resources
-  Climatology
-  Landscape architecture
-  Archaeology regional and community planning, transportation and logistics

Let me put it into GIS.

- So in 2010,  **Kerala Police** planned **GIS Based Crime mapping**. 
The Police Department will be developing a GIS-based crime mapping facility for effectively managing the data pertaining to law and order and thereby to make intelligent decisions with emphasis on spatial logistics and patterns.
[Detailed]([https://www.newindianexpress.com/states/kerala/2010/jul/02/kerala-police-plan-gis-based-crime-mapping-166437.html](https://www.newindianexpress.com/states/kerala/2010/jul/02/kerala-police-plan-gis-based-crime-mapping-166437.html))
<br/>How cool is that!

- Climate scientists work with thousands of data sets every day, often cross-checking, merging, morphing and manipulating it into something useful. Whether that is for academic or government reports, or for any decision makers who cannot make sense of raw data and need it transformed into something they can work with or use as supporting evidence . GIS is the technology of problem solving and geographical data - a data set with which climate scientists work most often - presents many problems.

![Data](http://wiki.gis.com/wiki/images/a/aa/Annual_Average_Temperature_Map.jpg)

- During **virus spread or health issue**, to track it.
Example, recently **Washington universty** tracking COVID-19 spread in world:<br/>
[Visit this](https://hgis.uw.edu/virus/)

### Available softwares 
-  ArcGIS (Esri)
-  MapInfo Professional (Pitney Bowes)
-  Geomedia (Hexagon Geospatial)
-  Global Mapper (Blue Marble)
-  Manifold GIS (Manifold)
-  Smallworld (General Electric)

So download it load data and map the world! **if possible surely make post on GIS databases**, but for now have a look on this:

![](https://miro.medium.com/max/1400/1*YIwx2jh66NdWqF-GpBTwCA.gif)
A week of flights in Brazil. Original file was just a csv with origin and destination coordinates. I loaded the data to PostGIS(GIS database), created point geometries from the coordinates, then created lines between the points and eventually visualized the data with QGIS Time Manager.


Happy to hear your feedback/criticism.<br/>
Stay Safe and Hydrated!

