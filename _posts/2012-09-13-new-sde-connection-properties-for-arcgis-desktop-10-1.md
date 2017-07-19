---
status: publish
layout: post
author:
  display_name: Michael Foulger
  email: michaelfoulger@utah.gov
tags: []
published: true
date: 2012-09-13 10:00:46 -0600
title: New SDE Connection Properties for ArcGIS Desktop 10.x
categories:
  - Data
  - Featured
---

Esri is now providing a tool to create an ArcSDE Connection File wherever you would like on your file system. The tool is located in the standard toolbox under Data Management -&gt; Workspace -&gt; Create ArcSDE Connection File.  Here's a look at where it's located, and what it looks like when filled out:

This tool is only available to users running a Standard (ArcEditor) or Advanced (ArcInfo) license level.  Users of a Basic (ArcView) license will need to download the connection file, available in a link below.
{:.pop}

<img src="{{ "/images/ArcSDEConnectionFile-e1346951121724.png" | prepend: site.baseurl }}" title="ArcSDE ConnectionFile" />

You can save the connection file anywhere you'd like, but if you want to see the connection in the `Database Connections` folder in ArcGIS Desktop, you'll need to save it to this location: `C:\Users\[Your User Name]\AppData\Roaming\ESRI\Desktop[version]\ArcCatalog`

It should be noted that the `AppData` folder is most likely hidden by default. In Windows, you can make it visible by going to `Control Panel`, `Folder Options`, choosing the `View` tab, and enabling `Show hidden files, folders, and drives` from the `Hidden files and folders` area. (Thanks Doug!)

Just replace the entry `[Your User Name]` and `[version]` with your login name and the version of ArcGIS Desktop you are using.

### Instructions for Basic (ArcView) license level users

If you're using a Basic license for Esri's desktop product (ArcView), and wish to connect to the SGID, you'll need to download a connection file from our FTP site:

<a title="Click Here to Download Connection File" href="ftp://ftp.agrc.utah.gov/ApplicationServer/ArcGIS_Connection_File/ConnectSGID10.sde">ftp://ftp.agrc.utah.gov/ApplicationServer/ArcGIS_Connection_File/ConnectSGID10.sde</a>

You can save the connection file anywhere you'd like, but if you want to see the connection in the `Database Connections` folder in ArcGIS Desktop, you'll need to save it to this location: `C:\Users\[Your User Name]\AppData\Roaming\ESRI\Desktop[version]\ArcCatalog`

It should be noted that the `AppData` folder is most likely hidden by default. In Windows, you can make it visible by going to `Control Panel`, `Folder Options`, choosing the `View` tab, and enabling `Show hidden files, folders, and drives` from the `Hidden files and folders` area. (Thanks Doug!)

Just replace the entry `[Your User Name]` and `[version]` with your login name and the version of ArcGIS Desktop you are using.
