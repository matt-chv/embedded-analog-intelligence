---
title: "Guide to Robotic Vision"
date: 2019-12-28
category: [sensor,ros]
lang: en
---
[EMVA guide to machine vision](https://www.emva.org/wp-content/uploads/FSF-VS-Brochure-2018-A4-full.pdf)

## Key take-away:
Camera Interface Standards.................................4
Hardware
 CameraLink.............................................5
 CameraLink HS........................................6
 CoaXPress...............................................7
 GigE Vision..............................................8
 USB3 Vision ............................................9
 Comparison Table..................................10
Software
 IIDC2 ....................................................12
 GenIcam...............................................13
 ```
 SFNC (Standard Feature Naming Convention)
 GenApi (Application Programming Interface)
 GenTL (Transport Layer)
 GenCP (Control Protocol)
 GenDC (Data Container)
 [...]
 Members of the GenICam standard group maintain a reference implementation that parses the file containing
the self-description of the camera. The production quality code is written in C++, and can be used **free of charge**. It
is highly portable and available on a range of operating systems and compilers. 
 ```
 
 Comparison Table..................................14
 
 Camera Performance Standards
EMVA 1288 ................................................15

```
The 1288 standard is based on a linear camera model. All noise sources except for photon noise and quantization noise can
be included into a single parameter, the variance of the dark noise. Thus the model contains only three basic unknowns: the
quantum efficiency, the dark noise and the system gain.
```
Lens Mount Standards.......................................16
Lighting Standards ............................................17
```
LIR-001-2017 Laser Line Metrics for use in Machine Vision and Metrology Applications
```    
     
## Related articles
 
 * [Event based camera]({% post_url 2018-11-16-event-camera.html %})
 * [Quantum dots camera sensors]({% post_url 2020-02-27-qdot_cameras %}) and [THZ imaging]({% post_url 2019-02-26-thz-imaging %})
 
## Questions:
 
 * Architecture overview?
 Brochure gives p 13 a very brief overview
 alternatively:
 ![GenICam architecture](/embedded-analog-intelligence/static/img/VS1212_Slideshow_ImagingStandard1.jpg "GeniCam architecture from qualitymag")
 or from [Genicam Harvester](https://github.com/genicam/harvesters)
 ![GenICam Harvester bindings](/embedded-analog-intelligence/static/img/48105146-a3b0e700-e279-11e8-8a3f-f94372aeff37.png )
 
 * ROS Integration?
 
