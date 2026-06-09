---
title: "Tutorials"
description: "How to provide ICE end-to-end NAT traversal support for RTP streams"
---

## OpenSIPS - Getting Started
A crash course about how to do a quick installation of OpenSIPS ( downloading sources, compiling, installing, etc )  and OpenSIPS Control Panel ( installing, provisioning users ), and have a fully functional platform in a matter of minutes. 
| [ver 1.8.x](/docs/tutorials-gettingstarted) |
| --- |

---

## Topology Hiding with OpenSIPS
Short introduction on configuring and using the topology_hiding module in OpenSIPS
| [ver 2.1](/docs/tutorials-topology-hiding) |
| --- |

---

## Accounting in OpenSIPS 
Unveils how SIP accounting works in OpenSIPS, from basic to complex scenarios with custom CDRs and multi-leg accounting for call forwarding. Everything is backed up by detailed explanations and working scripts examples.
| [2.2 & 2.3](/docs/tutorials-advanced-accounting) |
| --- |

---

## Easier scripting with the script_helper module
Module description and a complete usage example
| [ver 1.11](/docs/tutorials-scripthelper-1-11) |
| --- |

---

## Call Recording using SIPREC
This tutorial shows you how you can do call recording using the SIPREC standard.
| [ver 2.4](/docs/tutorials-siprec-2-4) |
| --- |

---

## Fraud detection with OpenSIPS 2.1
Description of the new module along with a complete usage example
| [ver 2.1](/docs/tutorials-frauddetection-2-1) | [ver 3.1](/docs/tutorials-frauddetection-3-1) |
| --- | --- |

---

## Message compression and compaction
Module description and a complete usage example
| [ver 2.1](/docs/tutorials-compression-2-1) |
| --- |

---

## Emergency calls using OpenSIPS
Architecture design and complete usage examples
| [ver 2.1](/docs/tutorials-emergency-2-1) | [latest ver](/docs/tutorials-emergency-2-2) |
| --- | --- |

---

## WebSocket and WebSocketSecure Integration with OpenSIPS
How to add Websocket, and Websocket Secure (2.2+ only) capabilities to your existing OpenSIPS deployment.
| [ver 2.2](/docs/tutorials-websocket-2-2) | [ver 2.1](/docs/tutorials-websocket-2-1) |  | [ver older than 2.1](/docs/tutorials-websocket) |
| --- | --- | --- | --- |

---

## Dynamic Routing with Failover
How to configure OpenSips to route phone calls based on the dialed number.  This is a detailed tutorial on how to use the drouting module with mysql and includes failover support.  It does not include load balancing.
| [ver 1.6.x](http://www.unixnews.net/2010/09/dynamic-routing-with-opensips.html) |
| --- |

---

## B2BUA
Which is the architecture of the B2BUA implementation, how to define service scenario documents and how to configure OpenSIPS to offer B2BUA services.
| [ver 1.6.x](/docs/tutorials-b2bua-1-6) | [ver older than 3.2](/docs/tutorials-b2bua) | [ver 3.2.x](/docs/tutorials-b2bua-3-2) |
| --- | --- | --- |

---

## Presence Agent
Presence Agent - design and configuration of Presence Agent in **OpenSIPS**
| [latest ver](/docs/tutorials-presence) |
| --- |

---

## Load-Balancing
How to use the load-balancing module from **OpenSIPS** to do traffic routing based on the real load of the destinations.
| [ver 1.5.x](/docs/tutorials-loadbalancing) | [ver 1.9.x](/docs/tutorials-loadbalancing-1-9) |
| --- | --- |

---

## Key-Value Interface
How to use the Key-Value interface in **OpenSIPS** in order to store, persistently or not, key-value information
| [latest ver](/docs/tutorials-keyvalueinterface) |
| --- |

---

## Event Interface
How to use **OpenSIPS** Event Interface in order to send events to external applications.
| [ver 1.8.x](/docs/tutorials-eventinterface-1-8) | [latest ver](/docs/tutorials-eventinterface) |
| --- | --- |

---

## MemCache Usage
How to use the memcache support in **OpenSIPS** in order to reduce the number of DB queries (authentication for example)
| [ver 1.5.x](/docs/tutorials-memorycaching) |
| --- |

---

## OpenSIPS - FreeSwitch Media Integration
This tutorial presents the concept and implementation of a realtime integration of OpenSIPS SIP server and FreeSWITCH media server. OpenSIPS is used a SIP server, while the purpose of FreeSWITCH is to provide a full set of media services - like voicemail, conference, announcements, etc
| [ver 1.8.x](/docs/tutorials-opensipsfreeswitchintegration) |
| --- |

---

## Realtime OpenSIPS - Asterisk Integration
How to implement a realtime integration of OpenSIPS SIP server and Asterisk media server for Voicemail, conference and announcement services.
| [ver 1.5.x](/docs/tutorials-opensipsasteriskintegration) | [ver 1.8.x](/docs/tutorials-opensipsasteriskintegration-1-8) |
| --- | --- |

---

## Concurrent calls limitation
How to control in **OpenSIPS** how many concurrent calls a user is allow to do.
| [ver 1.5.x](/docs/tutorials-concurrentcallslimitation-1-5) | [ver 1.8.x](/docs/tutorials-concurrentcallslimitation) |
| --- | --- |

---

## TLS setup
How to compile and configure the TLS support in **OpenSIPS** / **OpenSER** - script example included
| [ver 1.2.x](http://www.opensips.org/html/docs/tutorials/tls-1.2.x.html) | [ver 1.3.x](http://www.opensips.org/html/docs/tutorials/tls-1.2.x.html) | [ver 1.4.x](http://www.opensips.org/html/docs/tutorials/tls-1.4.x.html) | [ver 1.5.x](http://www.opensips.org/html/docs/tutorials/tls-1.4.x.html) | [ver 2.1.x](/docs/tutorials-tls-2-1) | [ver 2.2.x](/docs/tutorials-tls-2-2) |
| --- | --- | --- | --- | --- | --- |

---

## Replace 183 early media reply with perl module
Example script showing how to replace SIP status replies on the fly, as this is not (yet?) possible within the OpenSIPS routing script: [Replace 183 early media reply with 180 (Ringing)](/docs/tutorials-perl-183-to-180)

---

## A basic tutorial on RADIUS
How to install, configure, integrate and use FreeRADIUS server and Radiusclient-ng with OpenSIPS modules for accounting and authorization.
| [ver 1.6.x](/docs/tutorials-radius) |
| --- |

---

## OpenSIPS with Radius support
OpenSIPS with MySQL and FreeRADIUS integration and installation/configuration :
| [ver 1.5.x](http://voiprookie.blogspot.com/2009/04/freeradius-and-mysql.html) |
| --- |

---

## OpenSIPS and MediaProxy
MediaProxy 2.3.x and  OpenSIPS 1.5.x Integration:
| [ver 1.5.x](http://voiprookie.blogspot.com/2009/04/blog-post.html) |
| --- |

How to provide [ICE end-to-end NAT traversal support for RTP streams](http://mediaproxy.ag-projects.com/projects/mediaproxy/wiki/ICE)

---

## OpenSIPS and MSRP integration

* [SylkServer integration](/docs/msrp-chat) for multiparty conferencing and XMPP gateway
* [MSRPRelay integration](/docs/msrp-relay) for NAT traversal of MSRP chat and MSRP file transfers

---

## How to install opensips in Red Hat EL 5
How to install opensips 1.5 in a Red Hat Enterprise Linux 5 platform with Mysql Support:
| [ver 1.5.x](/docs/tutorials-opensipsonredhat) |
| --- |

---

## SIP Redirect with script
How setup OpenSIPS as a SIP redirect using a external script - also restricting base on ip address:
Please note since I am new to OpenSIPS this may need be cleaned up a bit.
| [ver 1.6.x](/docs/tutorials-redirect) |
| --- |

---

## OpenSIPS and fail2ban
This is a small tutorial so you can use fail2ban together with opensips to block via firewall the attackers that are using wrong authentication credentials
| [ver 2.4](/docs/tutorials-fail2ban) |
| --- |

---

## OpenSIPS, CentOS and MI_XMLRPC
Small tutorial on how to compile OpenSIPS or CentOS. It includes a vauable tip on how to compile correctly the MI_XMLRPC module. 
| [ver 1.6.3](/docs/tutorials-installoncentos) |
| --- |

---

## OpenSIPS Tutorials from SmartVox
A compilation of various tutorials covering topics like software installation (including MediaProxy on CentOS), authentication, clustering and comparing OpenSIPS with Asterisk provided by [SmartVox](http://kb.smartvox.co.uk/), thanks to **John Quick**.
| [Tutorial's Home Page](http://smartvox.co.uk/category/voip/) |
| --- |

---

## Distributed Load-Balancing with OpenSIPS and Redis (Spanish)
How to configure a cluster of OpenSIPS load balancers which communicates via Redis (in Spanish thanks to VozToVoice).
| [ver 1.8.2](http://www.voztovoice.org/?q=node/585) |
| --- |

---

## OpenSIPS and OpenXCAP Tutorial
A standalone Presence Agent tutorial using OpenSIPS and OpenXCAP provided by [AG Projects](http://ag-projects.com/).
| [Tutorial Page](http://openxcap.org/projects/openxcap/wiki/Configuration-new) |
| --- |

---

## Voice Transcoding with OpenSIPS and Sangoma D-series cards
Performing audio transcoding using OpenSIPS and Sangoma hardware
| [ver 1.10](/docs/tutorials-sangomavoicetranscoding) |
| --- |

---

## Scaling registrations with an OpenSIPS mid-registrar
How to integrate an OpenSIPS mid-registrar with your VoIP platform, allowing it to keep growing!
| [ver 2.3](/docs/tutorials-midregistrar) |
| --- |

---

## How To Configure a "Federated" User Location Cluster
Everything about federated user location clustering: setup, configuration, routing, NAT traversal and HA!
| [ver 2.4](/docs/tutorials-distributed-user-location-federation) |
| --- |

---

## How To Configure "Full Sharing" User Location Clusters
Detailed explanations and configuration examples on some essential "full sharing" user location setups
| [ver 2.4](/docs/tutorials-distributed-user-location-full-sharing) |
| --- |

---

## Authentication and Accounting Using Diameter
How to configure and deploy the aaa_diameter module and the "app_opensips" freeDiameter application
| [ver 3.2](/docs/tutorials-diameter-aaa) |
| --- |

---

## Cross-compiling
How to cross-compile OpenSIPS
| [ver 3.2](/docs/tutorials-crosscompile) |
| --- |

---

## RCS: Managing Capabilities
String processing techniques for dealing with large lists of RCS capabilities
| [ver 3.3](/docs/tutorials-rcs-managing-capabilities) |
| --- |

---

## Sending and Processing Diameter Requests
How to script Diameter Client and/or Server interactions for IMS Networks
| [ver 3.5](/docs/tutorials-diameter-client-server) |
| --- |
