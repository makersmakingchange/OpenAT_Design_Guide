---
title: Screw Posts
layout: default
nav_order: 3
parent: Design Elements for 3D Printed Parts
---

# Screw Posts

When working with screws in 3D prints, care must be taken when designing the hole that the screw screws into. A poorly designed hole can break under the force and ruin the print.

image placeholder

Most screw holes in MMC designs are screw posts, where a cylinder comes out from the enclosure for the screw to screw into. An unreinforced screw post can snap at the base under the force of screwing in the screw, leaving the post spinning freely and making removal of the screw difficult. This happens due to the stress concentration and lack of reinforcement at the base of the post and can be fixed by added reinforcing ribs and a fillet to the post.  

Ribs can be easily added to the sketch used to create the post, using two center rectangles. The length of the rectangles should be between two to three times the diameter of the post, and the width is generally 1.6 mm, the width of four walls on a 0.4 mm 3D printer nozzle. When extruding the post, simply also select the sections of the rectangles that extend past the post walls. After extruding, a two-distance chamfer can be used to chamfer the ribs.

image placeholder

After creating the ribs, a fillet can be used along the base of the post and ribs to reduce the stress concentration further, usually a 0.8-1.6 mm fillet.
