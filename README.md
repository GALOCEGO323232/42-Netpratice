*This project has been created as part of the 42 curriculum by kgagliar.*

# NetPractice

## Description

NetPractice is an introductory training project focused on fundamental computer networking concepts. The goal of the project is to understand how devices communicate within a network and how proper network configuration allows communication between different hosts.

The project consists of **10 progressive levels**, each presenting a non-functional network topology. The objective is to analyze the network diagram and correct the configuration by adjusting parameters such as IP addresses, subnet masks, gateways, and routing paths.

Through these exercises, students gain practical experience with IP addressing, subnetting, and routing, while developing a deeper understanding of how data travels between devices across multiple networks.

---

# Instructions

## Running the Training Interface

To run the NetPractice training interface:

1. Download the project files from the 42 intranet.
2. Extract the files to any directory on your computer.
3. Open the training interface by opening the file:

```
index.html
```

4. Enter your **42 intranet login** in the required field.
5. Click **Start!** to begin the training.
6. Select a level and carefully read the objective.

---

## Using the Interface

For each level:

1. Analyze the network diagram and identify the devices involved.
2. Modify only the **editable fields** (non-greyed fields).
3. Configure the required network parameters:

   * IP address
   * Subnet mask
   * Default gateway
4. Ensure all hosts can communicate correctly.
5. Click **Check again** to validate your solution.

The logs displayed at the bottom of the interface can help identify issues such as invalid IP addresses or missing gateways.

---

## Exporting Configurations

After successfully completing a level:

1. Click **Get my config** to export the configuration.
2. Download the generated configuration file.
3. Save the file using the naming convention:

```
level1.json
level2.json
level3.json
...
level10.json
```

⚠️ Make sure your **42 login is entered before exporting**, since the system generates configurations based on your login.

---

# Submission Requirements

Your repository must contain:

* **10 exported configuration files (one per level)**
* Files must be named `level1.json` through `level10.json`
* All files must be placed **at the root of the repository**

Example structure:

```
level1.json
level2.json
level3.json
level4.json
level5.json
level6.json
level7.json
level8.json
level9.json
level10.json
README.md
```

Each file must represent a **valid and complete solution** for its respective level.

---

# Resources

## Networking Concepts Studied

This project covers several essential networking concepts:

* **TCP/IP Addressing** — understanding how IP addresses are structured and assigned
* **Subnet Masks** — determining which devices belong to the same network
* **Default Gateway** — the router responsible for forwarding packets to other networks
* **Routers** — devices that connect different networks and route packets between them
* **Switches** — devices that connect multiple devices within the same local network
* **Routing Tables** — structures used by routers to determine packet forwarding paths
* **OSI Model Layers** — conceptual model describing how data moves across a network
* **Network Segmentation** — dividing networks into smaller subnetworks

Understanding these concepts is essential for designing and troubleshooting real-world networks.

---

## References

Some useful resources for networking concepts include:

* RFC 791 — Internet Protocol
* Subnetting tutorials and subnet calculators

---

## Use of AI

Artificial Intelligence tools were used as a **learning aid** during this project.

AI was used to:

* Help understand networking concepts such as subnetting and IP addressing
* Clarify the role of routers, switches, and gateways
* Explain theoretical models such as the OSI model

However, the NetPractice exercises themselves were solved independently.
All network configurations were analyzed and implemented manually based on the networking concepts learned.
