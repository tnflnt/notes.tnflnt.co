---
title: "Responsive Images in Hugo"
date: 2021-04-14T09:04:56-05:00
draft: false
description: "Handy code snippets for generating responsive images in Hugo, from Laura Kalbag."
images: [""]
externalurl: "https://laurakalbag.com/processing-responsive-images-with-hugo/"
tags: [links, hugo]
---

Laura Kalbag’s [how-to for setting up responsive image processing in Hugo](https://laurakalbag.com/processing-responsive-images-with-hugo/) fully rekindled my interest in keeping this site alive.

I know, this is super-niche, but solving the “right-sized image for the device” problem has bothered me since I started (and subsequently neglected) this hobby. Previously, I was doing it the hardest, dumbest way: exporting images at a specific width, optimizing them one at a time, dumping them all in the `/static/img/` directory, trying to follow a date-based naming convention so I’d have some clue which images matched which post.

Like a CHUMP.

Now we’re at galaxy-brain level:

- Using Hugo page bundles to keep images and markdown in the same directory (didn’t know this was a thing).
- Letting Hugo optimize the images and generate all the responsive sizes (didn’t know THIS was a thing, my god, Hugo can do so much stuff and I’m using the *barest of minimums*).
- Using custom shortcodes to build `srcset`’s of images, and all I have to do is plug in one image file name. I kinda, sorta feel like I understand shortcodes now! (loljk I do not)

Man, it’s nice to be excited about this thing again. Next stop: reformatting a bunch of posts. 🙃 