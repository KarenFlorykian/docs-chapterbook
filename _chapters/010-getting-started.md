---
title: Getting started
slug: getting-started
abstract: A guide to quickly setting up your site with this theme.
---

The best fitted for people aiming to shift performance and security tests execution left, save time and effort on framework setup, test results analysis, as well as receive timed and accurate results and metrics reporting


> This tutorial will guide you how to instal Carrier platform.

## Hardware requirements:
system_requirements, hardware, installation

### Carrier instance requirements:
- 4 cpu (and more)
- 16 GB RAM (and more)
- 100-500GB SSD (root drive or mounted drive)
    * Mounted drive is better option as it gives possibility to move carrier data to other instance or not lose data in case if instance is terminated accidentally.
- Static IP or public DNS

### Load generator:
- 2 cpu (and more)
- 8 GB ram (and more)

## Prerequisites
- instance launched in accordance with hardware requirements with root permissions
- the following inbound ports are open (security group for cloud):
    * http – 80
    * ssh - 22
    * tcp - 3100, 5672, 8086
- all daily updates that might trigger docker restart or termination should be disabled


[Learn]({{ site.baseurl }}/#getting-started)

---
```
This file is located at: {{ page.path }}
```
---
    
