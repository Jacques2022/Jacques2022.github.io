---
layout:     post
title:      "Mechanism Design for Variational Bottom"
subtitle:   " Notes for the construction for waterproof variational bottom."
date:       2024-05-21 12:45:00
author:     "H. Shen"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - Log
    - Water Wave
---

<!-- > “Hello world!” This is 引文. -->
In this article, we go through the procedures necessary to construct/build waterproof mechanical structure for the realization of bottom with variational depth.

# Basic Ideas

<p id = "tag1"></p>

The effect should look like [this](https://www.bilibili.com/video/BV1W14y1b7Mq).
<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=771908203&bvid=BV1W14y1b7Mq&cid=801456559&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>

The only problem is that the above design is not waterproof.

<!-- [This is how to use interior hyper-ref.](#build)
<p id = "build"></p> -->

# How to Achieve Waterproof?

## Identify the Problem
The [design](#tag1) shown previously places the motors below the bottom. Then, water leakage is inevitable when it is placed underwater. And the coils in motors will be damaged for sure.


## An Easy Solution
This is too easy to be perfect. **Do note that this method is merely a rough fix, not an elegant design!**


We can use the mechanism of worm drive to transfer direction of torque. Consider 45$^\circ$ worm gears, and the animation for the torque transferring mechanism is shown [below](#fig01).
![Torque Transferring in Right Angle](/img/in-post/2024-05-21-variational-bottom-design/fig01.gif)

<p id = "fig01"></p>


For each unit block, we can apply this mechanism two times to move the motors from below the block to its adjacent higher than the water surface. However, it shall take large amount of space. Don't worry about the overlapping problem when it comes to multiple rows and columns of the unit blocks. The rows do not interfere with each other naturally, and we can assemble the worms layer by layer to deal with different columns. $\textcolor{red}{\text{Need to design in Solidworks later.}}$

## Design the Parts in SolidWorks
### Design the Worm Gears
See [YouTube](https://www.youtube.com/watch?v=zjSCypsKnTE)
<iframe width="560" height="315" src="https://www.youtube.com/embed/zjSCypsKnTE?si=RAWU2ECLqKf4jY6j" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Some other worm [designs](http://www.360doc.com/content/20/0210/06/276037_890855650.shtml).
