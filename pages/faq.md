---
layout: page
header:
  image_fullwidth: banner5.jpg
title: "FAQ"
teaser: ""
permalink: /faq
---
## What are the minimum hardware requirements?
The main hardware requirement is the CPU because the decoding needs a lot of CPU power.

**Recommened**
* CPU: 4 cores x86 CPU with 2 GHz (Intel i-series)
* Display: High resolution with touchscreen

**Minimum**
* CPU
 * 4 core x86 CPU with 1.3 GHz (Intel Atom Z8300 or Intel Atom Z3736F)
 * 4 core ARM Cortex-A7 CPU with 900 MHz (Raspberry Pi 2)
* Display: 800 x 480 pixels

Please report if you are able to run welle.io on other hardware platforms.

## Where are the settings stored?
**Windows**  
The settings are stored inside the Windows registry at the key `HKEY_CURRENT_USER\SOFTWARE\welle.io\welle.io`

**Linux**  
The settings are stored inside you local settings folder `~/.config/welle.io/welle.io.conf`

## How can I delete the settings?
**Windows**
* Run regedit.exe
* Delete the key `HKEY_CURRENT_USER\SOFTWARE\welle.io`

**Linux**
* Delete the file `~/.config/welle.io/welle.io.conf`
