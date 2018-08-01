---
author: loneoceans
comments: true
date: 2013-02-24 06:24:24+00:00
layout: post

slug: a-table-top-drsstc-tesla-coil
title: A Table Top DRSSTC Tesla Coil
wordpress_id: 1351
categories:
- Electrical
- Projects
tags:
- coil
- drsstc
- gao
- ggy
- guangyan
- half bridge
- igbt
- loneoceans
- miters
- musical
- table
- tesla
- top
---

Hi everyone,

Introducing my *first DRSSTC.* It's a small tesla coil made to be portable and to make lightning at home. This coil is based of the amazing oneTesla pcb. I'm still in the process of doing a detailed write up at [http://www.loneoceans.com/labs/drsstc1/](http://www.loneoceans.com/labs/drsstc1/)!

![](http://miters.mit.edu/wp-content/uploads/2013/02/8502807104_68a141fd5e_c2.jpg)

As a learning experience, I wanted to go for something simple and nothing too fancy. I've had the fortune of being in the good company of other brilliant coilers (like Bayley, Tyler, Kramnik), and managed to get an older version of the oneTesla driver PCB, which runs this coil! I faced a couple of problems over the past few weeks but I've modified some parts and managed to get the coil working very well! **See the video of it in action here:**


**Important specifications** including calcs from JavaTC:



	
  * Max spark length - I don't know yet, does >22" sparks to free air and ground with ~100us on-time. More testing to come soon. Right now it's limited by hitting the floor.

	
  * **222kHz** resonant frequency (within 1%)

	
  * 2.4" Diameter PVC Secondary, ~2000 turns of AWG36 for a 10.25" length

	
  * 3.5" Diameter Acrylic Primary, 6 turns of AWG 14 for about 0.8" length

	
  * Single 0.101uF 2kVDC 942C CDE Primary Capacitor

	
  * 340VDC (120VAC rectified and doubled)

	
  * Roughly 100us on-time (in the photos here)

	
  * 2.2" x 8" AmazingOne spun toroid

	
  * Half Bridge of **60N65** IGBTs (seems to be similar to the 60N60 TO247 IGBTs)

	
  * Coupling = 0.22

	
  * Energy Transfer time = 9.87us


Performance has been pretty good. Originally, the coil used a 0.068uF 940C capacitor but that made my primary frequency about 19% too high and I lost a 60N60 half bridge. Increasing the primary to 8 turns of 14AWG (k=0.26) turned out to be a bad idea and I had a lot of racing sparks. After a few more coats of Polyurethane on the secondary, a return to 6 turns of AWG14 and a larger tank cap, the coil is in tune with a performance I'm very happy with.

This coil currently has a tiny built-in 19VDC laptop power supply for the electronics which uses the famed UCCs from TI as gate drivers to a GDT driving the gates of the IGBTs. Here's a pretty photo of the ground 'lighting' strikes of the tesla coil:

![](http://miters.mit.edu/wp-content/uploads/2013/02/8501702233_d0846991c7_c2.jpg)

Best Wishes!

 -  Guangyan
