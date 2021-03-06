---
copyright:
  years: 1994, 2017
lastupdated: "2017-09-27"
---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

# Microsoft Windows Update Information
IBM provides OS and software update services for Microsoft Windows Server environments free of charge.

All update services at SoftLayer share the following features:
* Update traffic is routed from your server, over your private VLAN, to the private service network
* Update traffic is part of your unlimited private network bandwidth and does not reduce public bandwidth allotments.
* Updates speeds are faster than updating from vendors directly (upgraded ports speeds available on demand)
* Updates are readily available during worldwide heavy critical update days.
* In emergency situations, public ports can be shut down while still allowing updates to occur over the private network
* Servers are pre-configured to update automatically at deployment with manual updates available on demand.


SoftLayer update servers are on the private service network with the following location identifiers.

Microsoft: **wsus01.service.softlayer.com**

Always test kernel or service pack upgrades before you install them in production server environments. You can find technical information that is related to specific hardware, OS, and applications deployed by IBM in the FAQ or drivers section inside the customer Web Portal. IBM engineers continually test kernel and service pack upgrades and post related information (including drivers) to help the upgrade process.


## WSUS - Windows Server Update Services

Microsoft Windows servers automatically pull updates from local Windows Server Update Services (WSUS) servers.

For Microsoft Windows operating systems, servers are configured by default to download and install patches as soon as they become available. The server restarts automatically if it is required. These updates are done to help protect servers from crucial vulnerabilities. If you prefer to schedule your updates differently, you can change the update schedule through the **Windows Updates** feature in the Control Panel.
