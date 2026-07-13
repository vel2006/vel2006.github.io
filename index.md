---
layout: default
title: Home
author: That1EthicalHacker
permalink: /index
nav: true
summary: >
    This is a summary, and if this is the top page something BAD has happened D:
edit_date: 20260628
date: 2026-06-28
order: 1000
---

## About The Last Blog
As some might know, this is infact the second time I have had a blog like thing, this is because I decided to nuke the first one after realizing all the mistakes made in it's design, so as to not spend months trying to fix the entire site this one was built to replace it.

<br>

## Recent Post
{% assign pages = site.pages | where: "layout", "post" | where_exp: "p", "p.edit_date" | sort: "edit_date" %}
{% assign newest_date = pages | last | map: "edit_date" | first %}
{% assign newest_post = pages | where: "edit_date", newest_date | sort: "order" | last %}
<h3>{{ newest_post.title }} {{ newest_post.date }}: <a href="{{ newest_post.url | relative_url }}">here</a></h3>
{{ newest_post.summary }}

## Recent Page
{% assign page_pages = site.pages | where: "layout", "default" | where_exp: "p", "p.edit_date" | sort: "edit_date" %}
{% assign newest_page_date = page_pages | last | map: "edit_date" | first %}
{% assign newest_page = page_pages | where: "edit_date", newest_page_date | sort: "order" | last %}
<h3>{{ newest_page.title }} {{ newest_page.date }}: <a href="{{ newest_page.url | relative_url }}">here</a></h3>
{{ newest_page.summary }}

<br>

## Home Lab
{% assign homelab = site.pages | where: "title", "Homelab" | first %}
{{ homelab.summary }}
My home lab and everything that happens reagrding it can be found [here](/homelab).

## Malware
{% assign malware = site.pages | where: "title", "Malware" | first %}
{{ malware.summary }}
For information about my own and other people's malware please click [this](/malware).

## Projects
{% assign projects = site.pages | where: "title", "Projects" | first %}
{{ projects.summary }}
To see an outline of my projects, please go to [this](/projects) page.

## Hacking
{% assign hacking = site.pages | where: "title", "Hacking" | first %}
{{ hacking.summary }}
To get a view into my hacking, please go to [this](/hacking) page.

<br>

## Updates
<ul>
    <li>07-13-2026: Site Content Upload #1</li>
    <li>07-10-2026: Projects Created</li>
    <li>07-10-2026: Malware Errox_CMD V1 Created</li>
    <li>06-29-2026: Malware Jack_Ketch V1 Created</li>
    <li>06-29-2026: Malware Created</li>
    <li>06-29-2026: Home Lab Services Created</li>
    <li>06-28-2026: Home Lab Created</li>
    <li>06-28-2026: About Created</li>
    <li>06-28-2026: Site Created</li>
</ul>