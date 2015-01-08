# LXD: The Container-Based Hypervisor That Isn't

## Speaker: Tycho Andersen

Tycho is a software engineer at Canonical in the Cloud Development and Operations group focusing on Linux containers and their implementations. He holds degrees from the University of Wisconsin-Madison and Iowa State University, and has co-authored several peer-reviewed papers. In his spare time he maintains a tiling window manager, collects programming languages, rides bicycles, and climbs mountains.

## Description: 

LXD, announced by Canonical at ODS Paris 2014, is a container-based "hypervisor". Hypervisor here is in quotes because LXD isn't a hypervisor in the traditional sense because the underlying virtualization technology is LXC and Linux containers. However, it will offer all of the things you expect from your hypervisor: (hardware-based) isolation from the host, image based workflows, live migration, and a nice API for interacting with it all.

In this talk I will cover LXD's current feature set including the command line tool and API for manipulating containers on a host and give an overview of the security features lxc/lxd offers. I will also cover future directions in LXD, including areas of focus and areas that are opportunities for contributions.
