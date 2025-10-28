---
title: Shadow Lines
layout: default
nav_order: 3
parent: Design Elements for 3D Printed Parts
---

# Shadow Line

When creating an enclosure, a shadow line should be added to help align the halves of the enclosure, hide any visual gaps or inconsistencies with the prints, and make the enclosure look more like a commercial injection molded version.

image placeholder

There are a variety of ways to make a shadow line, but they all have an overlap between the two halves of the enclosure instead of just butting them together, which can lead to gaps and a poor seal between the halves. When making an enclosure with 1.6 mm thick walls, it can be difficult to remove material from one side to accommodate the shadow line, so the shadow line is generally built behind it in this situation.

To do so, create a sketch on the top surface of the bottom enclosure. Offset the inner edge of the top surface by 0.2 mm and 1.8 mm. Extrude both areas down by 1.6 mm to join them to the bottom enclosure, then extrude just the area between the 1.8 mm and the 0.2 mm up by 1.6 mm. Chamfer the bottom edge by 1.8 mm for printability. Finally, chamfer the outside edge of both the top and bottom enclosure by 0.4 mm to prevent any misalignment from creating a visible overhang.

image placeholder