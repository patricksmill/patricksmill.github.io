---
layout: post
title:  "My Home Server: A Dive into Docker"
date:   2025-09-30 12:35:19 -0400
categories: software
---

I built my first computer during the pandemic in 2020. Since then, I have gradually been upgrading it one part at a time until, like the ship of Theseus, it is comprised of new replacement parts. This left me with an entire PC's worth of old parts. My summer project since coming home from school has been building a Family home server that serves as a media device.

The server runs on Ubuntu Server, and utilizes several Docker containers:

* For family photos, I use Immich, a self-hosted Google Photos alternative.
* My (Dad's) music collection is stored on the server, and I use Navidrome to access them from other devices.
* Romm acts as a personal retro video game library. I can download my game backups to any device.
* Portainer is used to manage and update the Docker stacks.

![Homepage]({{ "/assets/images/homeserver/homepage.png" | relative_url }})

This is my [Homepage](https://gethomepage.dev/) setup. I have it as the default page on all of my devices.
{: .caption .caption-center }


**Skills learned/practiced:**

* Linux server administration (Ubuntu Server)
* Docker
* Network configuration and port management
* Media file organization and metadata management
* Storage management and file system organization
* Troubleshooting hardware compatibility issues
* Backup and data recovery strategies
* Web-UI administration interfaces
* Network File Sharing (SMB)
