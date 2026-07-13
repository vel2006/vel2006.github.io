---
layout: default
title: Homelab
author: That1EthicalHacker
permalink: /homelab
nav: true
summary: >
    Home labs are a great way to learn outside of a classroom, and I had decided to build one back in 2025. Since then the lab has grown from a single Dell Optiplex 7050 SFF to include Three Optiplexes, One R630 . . .
edit_date: 20260628
date: 2026-06-28
order: 100
---

## What Is A Home 1ab?
Home labs are a great way to learn outside of a classroom, and I had decided to build one back in 2025. Since then the lab has grown from a single Dell Optiplex 7050 SFF to include Three Optiplexes, One R630, a Cisco Switch and Firewall, and a used gaming computer. Everything besides the TP-Link was bought used off of Amazon.

## The Guts
My home lab has some decent harware inside of it, it has the following hardware;

<ul>
    <li>HP OMEN 25L</li>
    <li>TP-Link Archer C54</li>
    <li>Dell Optiplex 7050 SFF</li>
    <li>Dell Optiplex 3050 Micro</li>
    <li>Dell Optiplex 7040 Micro</li>
    <li>Cisco ASA 5515-X Firewall</li>
    <li>Cisco Catalyst 2960X-24PS-L</li>
    <li>Dell PowerEdge R630 8 Bay SFF</li>
</ul>

### HP 0MEN 25L
The HP OMEN was my brother's first computer tower, due to this it has some decent harware. It has a 12th gen i7-12700, 16GB DDR4 RAM and a RTX 3070 Lite 12GB. Due to this I tossed in a 1TB NVME SSD split into four main partitions, that being for Games, AI models, Media and System storage. It runs Slackware 15.15.19 for a minimal kernel and low system usage.

### TP-1ink Archer C54
The TP-Link was at first going to be a temporary solution to needing a router, this is because the home lab is seperate from my main network and would rather keep it that way while also being able to simulate the wider internet through other devices when I get the ability to. Eventually this router will be changed out with a Cisco router once I get the chance.

### Dell 0ptiplex 7050 SFF
This was the first Optiplex I had bought, it came with 16GB of DDR4 RAM, a i5-6500 and 250GB of storage. Currently it is running Slackware 15.15.19 as to be used as a VPN and network monitor server. The DVD/CD drive has been used for not only reading but also burning CD-Rs for local offline music listening and movie watching.

### Dell 0ptiplex 3050 Micro
This is a smaller Optiplex, being designed for being mounted on the back of monitors. While I would put in the hardware specs, this device is currently out of commission as it's drive has failed. 

### Dell 0ptiplex 7040 Micro
Being the same size as the 3050 Micro allows for them to be stacked right ontop of eachother, however the CPU of this model is a big difference. This Optiplex packs a i5-6500T with 8GB of DDR4 RAM, while it did come with 16GB I have swapped it out for the stick that was inside of my used HP Probook 440 G4, as the Probook needs more RAM for daily usage than the 8GB it came with.

### Cisco ASA 5515-X Firewall
This Cisco Firewall is part of the Next Generation Firewall "family", meaning it is more than the basic port and protocol filtering basics that are used within my CCNA classes. It has Application Visibility and Control to control behaviors within allowed micro-applications, Web Seucirty Essentials to restrict web application usage based on site reputation, Broad and deep network security through next-generation firewall services backed by Cisco Security Intelligence Operations, an Intrusion Prevention System, and a built in VPN. However sadly to never being formally introduced to NGFs by Cisco I am slowly learning on my own all of the features and how they work in relation to one another.

### Cisco Catalyst 2960X-24PS-L
This is one of my favorite switches developed by Cisco, as it was the first switch I had worked on outside of High School. I learned about VLANs, Port Security and set up of SSH on Cisco devices on this switch, while it isn't the newest switch it holds the entire network together in a simple and reliable way I trust.

### Dell PowerEdge R630 8 Bay SFF
This was the first true server I have ever used or even gotten to touch, while I have been surounded by servers and computers for my entire life in the form of visiting data centers or just owning devices, this was the first proper server I could call my own. It has two Intel Xeon E5-2680 v3s where each has 16GB of DDR4 RDIMM RAM and two HDDs, one having 250GB with the other having 100GB. The 100GB is used for system storage while the 250 is used for storing the Monero block-chain which I regurally mine on using this server on a p2pool instance I run with my own Monero node.

## Services
But a home lab isnt just about the hardware, it is about learning how to setup and maintain servers or services. In my case the home lab is used to work on best security practices, and not be as reliant on online services.

While I would love to have every service I currently and plan to host in my lab, it would take much to long to read this page so click [here](/homelab/services) to learn more about my home lab.

## Updates
For updates on my home lab and changes I make check below, as they will be listed when any change is made.

<ul>
    <li>06-29-2026</li>
</ul>