---
layout: pages
title: FAQs
description: List of frequently asked questioned about freeShop.
permalink: /faqs/
---

### Do I need a CFW to use freeShop?
Yes. Luma3DS is recommended.

### Is there a 3DSX version?
No, and there won't be one. The elevated permissions required are complicated to support over multiple FW versions.

### Why are games missing? They're on the eShop.

It only shows games for which you have the title key. And even then some games won't show because they're not cached server-side (this will eventually change).

### Why does freeShop show DLC as installed when I don't have some of it?
All DLC is lumped together with the same title id, so even partial installs will show it as installed. If you're missing DLC, just delete it and reinstall it. If eShop partially installed it, or you previously purchased some DLC through eShop on that console, you may lose the DLC freeShop installs when you revisit eShop. This is currently unavoidable.

### Can freeShop download while sleeping?
Not yet. It's currently unknown how to go into sleep mode without interrupting network services.

### Can I download games of any region?
Depends on your CFW. Most of them allow it, including the recommended Luma3DS.

### Is this safe? Will I get banned/sued for using this?
Even modding your console's software/firmware runs legal risks. But like running freeShop, the risk is minimal. If you make sure to only install games you've purchased, then you remain in a safer legal grey area. And there is no way for Nintendo to know which client IP owns which games. That would requires some analytic guesswork, potentially resulting in many false-positive bans. Not likely to happen and none have been reported.

### I keep getting "Failed to install seed" errors.
You likely have a FW version < 9.6 and therefore cannot play newer games that utilize crypto seeds. You can fix this with a FW update.

### I keep getting "Wrong title key" errors.
You're probably not using correct encrypted keys (encTitleKeys.bin). Decrypted keys will give this error.

### I keep getting "Failed to finalize TMD install: 0xC86044D2".
The system is reporting that you don't have enough space on your SD card to install the game. If it's a DSiWare game, then it's your NAND that doesn't have the space.

### I keep getting "Failed to finalize content install: 0xD8E08025".
There are many possible reasons for this. But one known diagnosis is a possible SD card problem. For example, a fake SD card who is reporting space available while it's actually full will often give this error. Double-check your SD card.

### I get error code 0xD8A08004
This happens with the installation state gets screwed up. You have to reboot the console to get rid of it. If you consistently get this, report how so the bug can be fixed.
