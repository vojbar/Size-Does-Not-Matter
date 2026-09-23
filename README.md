# Size Does Not Matter

A professional network doesn't have to take up a server room.

This project started with a simple goal: to build a professionally organized network infrastructure where all essential networking equipment is kept in one place, mounted in a dedicated rack, and easy to manage. From there, the setup evolved into a compact infrastructure built around 7-inch and 10-inch rack systems, combining networking, computing, and a few things that are there simply because they look good.

The infrastructure is divided into two racks, each with a specific purpose:

- **7-inch Networking Rack** - routing, switching, and wireless infrastructure.
- **10-inch Computing Rack** - compute nodes, services, containers, and experimentation.

<p align="center">
  <img src="IMG_1698.jpg" alt="Showcase of the Racks at an Education Fair" width="47%">
  <img src="IMG_1723.jpg" alt="Showcase of the Racks at an Education Fair" width="47%">
</p>

<p align="center">
  <strong>7-inch Networking Rack and 10-inch Computing Rack</strong><br>
  <em>Showcased and presented to fellow students at an Education Fair</em>
</p>

---

# 7-inch Networking Rack

The 7-inch rack is dedicated to the networking infrastructure of the entire setup. It is built around Ubiquiti's UniFi ecosystem, bringing routing, switching, wireless connectivity, and network management together within a single platform. Keeping the networking infrastructure in its own dedicated rack makes the network easier to manage, keeps the core connectivity equipment organized in one place, and provides a clear connection between the network and the rest of the infrastructure.

## Rack Components

- **UniFi U6+**
- **UniFi Flex**
- **0.5U Patch Panel**
- **Raspberry Pi 4 2GB**
- **PoE++ Injector**
- **0.5U Brush Panel**
- **UniFi Cloud Gateway Ultra**

The U6+ is positioned on top of the rack to keep its antennas clear of the surrounding hardware. Directly below it, the Flex provides network connectivity and PoE for the access point, while the Ethernet Patch Panel keeps the network connections organized and the front of the rack clean. A Raspberry Pi is included as an additional node for potential network-related services such as DNS. The PoE Injector below it supplies power to the Flex, followed by a Brush Panel that keeps the remaining cabling organized. At the bottom of the rack, the Cloud Gateway Ultra serves as the network gateway and central controller for the UniFi infrastructure.

---

# 10-inch Computing Rack

The 10-inch rack is dedicated to the computing infrastructure of the setup. It is built around Raspberry Pi as the main computing platform, chosen for its balance of performance and low power consumption, making it well suited for continuously running services and workloads. Its compact single-board design also fits naturally into the 10-inch form factor, while Power over Ethernet allows the computing nodes to receive both power and network connectivity through a single cable, keeping the rack clean, organized, and easy to manage.

## Rack Components

- **UniFi Switch Ultra 210W**
- **0.5U Patch Panel**
- **4× Raspberry Pi 5 4GB**
- **0.5UBrush Panel**

The UniFi Switch Ultra 210W is mounted on the upper shelf and provides network connectivity and PoE for all four Raspberry Pi nodes. With a 210W PoE budget, it can power all four nodes simultaneously while retaining significant capacity even under high load. Directly below, the Ethernet Patch Panel keeps the network connections organized and the front of the rack clean. Two SBC shelves hold the four Raspberry Pi 5 4GB nodes, with two on each shelf. Each Raspberry Pi is equipped with a PoE+ Module for power and network connectivity, along with an NVMe storage module connected through the Raspberry Pi 5's PCIe interface. The 256 GB NVMe SSD serves as the primary boot drive and provides additional local storage. A Brush Panel at the bottom provides a clean path for the remaining cabling and keeps it out of sight.

---

> **Hardware sponsorship**  
> The racks used in this project were provided by DeskPi, a company offering compact rack systems in various form factors and related accessories. The sponsorship did not influence the project's design decisions, technical evaluation, or opinions.

[DeskPi Store](https://deskpi.com/)
