---
title: "New website"
date: 2021-07-30
# weight: 1
# aliases: ["/first"]
tags: ["first post", "website", "hugo", "papermod", "github", "wordpress", "markdown", "ghosts 'n goblins"]
author: "PilzHere"
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: true
description: "*Level up!*"
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
image: "/images/cover.png"
alt: "<alt text>" # alt text
caption: "<text>" # display caption under cover
relative: false # when using page bundles set this to true
hidden: true # only hide on current single page

editPost:
external_URL: "https://github.com/<path_to_repo>/content"
Text: "Suggest Changes" # edit text
appendFilePath: true # to append file path to Edit link
---

This is my first post on my new site!\
**What am I going to do with this site?**\
\
Well, I'm going to post about things and ideas that are swirling around or is stuck in my brain that needs to be ventilated digitally.\
\
I might post an image:
![Example image](/images/cover.png)
*Ghosts 'n Goblins*. Do you hate or love this game?\
Or maybe *it's complicated*...\
\
I might post some code:
```java
Console.WriteLine("Look 'ma! A string!");
```
\
{{< rawhtml >}}
<p class="speshal-fancy-custom">
I might post some <strong>raw HTML</strong>, inside Markdown. Impressive!
</p>
{{< /rawhtml >}}
\
As you can see, I'm currently getting used to **Markdown** as I'm coming from the HTML side of the world.
The more I use it, the more I appreciate it.\
\
I used to host my website using Wordpress. I found it a hassle and boring to update the content, so I didn't. I needed a simpler system that was less annoying to use and something I can edit in my favorite IDE/terminal and publish whenever I wish to do so.\
\
The new site is based on [Hugo](https://gohugo.io/) with the theme [PaperMod](https://adityatelange.github.io/hugo-PaperMod/). I like it out of the box, so there won't be a lot of adjustments for it.\
The site is stored in a [Github Pages repository](https://github.com/PilzHere/pilzhere.github.io) which is linked as a submodule inside the [construction-site repo](https://github.com/PilzHere/MyWebsite), which can be run and exported by [Hugo](https://github.com/gohugoio/hugo) using [the theme](https://github.com/adityatelange/hugo-PaperMod).

Hugo | Website construction repo | Github pages repo
------------ | ------------- | -------------
Run Hugo server | Stores Hugo web project | <br>
<br> | *Implement and debug code* | <br>
Build website data --> | Github pages submodule --> | Stores website data

\
This way, I can edit the website in the construction-site and push/update the website repository (github pages), and Github will automatically update the site at [pilzhere.github.io](https://pilzhere.github.io/).\
\
If you can read this it means it worked!
