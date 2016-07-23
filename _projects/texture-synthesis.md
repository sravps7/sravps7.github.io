---
layout: project
title: Texture Synthesis
description: Used a given finite sample of a texture to extend it to a larger size
category: project
permalink: /projects/texture-extend.html
---

This project was an image processing application. It involved using a sample finite image of a texture to fill holes or extend the existing image.

Here, I assumed that the image had some regularity in it. Also, the algorithm mentioned ahead will be very dependant on the fact that the sample is large enough to have the properties of the texture.

So here is the algorithm. The new image is constructed pixel-by-pixel from the sample image. For each new pixel to be constructed, a neighbourhood of that pixel in the image to be constructed is extracted in the form of a patch. This extracted neighbourhood is then compared with all possible patches in the original image. The most similar patch is then saved and its central pixel is assigned as the new pixel's value.

This procedure is repeated for each and every pixel until the image synthesized is of the required size.

[Here]( https://github.com/sravps7/extend_image ) is the code for the project. It is pretty much self-explanatory. Feel free to contact me if needed.