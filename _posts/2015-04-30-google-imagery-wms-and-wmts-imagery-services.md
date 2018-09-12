---
layout: post
status: publish
published: true
title: 'Google Imagery: WMS and WMTS Imagery Services, & Other Reminders'
author:
  display_name: Jessie Pechmann
  login: jpechmann
  email: jpechmann@utah.gov
  url: ''
author_login: jpechmann
author_email: jpechmann@utah.gov
wordpress_id: 17303
wordpress_url: http://gis.utah.gov/?p=17303
date: '2015-04-30 11:57:15 -0600'
date_gmt: '2015-04-30 17:57:15 -0600'
categories:
- Data
- Featured
tags:
- aerial photography
- utah
- google
- high resolution
---
<p>Users of <a href="{{site.baseurl}}{% post_url 2015-02-02-utah-acquires-high-resolution-aerial-photography-license %}">Google's statewide high resolution aerial photography</a> are transitioning to accessing the data through the new GCP-based discover.agrc.utah.gov server and its twin WMS and WMTS imagery services. The new services on the 'discover' server are much more capable and deliver higher image quality. For more information and a connection to discover.agrc.utah.gov, contact Rick Kelson at (801) 538-3237 or rkelson@utah.gov. </p>
<p><strong>WMS vs WMTS<br />
</strong>With two choices of OGC standard-based imagery services to choose from, WMS and WMTS, which should you use? The WMTS protocol should deliver the imagery faster so use it if works on your platform. But, the WMS service is an older standard that may be more maturely implemented within software applications, and is what ESRI users not yet at v10.2 should use. </p>
<p><a href="{{ "/downloads/WakeUp-Google.png" | prepend: site.baseurl }}"><img src="{{ "/images/WakeUp-Google-246x300.png" | prepend: site.baseurl }}" alt="" title="WakeUp Google" width="246" height="300" class="inline-text-left" /></a><strong>Other items</strong><br />
Users will find that both services will time out when they are unused for long periods. Refreshing the service in ArcMap should be as easy as opening the ArcCatalog view in ArcMap, and double clicking the service in that view to wake it up. See example at right.</p>
<p>AGRC now has the imagery files on premise and we hope, in the near future, to begin processing 'on premise' file requests that have been filed through the online Organizational Usage Agreement form. When ready, we'll reach out to you, the primary contacts, to begin that process.</p>
<p>Several users have asked for a link to view the imagery in a browser. You can do this now using <a href="https://discover.agrc.utah.gov/tiles/utah/preview">https://discover.agrc.utah.gov/tiles/utah/preview</a>, together with your organization's username and password. As this web view of the imagery uses the core WMTS service, it is a great way to begin any troubleshooting you may need to do.</p>
<p>We plan to incorporate the high resolution Google imagery into AGRC's hybrid base map, as well as adding WMTS as aservice directly within web applications.</p>
<p>Last but not least, a friendly reminder. Keep in mind that the WMS and WMTS services use the WGS84 datum which means users in other datums (NAD83 for example) will need to set an appropriate datum transformation within the viewing application, in addition to the desired projection. This is critical for getting the last meter or so of horizontal position accuracy. This and more is described at: <strong><a href="{{ "/data/googleimagery/" | prepend: site.baseurl }}">http://gis.utah.gov/data/googleimagery/</a></strong>.</p>
<p>Questions or issues? As always, please contact us: Rick Kelson at (801) 538-3237 or rkelson@utah.gov.</p>
