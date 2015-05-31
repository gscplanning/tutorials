---
layout: page
title: "Getting Parcel Lines"
subtitle: "How to download parcel boundaries from a qPublic site"
category: data
date: 2015-05-24 12:00:00
author: 'Ryan Cooper'
client: 'GSCPC'
---

### How to download parcel boundaries from a qPublic site

#### Target Audience:
citizens, realtors, lawyers

#### Objectives:

* Search for and find a specific property on a qPublic site
* Download a property's parcel boundary from a qPublic site

#### Introduction:

The purpose of this little tutorial is to walk you through how to search for and download a KML version of a property's parcel boundary through one of the more openly accessible qPublic sites. At the end of the tutorial you should have a file that you can view in Google Earth or work with in more advanced mapping programs like QGIS, ArcGIS, or CartoDB. 

For this tutorial, we'll use the Scott County PVA's qPublic site as the base example. That said, the process outlined here should work for Fayette and other PVAs with qPublic site where the parcel boundaries are made available for download.

**[Scott County PVA site](http://qpublic5.qpublic.net/ky_scott_accept.php)**

#### What is this qPublic thing? 

In Kentucky, property tax assessment is handled at the county level by, for the most part, the Property Valuation Administrator (PVA). Many Kentucky counties allow some level of access to PVA data through a [qPublic](http://www.qpublic.net/) site. qPublic sites potentially grant curious visitors access to a county's PVA data. Counties like Fayette and Scott have largely made there PVA data available for free although most counties require what some might argue is a cost-prohibitive subscription fee. That said, through some qPublic sites, you can access not only the property data, but also the boundary lines for the parcel you're looking for.

#### Searching for a Parcel

There are several ways to search for a parcel. Search options will vary from PVA to PVA, but when you begin  your search on a qPublic site, you will be presented with a list of options similar to this:

![qPublic search options](http://i1185.photobucket.com/albums/z344/buspainter2005/tutorials/qpublic%20parcels/pva1_zpsblej795b.png)

There are a couple of different ways that your search will return results. Let's look at them individually

##### Search by Owner Name, GIS Map Number, Location Address, Description...

When you do one of the above types of searches, a list of properties will be returned to. For instance, if you click *Search by Location Address* and search **E Main St**, you'll get something like this:

![](http://i1185.photobucket.com/albums/z344/buspainter2005/tutorials/qpublic%20parcels/pva2_zpsehszrvzl.png)

The lsit contains some basic information about each property returned. You can select a specific property by clicking its *Map Number* or the **Map It** link in the *GIS Map* column. Since we want to get at the parcel boundaries, we'll use the **Map It** link. In this example we're interested in `230 E Main St`.

![](http://i1185.photobucket.com/albums/z344/buspainter2005/tutorials/qpublic%20parcels/pva3_zpsmtpmah0q.png)

Clicking **Map It** for your parcel of choice will take you to a map interface. We'll delve more into that when we discuss how to actually download the parcel bounds.

![](http://i1185.photobucket.com/albums/z344/buspainter2005/tutorials/qpublic%20parcels/pva4_zps1wyfrjxk.png)

##### Search by Map

Let's say you know vaguely where a property is located, but the search options discussed above are coming up short. *Search by Map* allows you to interactively navigate a parcel map. A map viewer opens up showing the county at its fullest extent.

![](http://i1185.photobucket.com/albums/z344/buspainter2005/tutorials/qpublic%20parcels/pva5_zpsxuyaracz.png)

Do reduce load time, parcels aren't drawn at this scale. You'll need to zoom in. The map viewer toolbar has a few options for zooming in (outlined in purple).

![](http://i1185.photobucket.com/albums/z344/buspainter2005/tutorials/qpublic%20parcels/pva6_zpshlyozrie.png)

Additionally you can hold Shift + left-click, you can drag a box around an area of interest. The map will then zoom to that area.

![](http://i1185.photobucket.com/albums/z344/buspainter2005/tutorials/qpublic%20parcels/pva7_zpsowxvoibn.gif)

When you've found a parcel you're interested in, click it. The parcel will become highlighted and the information pane to the right will populated with attribute information about the it.

![](http://i1185.photobucket.com/albums/z344/buspainter2005/tutorials/qpublic%20parcels/pva4_zps1wyfrjxk.png)	

#### Download a Parcel Boundary 
