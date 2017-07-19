---
status: publish
layout: post
author:
  display_name: Data Queen
  email: agrc@utah.gov
tags:
  - address
  - cartography
  - data
  - geocoding
  - location
  - roads
published: true
date: 2016-01-14 09:57:01 -0700
title: Utah SGID Statewide Roads Data Layer Updates 1/13/2016
categories:
  - Data
  - Featured
---
<p>Updates were made recently to the SGID10.Transportation.Roads feature class that resides on the <a href="{{ "/data/how-to-connect-to-the-sgid-via-sde/" | prepend: site.baseurl }}">Utah SGID ArcSDE database server</a>.</p>
<p>The updated Roads data is also available as shapefiles and file geodatabase files for download on the <a href="ftp://ftp.agrc.utah.gov/UtahSGID_Vector/UTM12_NAD83/TRANSPORTATION/PackagedData/_Statewide/UtahRoadAndHighwaySystem/">SGID FTP site</a>.</p>
<p>Geocoding services and ArcGIS Server Applications & Web Services are now using the updated SGID10.Transportation.Roads feature class.</p>
<p>The following highlights what has been updated:</p>
<p><span style="text-decoration: underline;">County Updates:</span></p>
<ul>
<li><strong>Davis:</strong> Received centerline update 1/4/2016: added new roads, road name and address range changes since last update on 12/2/2015; geocoding improvements</li>
<li><strong>Iron:</strong> Received centerline update 12/15/2015: added new roads, road name and address range changes since last update on 12/4/2014; geocoding improvements</li>
<li><strong>Morgan:</strong> Received centerline update 12/17/2015: added new roads, road name and address range changes since last update on 2/9/2015; geocoding improvements</li>
<li><strong>Salt Lake:</strong> Received VECC's centerline update 12/21/2015: added new roads, road name and address range changes since last update on 11/23/2015; geocoding improvements</li>
<li><strong>Utah:</strong> Received centerline update 1/12/2016: added new roads, road name and address range changes since last update on 11/25/2015; geocoding improvements</li>
<li><strong>Washington:</strong> Received centerline update 12/21/2015: added new roads, road name and address range changes since last update 11/25/2015; geocoding improvements</li>
<li><strong>Weber:</strong> No changes made in December</li>
</li>
</ul>
<p><span style="text-decoration: underline;">Blue Stakes of Utah Feedback:</span></p>
<ul>
<li><strong>Davis:</strong> geocoding improvements</li>
<li><strong>Duchesne:</strong> geocoding improvements</li>
<li><strong>Morgan:</strong> geocoding improvements</li>
<li><strong>Salt Lake:</strong> geocoding improvements</li>
<li><strong>Utah:</strong> geocoding improvements</li>
<li><strong>Wasatch:</strong> geocoding improvements</li>
</ul>
<p><span style="text-decoration: underline;">UDOT Route System:</span></p>
<ul>
<li>The DOT_F_MP (From Milepost) and DOT_T_MP (To Milepost) fields that store the milepost attributes of the UDOT state and federal routes in SGID10.Transportation.Roads were updated</li>
<li>The DOT_RTID field that stores UDOT's unique numeric route identifiers was updated</li>
