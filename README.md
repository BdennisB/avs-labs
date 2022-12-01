![AVS MicroHack](/Images/schema/AVSMicroHackPic.png)

# Azure vMware Solution (AVS) specific LAB scenarios for a 2 hour workshop

## [Scenario](#scenario)

## [Prerequisites](#prerequisites)

## Scenario

In this lab , you will :

- be given an overview of the AVS architecture,
- create an NSX-T segment using the portal and verify it using NSX-T
- create a DNS and DHCP service
- carve out and mount an Azure Netapp Filesystem and NFS mount it as a datastore

This lab is built of :

- 6 vMware vSphere Clusters hosted on-premises along with 6 vCenters,
- 6 AVS solution hosted in Azure regions aligned with nested On Prem vCenters instances,
- A jumpbox per user deployed in Azure to control AVS and On Prem instances.

![Lab schema](/Images/schema/LABLBG.jpeg)

Each pair of AVS + on-premises cluster is assigned a unique IP range for the jumpbox. [IP ranges info](docs/Appendix.md)

## AVS Design Concepts Video

[![Azure VMware Solution MicroHack design video](https://res.cloudinary.com/marcomontalbano/image/upload/v1628861760/video_to_markdown/images/youtube--BGw5Nv_Kpiw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/BGw5Nv_Kpiw "Azure VMware Solution MicroHack design video")
