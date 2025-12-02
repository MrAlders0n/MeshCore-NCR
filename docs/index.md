# Welcome to Greater Ottawa Mesh Enthusiasts!

[Join us on Discord!](https://discord.gg/WSyNd8SfNr)

## About
Welcome to the Ottawa mesh group.  
See the info below for default frequencies, and please join our Discord to chat with us.

Both **MeshCore** and **Meshtastic** are protocols that run on top of LoRa radios.  
LoRa (Long Range) is a low-power modulation suited to long-distance links at modest data rates.  
By building on LoRa, both systems enable decentralized, low-cost community networks.

Most of the city is currently running **MeshCore** with some **Meshtastic** presence scattered around.  
We have roughly **50 static MeshCore repeaters** around the region, linking Carleton Place, Ashton, Stittsville,  
Kemptville, Kanata, Barrhaven, Westboro, Downtown, Old Ottawa South, Vanier, Orléans, and areas near Cumberland.

If you are interested in playing an active role in the community, we are always looking for volunteers.  
Reach out to **MrAlders0n** with what you would like to help with.

### Community Outreach
* Spread the word on social media (Reddit, Facebook, TikTok) or put posters up around the community

### Community Support
* Welcome new users in Discord and answer questions

### Fabrication Team
* For people who want to be involved in custom PCB design

### Knowledge Curators
* Maintain wiki content

### Tower Tech
* For people who like to climb stuff and help install or maintain repeaters

## MeshCore vs Meshtastic
**Meshtastic** is a peer-to-peer mesh where every node can forward traffic. It is flexible for ad-hoc use but prone  
to congestion in larger networks. Because it relies on nodes that often move, coverage can also be unreliable.

**MeshCore** relies on fixed repeaters for routing, providing a more stable and scalable backbone for city-wide coverage.

[Watch an overview on YouTube](https://www.youtube.com/watch?v=tXoAhebQc0c)

## MeshCore
To get started and connect to the mesh, begin with a **companion node**.  
Pick a build that fits your needs, then flash MeshCore companion firmware to the device.

From there, you can explore repeater builds and mounting options to expand coverage and strengthen the Ottawa mesh.

### Getting Started
* [Roles Explained](MeshCore/RolesExplained)
* [F.A.Q](MeshCore/F.A.Q)

### Hardware
* [Companion Nodes](MeshCore/CompanionNodes)
* [Repeater Nodes](MeshCore/Repeaters)
* [Mounting Options](MeshCore/RepeaterMountingOptions)

### Configuration
* [Flashing a companion node](MeshCore/FlashCompanion)
* [Flashing a repeater node](MeshCore/FlashRepeater)
* [Flashing a room server](MeshCore/FlashRoom)
* [Recommended Repeater Build Instructions](MeshCore/BuildRepeaterRec)
* [MeshCore to Discord using Meshcore-HA](MeshCore/MeshCore2Discord)
* [Compiling Wifi Firmware for Heltek v3](MeshCore/Heltekv3Wifi)
* [Compiling RAK4631 firmware with a Custom Display](MeshCore/RAKCustomDisplay)

### MeshCore Packet Analyzer
* [Overview](MeshCore-Packet/Overview)
* [Add a Companion Listener](MeshCore-Packet/OnboardObserver)
* [Add a Standalone Listener](MeshCore-Packet/OnboardRepeaterObserver)

### Ottawa Deployment
* [Repeaters and Coverage](MeshCore/Repeaters & Coverage)
* [Frequency Settings](MeshCore/Frequency Settings)
* [Wanted Repeater Locations](MeshCore/Wanted Repeater Locations)

## Meshtastic
The Meshtastic section is a work in progress.

* [Getting Started](Meshtastic/Getting Started)
* [Frequency Settings](Meshtastic/Frequency Settings)

## Useful Resources
* [Austin Mesh](https://www.austinmesh.org/)  
  Useful information and real-world testing of mesh nodes
* [Cold Weather Charging of Lithium-Ion Batteries](https://yycmesh.com/2025/04/19/cold-weather-charging-of-lithium-ion-batteries-real-world-lessons-from-the-meshtastic-community/)  
  A great write-up on repeater performance in extreme cold with LiPos

---

*This wiki is maintained by the Greater Ottawa Mesh Enthusiasts to provide information and track deployments.*
