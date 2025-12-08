---
title: 3D Printing Design Tips
layout: default
nav_order: 2
parent: Home
---

In this section, we have compiled other existing design guides, and provided information on the printers used in determining the tolerances used in this guide, as well as looser tolerances that can be used on older printers.

# Hydra Research Design Rules

Hydra Research has compiled a list of general-purpose design rules for use while 3D printing. These rules are more general than the ones in the Design Elements section of this report, and covers topics such as wall thickness, bridging, overhangs, and filets. 

A section that is particularly worth reading is the section on unsupported holes, found [here](https://www.hydraresearch3d.com/design-rules#unsupported-holes). This section covers how to design a hole in an overhanging part. Adding an unsupported circular hole in an overhang typically leads to a poor-quality printed hole, but the design features in this section allow for the holes to be printed without supports and without a drop in print quality.
The full design rules can be found [here](https://www.hydraresearch3d.com/design-rules).

# Rahix Design for 3D-Printing

Rahix has put together a blog post going into detail about design rules for 3D printing. The post covers part orientation, infill and strength, optimizing for print time and material usage, and much more.
The full blog post can be found [here](https://blog.rahix.de/design-for-3d-printing/)

# 3D Printers and Clearances

The printers used in the design of the devices linked in this guide were the Bambu P1S and the Prusa MK4. At the time that this guide was written, these were some of the better 3D printers on the market, capable of repeatedly printing accurate parts. 
The standard clearance between parts used in MMC devices is 0.1 mm. This clearance allows parts to fit together easily, without binding or being too loose. For some older printers however, this may be too tight of a fit to reliably assemble well. If that is the case, increasing the clearance between parts to 0.2 or even 0.3 mm may allow the parts to assemble easier. 
