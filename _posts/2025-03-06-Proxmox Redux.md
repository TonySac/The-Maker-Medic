---
title: Proxmox Redux
date: 2025-03-06
categories: [Blog]
tags: [Blog, Homelab]
image: /assets/img/PVE_Neo.png
---

I've been putting this off for awhile but after building out my NAS I decided I also needed to rebuild my HomeLab. I've been  neglecting things for far too long but also learned a lot since starting this journey so it would be nice run with a fresh install.

For better or worse, my home has become reliant on the HomeLab Server so I needed to pick a good time for the overhaul and minimize downtime. This was also a perfect opportunity to put my NAS with its NFS shares and Proxmox backups to the test.

Surprisingly the process went well. Just a quick flash of the latest Proxmox ISO to a USB drive and within about 10 minutes I was booted back into Proxmox and able to log into the network GUI. Once I mounted my NFS share I saw all my old backups and restored the nessicary VMs.

I spent about another hour making sure everything in the Home Assistant VM was working correctly. Sometimes the MQTT stuff acts up on a restore but it just required a reinitialization. 

With the restore complete, I can move on to what I was actually looking forward to... migrating Home Assistant to a new VM and setting up some additional self hosted services. I'll use that to procrastinate the next big overhaul... OPNSense... Stay tuned?