---
layout: post
title:  "Blog 0: Proxmox"
date:   2020-01-30 10:00:00 -0700
categories: Setting up Proxmox
---
Proxmox is a Debian open source platform that allows for the virtualization of IT infrastructure through KVM hypervisors and LXC containers. Proxmox is a useful tool in maximizing resources as it provides an easy to maneuver GUI and command line interface for creating new virtual machines and configuring already existing nodes. Proxmox can be installed on to hypervisors such as Virtualbox and VMware through ISO images, usb drives and CD roms, or on bare-metal hardware such as SSDs. 

[[https://github.com/emejia52/emejia52.github.io.wiki/[Proxmox GUI]https://pve.proxmox.com/pve-docs/images/screenshot/gui-datacenter-summary.png]]

Proxmox allows the user to adjust the scaling of storage and resources to meet the purposes of the applications on a single interface. Clustering multiple nodes through the interface is easy to accomplish and allows the user to adjust all connected nodes from one interface.  New nodes can be added with relative ease through the command: 

 hp2# pvecm add IP-ADDRESS-CLUSTER

This will add the node into the cluster and allow the user to access it from the Proxmox GUI.

 - [Proxmox Documentation](https://pve.proxmox.com/wiki/Main_Page)
