# Size-Does-Not-Matter
Traditional **19-inch racks** are the standard in enterprise environments, but they are not the only option. This project explores how compact rack formats can provide the same level of organization, reliability, and flexibility while requiring significantly less space. 

---

# Homelab Overview

My homelab is split into two dedicated racks. One is responsible for networking, while the other provides the computing resources for self-hosted applications and experiments. Together they form a compact yet fully functional home infrastructure.

<p align="center">
  <img src="IMG_1698.jpg" alt="7-inch Rack" width="48%">
  <img src="IMG_1723.jpg" alt="9-inch Rack" width="48%">
</p>

---

# 7-inch Networking Rack

The 7-inch rack is dedicated entirely to network infrastructure. It is built around the **Ubiquiti UniFi** ecosystem and serves as the backbone of the homelab, providing routing, switching, and wireless connectivity.

### Hardware

* UniFi Cloud Gateway Ultra
* UniFi Flex PoE Switch
* UniFi Access Point U6+

The goal of this rack is simple: keep the network reliable, easy to maintain, and neatly organized despite the limited amount of space.

---

# 9-inch Homelab Rack

The 9-inch rack provides the computing platform for my homelab. It combines networking with a small Raspberry Pi cluster that runs various self-hosted services and development projects.

### Hardware

* UniFi Switch
* 4× Raspberry Pi 5 (16 GB)

The Raspberry Pi nodes are ideal for an always-on environment thanks to their low power consumption, compact size, and reliability. They are primarily used for containerized applications, networking experiments, Linux services, and learning distributed systems.

---

# Why Small Racks?

Large server racks are excellent for enterprise deployments, but for many homelabs they are simply unnecessary. Compact racks are more affordable, require less space, consume less power, and integrate naturally into a home environment.

This project demonstrates that thoughtful design is far more important than physical size. With proper planning and cable management, a compact rack can offer the same professional appearance and functionality as much larger systems.

> **Size does not define capability. Good design does.**
