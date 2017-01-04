---
layout: post
status: publish
published: true
title: 'Utah SGID Statewide Roads Data Layer Updates 11/09/2016'
author:
  display_name: Greg Bunce
  email: gbunce@utah.gov
date: 2016-11-09
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

The updated Roads data is also available as shapefiles and file geodatabase files for download on the [SGID FTP site](ftp://ftp.agrc.utah.gov/UtahSGID_Vector/UTM12_NAD83/TRANSPORTATION/PackagedData/_Statewide/UtahRoadAndHighwaySystem/).

Geocoding services and ArcGIS Server Applications & Web Services are now using the updated SGID10.Transportation.Roads feature class.

The following highlights were updated:

#### County Updates:

- **Beaver County:** Obtained centerline update on 10/04/2016: added new roads, road name and address range changes since last update on 11/13/2014; geocoding improvements.

- **Davis County:** Obtained centerline update on 10/27/2016: added new roads, road name and address range changes since last update on 10/03/2016; geocoding improvements.

- **Salt Lake County:** Obtained centerline update from VECC on 10/20/2016: added new roads, road name and address range changes since last update on 10/03/2016; geocoding improvements.

- **Uintah County:** Obtained centerline update on 10/01/2016: added new roads, road name and address range changes since last update 11/05/2015; geocoding improvements

- **Utah County:** Obtained centerline update on 10/20/2016: added new roads, road name and address range changes since last update 10/03/2016; geocoding improvements

- **Washington County:** Obtained centerline update on 10/20/2016: added new roads, road name and address range changes since last update 10/03/2016; geocoding improvements

- **Weber County:** Obtained centerline update on 10/25/2016: added new roads, road name and address range changes since last update 10/03/2016; geocoding improvements

#### UDOT Route System:

- The DOT_F_MP (From Milepost) and DOT_T_MP (To Milepost) fields that store the milepost attributes of the UDOT state and federal routes in SGID10.Transportation.Roads were updated
- The DOT_RTID field that stores UDOT's unique numeric route identifiers was updated
