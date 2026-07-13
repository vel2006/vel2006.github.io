---
layout: default
title: Projects
author: That1EthicalHacker
permalink: /projects
nav: true
summary: >
    Over the last three years, pushing four years (at time of writing) I have worked on several projects that relate to cybersecurity. Some for friends . . . .
edit_date: 20260710
date: 2026-07-10
order: 100
---

Over the last three years, pushing four years (at time of writing) I have worked on several projects that relate to cybersecurity. Some for friends, others for personal gain, and some were just to help out my school. But the projects mentioned here are some of my personal favorite, not the best I've performed on. My favorite not best, big difference, as this is my blog and I get to choose what I show you.

## Projects

The projects shown here are not just "I did X, look at me" or "I made Y, look at me" but rather an in-depth explanation of something I did or made. Some of which I cannot talk to much about due to material and or information being protected by either copyright or some sort of NDA.

### Full Network Takeover

This project is still in development / works, so I will not speak all to much about it. However, I can say that it is a Python script designed to take over an entire network if PortSecurity defenses are not enabled.

Now some other 1337 network junkies out there are already saying "Well no that would not work for a full network due to how a MAC address cannot be used for several IP addresses if you try to use ARP Spoofing against a single device. So at most you would have to change the route of traffic using some other means!" That is true. However, what I am wanting to do with this script is different than the standard ARP Spoofing attack. I am wanting to make this script work where the connected devices see it as a L2 or L3 switch, that way the issue of there being several IP addresses associated with one MAC address is not an issue.

It also means that I could fake the attacking device to look like a Cisco switch for example as to then attempt to seem like a higher priority bridge as to force traffic onto the attacker's device instead of a real switch.

### WiFi Harassment

This project is almost done, I started development during an overseas trip. This tool is a WiFi attack suite. It can do everything from finding all wireless devices connected in a network to forcing itself to join a WPA2-PSK network.

This script is one of, if not the most advanced project I have every worked on. I plan to release it in September of 2026.

### Anti-Bot

Anti-Bot is a project I have been working on for some time now. The idea stems from MadHermitLabs's idea for a way to hold several files within a single filesystem like AWS bucket using a single large encrypted file. However, instead of mine being for preventing the analysis of files held within a cloud storage enviroment, it is designed to be used on website content as to combat the agressive scraping of AI Bots and hackers.

It would work in the same way that a public key encryption algorithm does, except that not only would the content be encrypted but obfuscated. Where one part of it, usually the encryption's key is derived of the obfuscation's. While some might claim that if you would know the obfuscation key you could easily determine the encryption key, and that is the point. The point of this project / tool is not to stop scraping, as it will happen whether if you want it to or not, it is designed to make scraping more expensive.

So why not just use a bot check or some other anti-scraping method? Simple, way's around it. No matter the security of something, it could be the best encryption of the current day, but give three years and it might be dated. Take for example TDES (Tripple DES), at the time when it was released TDES was considered secure, this is no longer the case as of 2016 with CVE-2016-2183 and CVE-2016-6329, or the simple bot checks that ask for you to click on a box. Both of these methods are now inefective in their respected part of security, no matter the design eventually it will be broken.

And sure, while computing advances Anti-Bot will fall to the same fate as TDES, I can make it as taxing as possible to decrypt and deobfuscate as possible without specialty hardware, which is exactly the point. Because while SHA-1 hashes are now easy to crack on even a RTX 3070 12 GB, it still takes time to crack.

<br>

For the time being, those are all of the projects I will be showing here. Do keep in mind I am always working on something new, so check back in every now and then to see what I put out there for the world to judge :)