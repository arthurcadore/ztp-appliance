# Zero Touch Provisioning Appliance

This project provides a Zero Touch Provisioning (ZTP) appliance based on Docker Compose, which combines DHCP and TFTP servers to automate the provisioning of networked devices.

---

## Overview

The ZTP Appliance includes two main services:

- DHCP Server
Responsible for assigning IP addresses to client devices and indicating the location of the TFTP server.

- TFTP Server
Provides the configuration files and images required for client booting/provisioning.

This combination is used in network environments for remote boot, automatic configuration, and hands-free booting.
