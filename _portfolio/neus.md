---
title: "Surface Reconstruction from Multi-View Images"
excerpt: "Deep Learning, NeuS, NeRF<br/><a href='neus' class='portfolio-link'><img src='/images/Hog_Vid3.gif' width='600'></a>"
collection: portfolio
order: 8
---


<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->

For my final project in the course CSCE 5563 Intro to Deep Learning, a literature review and implementation of the Neural Surface (NeuS) reconstruction technique was done. This approach is capable of producing higher quality surface reconstructions than the popular Neural Radiance Field (NeRF) approach. For the implementation, several 2D images of a toy razorback were taken and used to train the model to learn the neural implicit surface representation. With the trained model, a high quality surface could be extracted and then used to interpolate between images for novel view synthesis.