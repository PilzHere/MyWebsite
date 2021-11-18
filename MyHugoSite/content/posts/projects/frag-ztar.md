---
title: "Frag Ztar"
date: 2021-11-18
weight: 1
# aliases: ["/frag-ztar"]
author: "PilzHere"
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Star Fox (SNES) inspired rail shooter."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true

cover:
    image: "https://img.itch.zone/aW1hZ2UvMTI4MTE5Ni83NDY4OTg2LnBuZw==/250x600/BhcN%2FV.png"
    alt: "gng"
    caption: ""
    relative: false # when using page bundles set this to true hidden: false # only hide on current single page
    
editPost:
    URL: "mailto:pilzhere.net@gmail.com?subject=Suggesting changes for "
    # Text: "Suggest changes"
    # appendFilePath: true # to append file path to Edit link

---

## I have enjoyed another game jam!

This time it was the swedish videogame news site [Frag Zone](https://fz.se) that set up *FZ Game Jam 2021*. The time is
right because it's cold and dark outside these months. So a lot of my spare time is at the computer.

The jam time was set to a month, ending at 16th of November. I joined the jam 1 week late when randomly visiting the
site. There was money to win, so why not!?

I've wanted to try out MonoGame for a long time and thought this could be the right time. I don't feel there's a big
difference in C# and Java anyway.

I've also thinking about trying to make a *rail shooter* for a while too. As most of my games, I try to recreate another
game I already know about and then add or change things as I see fit. This time that game was **Star Fox** for the *
SNES* in holy 256*224 resolution.

I didn't use MonoGame the "Game component way". I usually stick to entities and try to use interface's only when needed.
It feels like I have more control of the workflow and game that way, especially update/render order...

Anyway the game turned out ALMOST as I wanted it. Working with MonoGame, making calculations using Vectors and Matrices
is easier than in LibGDX. One thing I was disappointed with was that MonoGame does not have an implemented way of
reading animations from a 3D model.

### What I used for this project:

<ul>
<li>C# with MonoGame game framework and of course Rider as IDE.</li>
<li>Blender for low poly 3D models.</li>
<li>Aseprite for pixel textures.</li>
<li>Git for version control.</li>
</ul>

### Few mistakes and things I didn't have time to implement:

<ul>
<li>MonoGame does not export to WebGL. Why is this not a thing?</li>
<li>I didn't use shaders for the model as "your supposed to" but it works and can always be updated in a more efficient way later by anyone.</li>
<li>No end boss. =(</li>
<li>More enemies.</li>
<li>Velocity based movement.</li>
</ul>

The final result of the game's votes will be 1st of December. It would be nice to win!

<br />
------------ | -------------
![](https://img.itch.zone/aW1hZ2UvMTI4MTE5Ni83NDU3MzY4LnBuZw==/347x500/mx5Lvp.png) | ![](https://img.itch.zone/aW1hZ2UvMTI4MTE5Ni83NDU3MzY5LnBuZw==/347x500/K0AqIw.png)
![](https://img.itch.zone/aW1hZ2UvMTI4MTE5Ni83NDU3MzY3LnBuZw==/347x500/5NPnzy.png) | ![](https://img.itch.zone/aW1hZ2UvMTI4MTE5Ni83NDU3MzY1LnBuZw==/347x500/mPRR4U.png)
![](https://img.itch.zone/aW1hZ2UvMTI4MTE5Ni83NDY4OTg2LnBuZw==/347x500/%2F5pvfK.png)

### [Download game from Itch](https://pilzhere.itch.io/frag-ztar)

### [Download sourcecode from Github](https://github.com/PilzHere/FZtar)

Development GIF's {{< rawhtml >}}
    <div style='position:relative; padding-bottom:calc(87.35% + 44px)'><iframe src='https://gfycat.com/ifr/FrailVioletGroundhog' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>
    <br />
{{< /rawhtml >}}
