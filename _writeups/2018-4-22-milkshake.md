---
title: Milkshake
---


## Milkshake

#### Location:
[Hack the box](https://www.hackthebox.eu/)

#### Description:
The challenge is to discover the coded message inside an audio file. For steganography beginners.

#### Software Used:
+ Any audio player (WMP, Winamp, VLC, etc.)
+ Audacity

#### Methodology:
After you download the files, examine the audio file with any audio player. You will notice some strange "static" riping our ears on the first seconds of the song. This already gives a lead that something is wrong with the audio spectre.

We should then focus in how to analyze this audio spectre and see what happens at that frequency level. A good opensource tool for this task is Audacity.

So let's open the file with Audacity and see what we can find.

