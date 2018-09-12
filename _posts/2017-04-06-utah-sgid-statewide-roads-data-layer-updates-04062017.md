---
layout: post
status: publish
published: true
title: 'Utah SGID Statewide Roads Data Layer Updates 04/06/2017'
author:
  display_name: Greg Bunce
  email: gbunce@utah.gov
date: 2017-04-06
categories:
- Data
- Featured
tags:
- SGID
- Data
- Utah
- Roads
- Centerlines
- Statewide
- GIS
---

Updates were made recently to the SGID10.Transportation.Roads feature class that resides on the [Utah SGID ArcSDE database server]({{ "/data/how-to-connect-to-the-sgid-via-sde/" | prepend: site.baseurl }}).

The updated roads data is also available as shapefiles and file geodatabase files for download on the [SGID FTP site](ftp://ftp.agrc.utah.gov/UtahSGID_Vector/UTM12_NAD83/TRANSPORTATION/PackagedData/_Statewide/UtahRoadAndHighwaySystem/).

Geocoding services and ArcGIS Server Applications & Web Services are now using the updated SGID10.Transportation.Roads feature class.

The following are highlights from this update:

#### County Updates:

- **Box Elder County:** Obtained roads data on 03/02/2017: added new roads, updated road names and address ranges, etc. Previous update was on 01/10/2017.

- **Carbon County:** Obtained roads data on 03/16/2017: added new roads, updated road names and address ranges, etc. Previous update was on 12/2015.

- **Davis County:** Obtained roads data on 03/24/2017: added new roads, updated road names and address ranges, etc. Previous update was on 03/09/2017.

- **Grand County:** Obtained roads data from the Grand County on 03/08/2017 and from the City of Moab on 02/10/2017: added new roads, updated road names and address ranges, etc. Previous update was on 12/03/2015.

- **Salt Lake County:** Obtained roads data on 03/28/2017: added new roads, updated road names and address ranges, etc. Previous update was on 03/09/2017.

- **South Jordan City:** Obtained roads data on 03/06/2017: added new roads, updated road names and address ranges, etc. Previous update via Salt Lake County data was on 03/09/2017.

- **Utah County:** Obtained roads data on 03/20/2017: added new roads, updated road names and address ranges, etc. Previous update was on 03/09/2017.

- **Washington County:** Obtained roads data on 03/17/2017: added new roads, road names and address ranges, etc. Previous update was on 03/09/2017.

- **Wayne County:** Obtained roads data on 03/15/2017: added new roads, road names and address ranges, etc. Previous update was on 12/03/2015.

- **Weber County:** Obtained roads data on 03/30/2017: added new roads, road names and address ranges, etc. Previous update was on 03/09/2017.

#### UDOT Route System:

- The DOT_F_MP (From Milepost) and DOT_T_MP (To Milepost) fields that store the milepost attributes of the UDOT state and federal routes in SGID10.Transportation.Roads were updated
- The DOT_RTID field that stores UDOT's unique numeric route identifiers was updated
