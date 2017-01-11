---
layout: pages
title: Get Started
description: Guide to get started with installing and using freeShop.
permalink: /get-started/
---


## Installation

1. First, make sure your 3DS can install and launch homebrew software. If you have a stock system and cannot, follow the guide: [https://3ds.guide/](https://3ds.guide/)
2. The following 3DS software is recommended for freeShop usage and setup:
    - [Luma3DS](https://github.com/AuroraWright/Luma3DS/releases)
    - [FBI](https://github.com/Steveice10/FBI/releases) for an installer
    - [ftpd](https://github.com/mtheall/ftpd/releases) for transfering files to the SD card
    - [Decrypt9](https://github.com/d0k3/Decrypt9WIP/releases) for dumping and encrypting title keys.
3. Download and install freeShop using one of the following methods:
    - QR Code (recommended)
        - Using FBI, navigate to **Remote Install > Scan QR Code** and then scan this [QR. <span class="glyphicon glyphicon-qrcode" aria-hidden="true"></span>](/img/qr.png){: data-featherlight=""}
    - Manual Download
        - Download the [latest CIA file](https://get.freeshop.pw/latest), transfer it to the SD card, and install it using FBI or any other CIA installer.

<div class="alert alert-danger" role="alert">
<b>Warning:</b> do not use any DNS or router configurations that block Nintendo's servers. They may interfere with freeShop's ability to access the necessary servers.
</div>

## Initial Setup

1. Launching freeShop for first time will create all necessary files and directories on the SD card. It will inform you that no [keys are found. <span class="glyphicon glyphicon-picture" aria-hidden="true"></span>](/img/screenshots/1.png){: data-featherlight=""}
2. You need a title key file (commonly named **encTitleKeys.bin**). You can dump the keys of installed tickets on a 3DS console using the following steps:
    1. Boot up Decrypt9.
    2. Go to "Ticket/Titlekey Options"
    3. Go to "Titlekey Dump" (either SysNAND or EmuNAND, whichever you use)
    4. Choose a filename. The saved file should be in the **sd:/files9/** directory.
3. You can use your title key file(s) in two different ways:
    - Place the key file(s) in the **sd:/3ds/data/freeShop/keys/** directory.
    - Download your file(s) from URL, synchronizing with cloud backups:
        - Add the URL in the freeShop settings in the "Update" tab.
        - [This is a video demonstration. <span class="glyphicon glyphicon-facetime-video" aria-hidden="true"></span>](https://youtu.be/FV7vDPBYupA?t=1m30s)
        - You must restart freeShop in order for it to download the key file.
