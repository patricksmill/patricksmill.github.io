---
layout: post
title:  "Home Server"
date:   2025-09-30 12:35:19 -0400
categories: software
---

I built my first computer during the pandemic in 2020. Since then, I have gradually been upgrading it one part at a time until, like the ship of Theseus, it is comprised of new replacement parts. This left me with an entire PC's worth of old parts. My summer project since coming home from school has been building a Family home server that serves as a media device.

The server runs on CasaOS on top of Ubuntu Server, and utilizes several Docker containers:

* For family photos, I use Immich, a self-hosted Google Photos alternative.
* I ripped our old DVDs using MakeMKV and organized them using Radarr for movies and Sonarr for TV Shows
* Plex Media Server streams these backups to devices on the network, serving as a Self-hosted Netflix

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