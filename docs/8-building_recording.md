---
id: building_recording
title: Building recording
---
## Introduction
Conservation architects, architectural historians and urban historians are all in in agreement about the recording of the physical fabric of historic buildings. There is an Icomos document devoted to this issue. This is [Principles for the recording of monuments , groups of buildings and sites](https://www.icomos.org/charters/archives-e.pdf) (Icomos 1996 ). This document states that it is important to provide "a permanent record of all monuments, groups of buildings and sites that are to be destroyed or altered in any way, or where at risk from natural events or human activities".
 
An advisory document for building recording in New Zealand is "Investigation and Recording of Buildings and Standing Structures". It is still available from Heritage New Zealand [here](http://www.heritage.org.nz/~/-/media/bd20738fc99e4f69bec8cec6395b251a.ashx). The document is dated 2006 and has been assigned an isbn number, 978-0-908577-91-0 (online). Authorship is not stated, but an archaeologist employed by the trust, Martin Jones, is thought to be largely responsible.


## Structure from motion
Structure from motion (sfm) is a technique that is a development of photogrammery. Multiple photographs from different viewpoints are taken. These are taken into a digital environment and software is used to automatically calculate the viewpoint from which each photo was taken. The software then matches points from photo to photo, and use this information to calculate the 3d coordinates of each point. The software is then able to make a 3d mesh based on the point cloud and to apply a texture to the mesh.

The resulting model is scale indeterminate. It is then imported into 3d mesh manipulation software such as cloudcompare or even sketchup. Here, the model can be scaled, according to reference (or "control") measurements made on site. 

 The heart of this system is software based. Opendronemap is a very good open source structure from motion solution.

 I have experimented with different camera types, point and shoot cameras, dslr cameras, and phone cameras. Results were usable in most cases. Accuracy is largely dependent on the quality and number of images used. The use of a large sensor dslr camera off a tripod and in ideal overcast light conditions gives the best results.  

Poor results are obtained when there are difficulties getting multiple unobscured shots of the subject building. This is the case when there are other buildings or objects in the foreground, or when obscuring vegetation is present. Buildings that are built of very uniform and slightly reflective material also return poor results as the software has difficulty in fixing points between photographs.

The models below are large files, fast uncapped connection needed.

<div class="sketchfab-embed-wrapper"> <iframe title="Kohekohe Church" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/eee29ce3211d4dcc9fd96e9d529e05c0/embed"> </iframe> </div>
*Kohekohe Church*

<div class="sketchfab-embed-wrapper"> <iframe title="Catalina Barracks" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/677e05f6f3f7438db8977337b4b4a912/embed"> </iframe> </div>
*Catalina Barracks, Whenuapai Air Base, now demolished*

<div class="sketchfab-embed-wrapper"> <iframe title="Demolished deco house Titirangi" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/da96d98130f64efc90b921052256c50f/embed"> </iframe> </div>
*Deco house, Titirangi, now demolished*

## Cyark

The state of the art now, with regard to public presentation of building records is to be found in websites produced by organisations such as Cyark.  CyArk was founded in 2003 in response to the Taliban's destruction of the 1600-year-old Bamiyan Buddhas in Afghanistan.  Cyark's goal is to ensure that heritage sites are available to future generations, while making them  accessible to the public online now.  New technologies are being used to create a free, 3D online library of the world's cultural heritage sites. Particular attention is paid to sites that are likely to be  lost to natural disasters, destroyed by human activity or and lack of activity (maintenance). 
[http://www.cyark.org/about/](http://www.cyark.org/about/ "Cyark is here...")

## Conclusions
Institutions around the world are now moving to a web based presentation of their heritage. Such sites often allow for user manipulation of heritage 3d models, textured, or dense coloured point clouds, together with hotspots and links to historic images and commentary, both textual and audio based.

