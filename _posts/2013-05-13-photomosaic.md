---
layout:     post
title:      CUDA Photomosaic Renderer
date:       2013-05-13
---

For [Parallel Computer Architecture & Programming](http://dolores.sp.cs.cmu.edu/15418_spr13/), I implemented a parallel program to generate mosaics from a database of over 100,000 Instagram photos. Photomosaics are photos made up of thousands of subphotos. The biggest challenge was not in finding image matches, but in removing duplicate photos, and stitching the photos together in parallel. The parallel version was implemented in CUDA and achieved a best speedup of 39.1x over the serial C++ version.  

[Final Presentation](https://docs.google.com/presentation/d/1XTquo0vBZemvYEyvsWsdyDRvD0x2KRndcEUinNKREZc/edit?usp=sharing), [View on Github](https://github.com/thedrick/InstagramPhotomosaic)