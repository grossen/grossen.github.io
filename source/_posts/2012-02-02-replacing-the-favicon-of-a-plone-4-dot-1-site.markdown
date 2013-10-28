---
layout: post
title: "Replacing the favicon of a Plone 4.1 site"
date: 2012-02-02 23:05
comments: true
categories: 
- cms
- plone
---
This is what i did to change the favicon of my Plone 4.1 website.

First login to your Plone site and then go to the ZMI (Site Setup -> Zope
Management Interface). In the ZMI browse to
_<site_root>/portal_skins/plone_images_.

In this folder click on **favicon.ico** and choose customize.

A copy of the favicon will now be placed into the _<site_root>/custom folder_.  
As title choose something like "My favicon" and upload your favicon.ico file.

This should give you the new favicon.

