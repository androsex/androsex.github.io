---
layout: post
title: "androsex - part I"
date: 2015-10-27 15:33:15 +0100
comments: true
categories: 
---
## Android system cooking

# persistent changes to system image
il formato delle immagini di sistema (system.img) può essere o yaffs2 o ext4 (il primo sarà sostituito dal secondo).

#emulator
L'immagine utilizzata dall' AVD è presa dalla directory del SDK, si possono seguire due strade:

* pack/unpack locale sull'host
* pack/unpack sul device

Una volta creata l'immagine custom, usare il flag -system con il comando emulator
Sull'emulatore installare nella partizione di sistema le GApps, Supersu e Xposed.

#device


Risorse utili:

http://forum.xda-developers.com/showthread.php?t=2095854
http://muzso.hu/2012/08/10/how-to-pack-and-unpack-system.img-and-userdata.img-from-an-android-factory-image
http://newandroidbook.com/tools/imgtool.html
http://forum.xda-developers.com/showthread.php?t=2528952
http://rex-shen.net/android-unpackpack-factory-images/
http://blog.vishalon.net/index.php/tutorial-how-to-make-a-change-permanent-in-system-folder-for-android-emulator-yaffs2ext4/
