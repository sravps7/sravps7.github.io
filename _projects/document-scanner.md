---
layout: project
title: Document Scanner
description: Reconstruction of a document by stiching overlapping images 
category: project
permalink: /projects/document_scanner.html
---

This project was done as a course project of the Digital Image Processing course in a team of three.
We implemented a [paper](https://stacks.stanford.edu/file/druid:bf950qp8995/Badlani_Akinola_Li.pdf) of Stanford university.

We successfully reconstructed a document by taking multiple overlapping images of it. This procedure is used when the size of the document to be scanned is very large to fit in one image without comprmising on the resolution.


 ![Original]({{ site.url }}/public/images/document_scanner/original.jpg)

 ![Reconstructed]({{ site.url }}/public/images/document_scanner/reconstructed.png)




The images were aligned after calculating a homography matrix for each image and were then stiched together using a slightly modified standard stiching technique. Post-processing steps included Gain compensation (to equalise the intensities of all the constituent images) and multi-band blending (to remove the prominent edges left over even after Gain compensation).

Feel free to go through the code and the report of the project [here](https://github.com/udiboy1209/cs663-document-scanner). 
