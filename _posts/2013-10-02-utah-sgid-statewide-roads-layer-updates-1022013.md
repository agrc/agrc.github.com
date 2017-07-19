---
status: publish
layout: post
author:
  display_name: Data Queen
  email: agrc@utah.gov
tags:
  - address
  - data
  - location
published: true
date: 2013-10-02 18:08:03 -0600
title: Utah SGID Statewide Roads Layer Updates 10/2/2013
categories:
  - Data
  - Featured
  - SGID Blog
---
<p>Updates were made recently to the SGID10.Transportation.Roads feature class that resides on the <a href="{{ "/data/how-to-connect-to-the-sgid-via-sde/" | prepend: site.baseurl }}">Utah SGID ArcSDE database server</a>.</p>
<p>The updated Roads data is also available as shapefiles and file geodatabase files for download on the <a href="ftp://ftp.agrc.utah.gov/UtahSGID_Vector/UTM12_NAD83/TRANSPORTATION/PackagedData/_Statewide/UtahRoadAndHighwaySystem/">SGID FTP site</a>.</p>
<p>Geocoding services and ArcGIS Server Applications & Web Services are now using the updated SGID10.Transportation.Roads feature class.</p>
<p>The following highlights what has been updated:</p>
<p><span style="text-decoration: underline;">County Updates:</span></p>
<ul>
<li><strong>Davis:</strong> Received centerline update 7/31/2013: added new roads, road names, and address ranges; geocoding improvements</li>
<li><strong>Iron:</strong> Received centerline update 9/24/2013: added road names and address ranges; geocoding improvements</li>
<li><strong>Tooele:</strong> Received centerline update 8/28/2013: added new roads, road names, and address ranges; geocoding improvements</li>
<li><strong>Utah:</strong> Received centerline update 7/29/2013: added new roads (August's update), road names, and address ranges; geocoding improvements</li>
</ul>
<p><span style="text-decoration: underline;">Blue Stakes of Utah Feedback:</span></p>
<ul>
<li><strong>Cache:</strong> geocoding improvements</li>
<li><strong>Davis:</strong> geocoding improvements</li>
<li><strong>Garfield:</strong> geocoding improvements</li>
<li><strong>Iron:</strong> geocoding improvements</li>
<li><strong>Salt Lake:</strong> geocoding improvements</li>
<li><strong>San Juan:</strong> geocoding improvements</li>
<li><strong>Sanpete:</strong> geocoding improvements</li>
<li><strong>Tooele:</strong> geocoding improvements</li>
<li><strong>Uintah:</strong> geocoding improvements</li>
<li><strong>Utah:</strong> geocoding improvements</li>
<li><strong>Wasatch:</strong> geocoding improvements</li>
<li><strong>Washington:</strong> geocoding improvements</li>
</ul>
<p><span style="text-decoration: underline;">UDOT Route System:</span></p>
<ul>
<li>The DOT_F_MP (From Milepost) and DOT_T_MP (To Milepost) fields that store the milepost attributes of the UDOT state and federal routes in SGID10.Transportation.Roads were updated</li>
<li>The DOT_RTID field that stores UDOT's unique numeric route identifiers was updated</li>
</ul>
