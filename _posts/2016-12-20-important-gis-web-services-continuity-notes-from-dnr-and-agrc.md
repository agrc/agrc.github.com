---
layout: post
status: publish
published: true
title: 'Important GIS Web Services Continuity Notes from DNR and AGRC'
author:
  display_name: Bert Granberg
  email: bgranberg@utah.gov
date: 2016-12-20 23:21:12
categories:
- Featured
tags:
- HTTP
- HTTPS
- best practices
- basemaps
- discover

---

GIS web services are relied upon by increasingly. Here are two important service update announcements:

**DNR’s Public GIS Datasets Get New https:// URLs**

As part of the State of Utah’s move toward GIS best practices, including greater data security, DNR is moving our public, GIS data servers from HTTP to HTTPS protocol.  This action will, unfortunately, break data links within .mxds, other desktop GIS software, web maps, and custom applications that reference DNR data currently found at http://maps.dnr.utah.gov/arcgis/rest/services.

DNR will make this change on January 4th at 5pm.  If you use/incorporate DNR web services, it may be wise to remove the layer(s) from your projects/apps and add the services back in, using the URLs after Jan. 4th from its new directory address at https://maps.dnr.utah.gov/arcgis/rest/services.

**AGRC plans January 31 shutdown for NAD83 base maps.**

As previously communicated, AGRC is working toward a year-end shut off the NAD83 base maps served from mapserv.utah.gov. We've been in contact with all of the users and apps known to us to convert to the web Mercator WGS84 base maps and high resolution and historic imagery hosted on the discover.agrc.utah.gov server.

We've set a target date/time of January 31 at 6:00pm MST to shut down the existing NAD83 base map services. Similarly, we recommend removing them from map documents (mxds, etc) and web map services prior to the scheduled shutoff.

Theses services were first built almost ten years ago, before web mercator became the defacto standard for tiled map services. It's sad to see them replaced but it's good to coalesce around best practices and reduce duplicate maintenance and storage.

Also, AGRC is now creating accounts for the discover.agrc.utah.gov server for those not previously eligible to access the licensed Google imagery. These new 'public' accounts allow access to statewide NAIP aerial photography and color infrared layers, older black and white aerials, and all of AGRC's custom base map tile services. ***If you already have a discover account, you do not need to create another account to access the base maps.***

Please contact Matt Peters ([mpeters@utah.gov](mailto:mpeters@utah.gov)) at AGRC if you have questions or issues in regard to the NAD83 base map shutdown.
