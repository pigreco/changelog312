# Changelog312
Changelog 3.12 București

![](imgs/splash_3_12.png)

---

##	QGIS Development Server Application
- **author**:	[elpaso](https://twitter.com/elpaso66)
- **merged**:	2020-01-24T17:56:37Z
- **tags**:	Feature;Needs Documentation;Server 
- ([REVERT](https://github.com/qgis/QGIS/pull/34124))
- **PR**:	[33921](https://github.com/qgis/QGIS/pull/33921)

##	MBTiles raster support in WMS provider
- **author**:	[wonder-sk](https://github.com/wonder-sk)
- **milestone**:	3.12.0
- **merged**:	2020-01-17T13:18:41Z
- **tags**:	Changelog;Feature
- **PR**:	[33855](https://github.com/qgis/QGIS/pull/33855)
- **Descrizione**:  This PR adds MBTiles tiled raster map support to WMS provider so that it uses the same code paths
like WMTS or XYZ tiles.

##	Add new algorithm: Detect Dataset Changes
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **milestone**:	3.12.0
- **merged**:	2020-01-16T06:35:51Z
- **tags**:	Feature;Processing
- **PR**:	[33832](https://github.com/qgis/QGIS/pull/33832)
- **Descrizione**:  This algorithm compares two vector layers, and determines which features
are unchanged, added or deleted between the two. It is designed for comparing
two different versions of the same dataset.

##	New algorithm "Rename table field"
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **milestone**:	3.12.0
- **merged**:	2020-01-15T08:56:11Z
- **tags**:	Changelog;Feature;Processing
- **PR**:	[33807](https://github.com/qgis/QGIS/pull/33807)
- **Descrizione**:  Takes an input layer, existing field and a new name for the field, and
outputs a new layer with the selected field renamed.

##	Show distance from GPS lock position to current cursor
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **milestone**:	3.12.0
- **merged**:	2020-01-15T08:55:28Z
- **tags**:	Feature;GPS
- **PR**:	[33780](https://github.com/qgis/QGIS/pull/33780)
- **Descrizione**:  When a GPS device is connected, whenever the user moves the cursor over the canvas a live status bar message displays the distance and bearing from the cursor to the GPS fix position.

![](https://user-images.githubusercontent.com/1829991/72318360-cd6c6600-36e7-11ea-9f2d-9a47d8772623.gif)

##	Add new mode to "Join Attributes by Location" to take attributes from matching feature with largest area of overlap only
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **milestone**:	3.12.0
- **merged**:	2020-01-14T08:28:32Z
- **tags**:	Changelog;Feature;Processing
- **PR**:	[33754](https://github.com/qgis/QGIS/pull/33754)
- **Descrizione**:  This allows for easy polygon->polygon joins, where you expect there to be
only a single matching feature and don't want to include features which
are just touching or have just tiny sliver polygon overlaps.
- **Sponsored by** SMEC/SJ
  
![](./imgs/33754.png)

##	New layout item type: manually created fixed tables
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **milestone**:	3.12.0
- **merged**:	2020-01-14T06:08:21Z
- **tags**:	Feature;Print Layouts
- **PR**:	[33734](https://github.com/qgis/QGIS/pull/33734)
##	Fix invalid attributes dialog on copy to another layer
- **author**:	signedav
- **milestone**:	3.12.0
- **merged**:	2020-01-15T07:00:43Z
- **tags**:	Feature;Needs Documentation
- **PR**:	[33688](https://github.com/qgis/QGIS/pull/33688)
##	Native PostGIS raster data provider
- **author**:	[elpaso](https://twitter.com/elpaso66)
- **milestone**:	3.12.0
- **merged**:	2020-01-17T10:31:28Z
- **PR**:	[33685](https://github.com/qgis/QGIS/pull/33685)
##	Allow customization of the items shown in browser
- **author**:	PeterPetrik
- **milestone**:	3.12.0
- **merged**:	2020-01-15T09:08:59Z
- **PR**:	[33679](https://github.com/qgis/QGIS/pull/33679)
##	Add setting for format to show angular bearings to projects
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2020-01-09T04:10:31Z
- **tags**:	Feature;Needs Documentation
- **PR**:	[33674](https://github.com/qgis/QGIS/pull/33674)
##	Add user control over scalebar numeric formats
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2020-01-09T06:51:51Z
- **tags**:	Changelog;Feature;Needs Documentation;Print Layouts
- **PR**:	[33657](https://github.com/qgis/QGIS/pull/33657)
##	Add Refresh action to OGC services
- **author**:	Samweli
- **milestone**:	3.12.0
- **merged**:	2020-01-18T02:18:21Z
- **PR**:	[33651](https://github.com/qgis/QGIS/pull/33651)
##	Allow layout attribute tables to be styled using the foreground and background colors of matching conditional styles
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **milestone**:	3.12.0
- **merged**:	2020-01-08T02:31:25Z
- **tags**:	Changelog;Feature;Needs Documentation;Print Layouts
- **PR**:	[33638](https://github.com/qgis/QGIS/pull/33638)
##	Support for Oracle curves and surfaces
- **author**:	troopa81
- **milestone**:	3.12.0
- **merged**:	2020-01-13T00:24:26Z
- **tags**:	Changelog;Data Provider;Feature
- **PR**:	[33629](https://github.com/qgis/QGIS/pull/33629)
##	New parameter type for map themes
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2020-01-05T10:50:06Z
- **tags**:	Feature;Processing
- **PR**:	[33608](https://github.com/qgis/QGIS/pull/33608)
##	Rotate expression function (with followups)
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2020-01-02T04:45:07Z
- **tags**:	Changelog;Feature
- **PR**:	[33575](https://github.com/qgis/QGIS/pull/33575)
##	Add native affine transform algorithm for vectors
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-12-31T05:01:36Z
- **tags**:	Changelog;Feature;Processing
- **PR**:	[33552](https://github.com/qgis/QGIS/pull/33552)
##	Allow dropping a map layer from the layer tree onto a projection selection widget
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-12-22T19:17:41Z
- **tags**:	Changelog;Feature;GUI/UX
- **PR**:	[33485](https://github.com/qgis/QGIS/pull/33485)
##	Load 3D vector layer data in background + tiling
- **author**:	[wonder-sk](https://github.com/wonder-sk)
- **milestone**:	3.12.0
- **merged**:	2020-01-16T23:00:34Z
- **tags**:	3D;Changelog;Feature
- **PR**:	[33480](https://github.com/qgis/QGIS/pull/33480)
##	Stored expressions
- **author**:	[elpaso](https://twitter.com/elpaso66)
- **milestone**:	3.12.0
- **merged**:	2019-12-17T19:13:33Z
- **tags**:	Expressions;Feature
- **PR**:	[33437](https://github.com/qgis/QGIS/pull/33437)
##	List referenced layer values in Expression Builder
- **author**:	signedav
- **merged**:	2019-12-20T16:29:11Z
- **PR**:	[33436](https://github.com/qgis/QGIS/pull/33436)
##	Other average methods 3d mesh
- **author**:	PeterPetrik
- **milestone**:	3.12.0
- **merged**:	2019-12-20T06:48:40Z
- **tags**:	Feature;Mesh;Needs Documentation
- **PR**:	[33426](https://github.com/qgis/QGIS/pull/33426)
##	Fixes time reference for mesh layer #32186 #33399 #31933
- **author**:	vcloarec
- **milestone**:	3.12.0
- **merged**:	2019-12-17T13:56:50Z
- **tags**:	Bug;Data Provider;Feature;Mesh
- **PR**:	[33410](https://github.com/qgis/QGIS/pull/33410)
##	Add expressions is_empty(geom)  is_empty_or_null(geom)
- **author**:	lbartoletti
- **merged**:	2019-12-16T07:06:59Z
- **PR**:	[33333](https://github.com/qgis/QGIS/pull/33333)
##	Support datasets with data defined on faces in mesh calculator
- **author**:	PeterPetrik
- **milestone**:	3.12.0
- **merged**:	2019-12-06T17:27:29Z
- **tags**:	Feature;Mesh
- **PR**:	[33248](https://github.com/qgis/QGIS/pull/33248)
##	Show the total pan distance and bearing in the status bar
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-12-05T18:50:19Z
- **PR**:	[33241](https://github.com/qgis/QGIS/pull/33241)
##	Add option to auto-rotate canvas to GPS bearing; show GPS bearing as a line over map
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-12-10T03:05:06Z
- **tags**:	Feature;GPS
- **PR**:	[33240](https://github.com/qgis/QGIS/pull/33240)
##	Show html files in browser panel
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-12-06T04:39:10Z
- **PR**:	[33219](https://github.com/qgis/QGIS/pull/33219)
##	New algorithm "Repair Shapefile"
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-12-04T09:58:03Z
- **tags**:	Feature;Processing
- **PR**:	[33218](https://github.com/qgis/QGIS/pull/33218)
##	Static particle traces for rendering mesh vector dataset
- **author**:	vcloarec
- **milestone**:	3.12.0
- **merged**:	2019-12-03T07:13:37Z
- **tags**:	Feature;Mesh
- **PR**:	[33165](https://github.com/qgis/QGIS/pull/33165)
##	Stacked 3d mesh (part 1.)
- **author**:	PeterPetrik
- **milestone**:	3.12.0
- **merged**:	2019-12-05T06:08:52Z
- **tags**:	Data Provider;Feature;Mesh;Squash!
- **PR**:	[33153](https://github.com/qgis/QGIS/pull/33153)
##	Show "Open Document..." action when right clicking certain
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-12-04T06:50:53Z
- **PR**:	[33142](https://github.com/qgis/QGIS/pull/33142)
##	Allow drag and drop of pictures onto layouts
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-11-28T08:38:32Z
- **tags**:	Feature;Print Layouts
- **PR**:	[33113](https://github.com/qgis/QGIS/pull/33113)
##	Paint effect support for diagram renderer
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-11-24T20:20:44Z
- **PR**:	[33044](https://github.com/qgis/QGIS/pull/33044)
##	New diagram type "stacked bars"
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-11-24T09:11:22Z
- **PR**:	[33043](https://github.com/qgis/QGIS/pull/33043)
##	Diagrams - add option to show axis for histogram plots; many fixes
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-11-23T08:06:19Z
- **PR**:	[33029](https://github.com/qgis/QGIS/pull/33029)
##	Streamlines Renderer for vector dataset on mesh layer.
- **author**:	vcloarec
- **milestone**:	3.12.0
- **merged**:	2019-11-25T07:54:12Z
- **tags**:	Feature;Mesh
- **PR**:	[32996](https://github.com/qgis/QGIS/pull/32996)
##	Add option to control pie diagram angular direction
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-11-21T23:01:51Z
- **PR**:	[32986](https://github.com/qgis/QGIS/pull/32986)
##	Add spacing option for vector layer bar chart diagrams
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-11-21T05:21:45Z
- **PR**:	[32984](https://github.com/qgis/QGIS/pull/32984)
##	Allow to delete custom label position
- **author**:	3nids
- **merged**:	2019-11-20T10:46:22Z
- **tags**:	Feature;Labeling
- **PR**:	[32942](https://github.com/qgis/QGIS/pull/32942)
##	Add search box to layout manager
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **milestone**:	3.12.0
- **merged**:	2019-11-20T07:38:29Z
- **PR**:	[32939](https://github.com/qgis/QGIS/pull/32939)
##	is_valid expression
- **author**:	pkinglinz
- **merged**:	2019-11-17T16:31:49Z
- **tags**:	Expressions;Feature
- **PR**:	[32900](https://github.com/qgis/QGIS/pull/32900)
##	Processing raster calc: add missing btns and validate
- **author**:	[elpaso](https://twitter.com/elpaso66)
- **merged**:	2019-11-16T07:19:28Z
- **tags**:	Feature;GUI/UX;Processing
- **PR**:	[32890](https://github.com/qgis/QGIS/pull/32890)
##	Make the DXF renderer ready for background threading and fix symbology
- **author**:	m-kuhn
- **merged**:	2019-11-14T08:47:23Z
- **PR**:	[32770](https://github.com/qgis/QGIS/pull/32770)
##	Add Fuzzy Logic raster algorithms
- **author**:	root676
- **merged**:	2019-11-10T19:26:03Z
- **tags**:	Feature;Processing
- **PR**:	[32701](https://github.com/qgis/QGIS/pull/32701)
##	Server OAPIF simple transactions
- **author**:	[elpaso](https://twitter.com/elpaso66)
- **milestone**:	3.12.0
- **merged**:	2019-11-15T13:21:04Z
- **tags**:	Feature;Server
- **PR**:	[32694](https://github.com/qgis/QGIS/pull/32694)
##	Server OAPIF properties
- **author**:	[elpaso](https://twitter.com/elpaso66)
- **merged**:	2019-11-06T09:48:05Z
- **tags**:	Feature;Server
- **PR**:	[32655](https://github.com/qgis/QGIS/pull/32655)
##	HAlign/VAlign support for TEXT
- **author**:	m-kuhn
- **merged**:	2019-11-07T15:37:07Z
- **tags**:	DXF/DWG;Feature
- **PR**:	[32629](https://github.com/qgis/QGIS/pull/32629)
##	Add save multiple styles action to style menu
- **author**:	[elpaso](https://twitter.com/elpaso66)
- **merged**:	2019-11-11T10:25:30Z
- **tags**:	Feature;GUI/UX
- **PR**:	[32628](https://github.com/qgis/QGIS/pull/32628)
##	Add expression functions for converting to/from wkb
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **merged**:	2019-11-04T03:00:12Z
- **PR**:	[32561](https://github.com/qgis/QGIS/pull/32561)
##	Add - **merged**:_from_epoch (MSec from epoch) expression function
- **author**:	rduivenvoorde
- **merged**:	2019-11-22T10:09:38Z
- **PR**:	[32551](https://github.com/qgis/QGIS/pull/32551)
##	Ignored credentials temporary cache
- **author**:	[elpaso](https://twitter.com/elpaso66)
- **milestone**:	3.12.0
- **merged**:	2019-11-01T08:02:35Z
- **tags**:	Feature;GUI/UX
- **PR**:	[32546](https://github.com/qgis/QGIS/pull/32546)
##	Create child feature with geometry from the relation editor
- **author**:	troopa81
- **merged**:	2019-12-04T13:46:33Z
- **PR**:	[32528](https://github.com/qgis/QGIS/pull/32528)
##	Value relation restore missing layers from DBs
- **author**:	[elpaso](https://twitter.com/elpaso66)
- **milestone**:	3.12.0
- **merged**:	2019-11-04T11:03:41Z
- **tags**:	Feature;Requires Tests!
- **PR**:	[32487](https://github.com/qgis/QGIS/pull/32487)
##	Selection widget in feature selection dialog
- **author**:	troopa81
- **merged**:	2019-12-16T10:32:26Z
- **PR**:	[32472](https://github.com/qgis/QGIS/pull/32472)
##	add gdal_viewshed algorithm
- **author**:	alexbruy
- **merged**:	2019-11-06T03:40:35Z
- **tags**:	Feature;Processing
- **PR**:	[32463](https://github.com/qgis/QGIS/pull/32463)
##	Add density-based point count for the random marker fill
- **author**:	nirvn
- **merged**:	2019-10-30T05:04:14Z
- **tags**:	Feature;Symbology
- **PR**:	[32456](https://github.com/qgis/QGIS/pull/32456)
##	Server wfs3 timefilter dimensions
- **author**:	[elpaso](https://twitter.com/elpaso66)
- **milestone**:	3.12.0
- **merged**:	2019-10-30T17:29:50Z
- **tags**:	Feature;Server
- **PR**:	[32322](https://github.com/qgis/QGIS/pull/32322)
##	Add OGC API - Features (OAPIF) provider
- **author**:	rouault
- **merged**:	2019-10-25T20:48:00Z
- **PR**:	[32262](https://github.com/qgis/QGIS/pull/32262)
##	Random marker fill symbol layer type
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **milestone**:	3.12.0
- **merged**:	2019-10-28T04:34:31Z
- **PR**:	[32241](https://github.com/qgis/QGIS/pull/32241)
##	Export mesh contours & resampling
- **author**:	PeterPetrik
- **milestone**:	3.12.0
- **merged**:	2019-10-29T22:16:06Z
- **tags**:	Feature;Mesh
- **PR**:	[32201](https://github.com/qgis/QGIS/pull/32201)
##	Feature update layer selection relation widgets
- **author**:	troopa81
- **milestone**:	3.12.0
- **merged**:	2019-10-29T07:32:32Z
- **PR**:	[31951](https://github.com/qgis/QGIS/pull/31951)
##	fix #29326 Adding playback function for mesh datasets
- **author**:	MarcusUrban
- **milestone**:	3.12.0
- **merged**:	2019-10-31T08:09:48Z
- **tags**:	Feature;Mesh
- **PR**:	[31875](https://github.com/qgis/QGIS/pull/31875)
##	Add json support to WMS GetLegendGraphic
- **author**:	elemoine
- **milestone**:	3.12.0
- **merged**:	2019-10-26T00:51:40Z
- **tags**:	Feature;Merge After Thaw;Server
- **PR**:	[31747](https://github.com/qgis/QGIS/pull/31747)
##	Add option to set color for rendering nodata pixels in raster layers
- **author**:	[nyalldawson](https://twitter.com/nyalldawson)
- **milestone**:	3.12.0
- **merged**:	2019-10-27T00:07:05Z
- **tags**:	Feature;Merge After Thaw
- **PR**:	[31728](https://github.com/qgis/QGIS/pull/31728)
##	Hash expressions
- **author**:	lbartoletti
- **merged**:	2019-10-25T22:32:27Z
- **tags**:	Feature;Merge After Thaw
- **PR**:	[31726](https://github.com/qgis/QGIS/pull/31726)
##	Parallelize snap caching
- **author**:	troopa81
- **milestone**:	3.10.1
- **merged**:	2019-10-31T08:31:21Z
- **PR**:	[31648](https://github.com/qgis/QGIS/pull/31648)
##	Add z distance
- **author**:	ismailsunni
- **milestone**:	3.12.0
- **merged**:	2019-10-29T21:55:01Z
- **PR**:	[31451](https://github.com/qgis/QGIS/pull/31451)
##	Selective masking
- **author**:	mhugo
- **milestone**:	3.12.0
- **merged**:	2019-11-07T07:17:26Z
- **tags**:	Feature;Labeling;Symbology
- **PR**:	[30747](https://github.com/qgis/QGIS/pull/30747)
##	Bad Layer Handler Improvements
- **author**:	roya0045
- **milestone**:	3.12.0
- **merged**:	2019-11-21T10:51:54Z
- **tags**:	Feature;Squash!
- **PR**:	[30297](https://github.com/qgis/QGIS/pull/30297)