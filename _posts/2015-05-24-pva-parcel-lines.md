---
layout: page
title: "Downloading Parcel Lines"
subtitle: "How to download parcel boundaries from the Scott County PVA"
category: data
date: 2015-05-24 12:00:00
author: 'Ryan Cooper'
client: 'GSCPC'
---

## Objectives:

* Search for and find a specific property on the Scott County PVA website.
* Download a property's parcel boundary as a KML file

## Introduction:

The purpose of this little tutorial is to walk you through how to search for and download a KML version of a property's parcel boundary via the Scott County PVA's website. At the end of the tutorial you should have a file that you can view in Google Earth or work with in more advanced mapping programs like QGIS, ArcGIS, or CartoDB. 

Although this tutorial uses Scott County PVA's qPublic site as the base example, the process outlined here should work for Fayette and other PVAs with a qPublic site where the parcel boundaries are made available for download.

**[Scott County PVA site](http://qpublic5.qpublic.net/ky_isearch.php?county=ky_scott)**

## What is this qPublic thing? 

In Kentucky, property tax assessment is handled at the county level by, for the most part, the Property Valuation Administrator (PVA). Many Kentucky counties allow some level of access to PVA data through a [qPublic](http://www.qpublic.net/)-based website. qPublic sites potentially grant curious visitors access to a county's PVA data. Counties like Fayette and Scott have largely made their PVA data available for free. Most counties require what some might argue is a cost-prohibitive subscription fee. That said, through some qPublic sites, you can access not only the property data, but also the boundary lines for the parcel you're looking for.

## Searching for a Parcel

1. Go to the [Scott County PVA site](http://qpublic5.qpublic.net/ky_isearch.php?county=ky_scott)
	- URL: `http://qpublic5.qpublic.net/ky_isearch.php?county=ky_scott`
2. The site gives you several options for searching for a parcel. Select the option that you have information for. <br> ![](http://i1368.photobucket.com/albums/ag172/gscplanning/geparcelmap/pva1_zpsw5teqnrx.jpg)
	- **Tip:** *If you know where your parcel is, but don't have much information about it, `Search by Map` is probably your best bet.*
3. After submitting your search, you will be presented with a list of results. Locate your the row for your parcel of interest. In the last column, **GIS Map**, with a link, `Map It`. Click that link. <br> ![](http://i1368.photobucket.com/albums/ag172/gscplanning/geparcelmap/pva2_zpstddclbte.jpg)
4. A map should be directed to a map with your parcel highlighted with a pinkish red outline. Make sure it's the parcel you want! <br> ![](http://i1368.photobucket.com/albums/ag172/gscplanning/geparcelmap/pva3_zpscst3gfaf.jpg)

## Download a Parcel
1. In the right pane on your screen is the Parcel Information Table. This gives you a little more information about the parcel. You have the option **View as:** and several map providers. Click `Google Earth`. <br> ![](http://i1368.photobucket.com/albums/ag172/gscplanning/geparcelmap/pva4_zpstpl4gjse.jpg)
2. You'll be prompted to save a file called `qpublic_parcel.kml`. This is a file containing the boundary for your parcel! Feel free to rename it something meaningful to you and save it to a location where you'll remember to find it. <br> ![](http://i1368.photobucket.com/albums/ag172/gscplanning/geparcelmap/pva5_zpsilsmut0v.jpg)

Congratulations! You've successfully found a parcel on the Scott County PVA website and saved a KML file of its boundaries.  Unfortunately you can only select one parcel at a time so if you want to get more parcel boundaries, you'll need to repeat the step for this section.
