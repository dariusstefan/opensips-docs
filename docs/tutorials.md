---
title: "Tutorials"
description: "How to provide ICE end-to-end NAT traversal support for RTP streams"
---

## [OpenSIPS - Getting Started](/docs/tutorials-gettingstarted)
A crash course about how to do a quick installation of OpenSIPS ( downloading sources, compiling, installing, etc )  and OpenSIPS Control Panel ( installing, provisioning users ), and have a fully functional platform in a matter of minutes. 

---

## [Topology Hiding with OpenSIPS](/docs/tutorials-topology-hiding)
Short introduction on configuring and using the topology_hiding module in OpenSIPS.

---

## [Accounting in OpenSIPS](/docs/tutorials-advanced-accounting)
Unveils how SIP accounting works in OpenSIPS, from basic to complex scenarios with custom CDRs and multi-leg accounting for call forwarding. Everything is backed up by detailed explanations and working scripts examples.

---

## [Easier scripting with the script_helper module](/docs/tutorials-scripthelper)
Module description and a complete usage example.

---

## [Call Recording using SIPREC](/docs/tutorials-siprec)
This tutorial shows you how you can do call recording using the SIPREC standard.

---

## [Fraud detection with OpenSIPS](/docs/tutorials-frauddetection)
Description of the new module along with a complete usage example.

---

## [Message compression and compaction](/docs/tutorials-compression)
Module description and a complete usage example.

---

## [Emergency calls using OpenSIPS](/docs/tutorials-emergency)
Architecture design and complete usage examples.

---

## [WebSocket and WebSocketSecure Integration with OpenSIPS](/docs/tutorials-websocket)
How to add Websocket, and Websocket Secure (2.2+ only) capabilities to your existing OpenSIPS deployment.

---

## [Dynamic Routing with Failover](http://www.unixnews.net/2010/09/dynamic-routing-with-opensips.html)
How to configure OpenSips to route phone calls based on the dialed number.  This is a detailed tutorial on how to use the drouting module with mysql and includes failover support.  It does not include load balancing.

---

## [B2BUA](/docs/tutorials-b2bua)
Which is the architecture of the B2BUA implementation, how to define service scenario documents and how to configure OpenSIPS to offer B2BUA services.

---

## [Presence Agent](/docs/tutorials-presence)
Presence Agent - design and configuration of Presence Agent in **OpenSIPS**.

---

## [Load-Balancing](/docs/tutorials-loadbalancing)
How to use the load-balancing module from **OpenSIPS** to do traffic routing based on the real load of the destinations.

---

## [Key-Value Interface](/docs/tutorials-keyvalueinterface)
How to use the Key-Value interface in **OpenSIPS** in order to store, persistently or not, key-value information.

---

## [Event Interface](/docs/tutorials-eventinterface)
How to use **OpenSIPS** Event Interface in order to send events to external applications.

---

## [MemCache Usage](/docs/tutorials-memorycaching)
How to use the memcache support in **OpenSIPS** in order to reduce the number of DB queries (authentication for example).

---

## [OpenSIPS - FreeSwitch Media Integration](/docs/tutorials-opensipsfreeswitchintegration)
This tutorial presents the concept and implementation of a realtime integration of OpenSIPS SIP server and FreeSWITCH media server. OpenSIPS is used a SIP server, while the purpose of FreeSWITCH is to provide a full set of media services - like voicemail, conference, announcements, etc.

---

## [Realtime OpenSIPS - Asterisk Integration](/docs/tutorials-opensipsasteriskintegration)
How to implement a realtime integration of OpenSIPS SIP server and Asterisk media server for Voicemail, conference and announcement services.

---

## [Concurrent calls limitation](/docs/tutorials-concurrentcallslimitation)
How to control in **OpenSIPS** how many concurrent calls a user is allow to do.

---

## [TLS setup](/docs/tutorials-tls)
How to compile and configure the TLS support in **OpenSIPS** - script example included.

---

## [Replace 183 early media reply with perl module](/docs/tutorials-perl-183-to-180)
Example script showing how to replace SIP status replies on the fly, as this is not (yet?) possible within the OpenSIPS routing script.

---

## [A basic tutorial on RADIUS](/docs/tutorials-radius)
How to install, configure, integrate and use FreeRADIUS server and Radiusclient-ng with OpenSIPS modules for accounting and authorization.

---

## [OpenSIPS with Radius support](http://voiprookie.blogspot.com/2009/04/freeradius-and-mysql.html)
OpenSIPS with MySQL and FreeRADIUS integration and installation/configuration.

---

## [OpenSIPS and MediaProxy](http://voiprookie.blogspot.com/2009/04/blog-post.html)
MediaProxy 2.3.x and  OpenSIPS 1.5.x Integration.

How to provide [ICE end-to-end NAT traversal support for RTP streams](http://mediaproxy.ag-projects.com/projects/mediaproxy/wiki/ICE)

---

## OpenSIPS and MSRP integration

* [SylkServer integration](/docs/msrp-chat) for multiparty conferencing and XMPP gateway
* [MSRPRelay integration](/docs/msrp-relay) for NAT traversal of MSRP chat and MSRP file transfers

---

## [How to install opensips in Red Hat EL 5](/docs/tutorials-opensipsonredhat)
How to install opensips 1.5 in a Red Hat Enterprise Linux 5 platform with Mysql Support:

---

## [SIP Redirect with script](/docs/tutorials-redirect)
How setup OpenSIPS as a SIP redirect using a external script - also restricting base on ip address:
Please note since I am new to OpenSIPS this may need be cleaned up a bit.

---

## [OpenSIPS and fail2ban](/docs/tutorials-fail2ban)
This is a small tutorial so you can use fail2ban together with opensips to block via firewall the attackers that are using wrong authentication credentials.

---

## [OpenSIPS, CentOS and MI_XMLRPC](/docs/tutorials-installoncentos)
Small tutorial on how to compile OpenSIPS or CentOS. It includes a vauable tip on how to compile correctly the MI_XMLRPC module. 

---

## [OpenSIPS Tutorials from SmartVox](http://smartvox.co.uk/category/voip/)
A compilation of various tutorials covering topics like software installation (including MediaProxy on CentOS), authentication, clustering and comparing OpenSIPS with Asterisk provided by [SmartVox](http://kb.smartvox.co.uk/), thanks to **John Quick**.

---

## [Distributed Load-Balancing with OpenSIPS and Redis](http://www.voztovoice.org/?q=node/585) (Spanish)
How to configure a cluster of OpenSIPS load balancers which communicates via Redis (in Spanish thanks to VozToVoice).

---

## [OpenSIPS and OpenXCAP Tutorial](http://openxcap.org/projects/openxcap/wiki/Configuration-new)
A standalone Presence Agent tutorial using OpenSIPS and OpenXCAP provided by [AG Projects](http://ag-projects.com/).

---

## [Voice Transcoding with OpenSIPS and Sangoma D-series cards](/docs/tutorials-sangomavoicetranscoding)
Performing audio transcoding using OpenSIPS and Sangoma hardware.

---

## [Scaling registrations with an OpenSIPS mid-registrar](/docs/tutorials-midregistrar)
How to integrate an OpenSIPS mid-registrar with your VoIP platform, allowing it to keep growing.

---

## [How To Configure a "Federated" User Location Cluster](/docs/tutorials-distributed-user-location-federation)
Everything about federated user location clustering: setup, configuration, routing, NAT traversal and HA!

---

## [How To Configure "Full Sharing" User Location Clusters](/docs/tutorials-distributed-user-location-full-sharing)
Detailed explanations and configuration examples on some essential "full sharing" user location setups.

---

## [Authentication and Accounting Using Diameter](/docs/tutorials-diameter-aaa)
How to configure and deploy the aaa_diameter module and the "app_opensips" freeDiameter application.

---

## [Cross-compiling](/docs/tutorials-crosscompile)
How to cross-compile OpenSIPS.

---

## [RCS: Managing Capabilities](/docs/tutorials-rcs-managing-capabilities)
String processing techniques for dealing with large lists of RCS capabilities.

---

## [Sending and Processing Diameter Requests](/docs/tutorials-diameter-client-server)
How to script Diameter Client and/or Server interactions for IMS Networks.
