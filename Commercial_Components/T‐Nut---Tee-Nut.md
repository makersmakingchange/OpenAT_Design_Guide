---
title: T-Nut/Tee Nut
layout: default
nav_order: 3
parent: Commercial Components
---

# T-Nut/Tee Nut

Tee nuts are off-the-shelf metal components that provide a way to add robust threads to a 3D printed part. Tee nuts are generally designed for use in wood and are intended to be hammered in from the opposite side of where the bolt or machine screw attaches.  
A ¼-20 UNC tee nut is used to add threads to a project, typically for mounting purposes. 

<img width="289" height="351" style="display: block; margin: 0 auto" alt="image" src="https://github.com/user-attachments/assets/52a6d6b4-bd65-43c0-ba05-ffa99b856589" />
<img width="454" height="326" style="display: block; margin: 0 auto" alt="image" src="https://github.com/user-attachments/assets/603366e6-8a8c-4108-9ba7-fddec359b673" />


This is one of the most complicated parts to add to a model, with a long list of dimensions required to make a suitable mounting feature. They can come in 3-, 4-, and 6- toothed versions, so the mounting hole has 12 slots to accommodate any version.

## Example Files

An example of the part dimensioned below is provided as an STL, a STEP, and a F3D file. Currently only the positive is provided, i.e. the part that was dimensioned, but there are plans to add a negative to allow the component to be imported into a design then added as a Boolean subtraction or addition, depending on if you are using the positive or negative.

* <a href="CAD_Files/T_Nut/T_Nut_Mounting_Positive.stl" download>STL File</a>
* <a href="CAD_Files/T_Nut/T_Nut_Mounting_Positive.step" download>STEP File</a>
* <a href="CAD_Files/T_Nut/T_Nut_Mounting_Positive.f3d" download>F3D File</a>

## Dimensions

The following are the list of dimensions used in the T-Nut mounting feature.
* **Counterbore Radius:** The radius of the counterbore that sinks the flat surface of the T-Nut that the teeth and threaded shaft come out of.
* **Counterbore Depth:** The depth of the counterbore that sinks the flat surface of the T-Nut that the teeth and threaded shaft come out of.
* **Thread Radius:** The radius of the hole through the part that the threaded section of the T-Nut goes through.
* **Thread Depth:** The depth of the hole through the part that the threaded section of the T-Nut goes through.
* **Wall Thickness:** The thickness of the outer wall of the T-Nut fixture.
* **Chamfer Length:** The length of chamfer used to start the hole for the threaded shaft.
* **Tooth Spacing:** The distance between the centerline of the fixture and the furthest point of the tooth hole.
* **Tooth Width:** The width of the hole used to capture the teeth of the T-Nut.
* **Tooth Length:** The length of the hole used to capture the teeth of the T-Nut.
* **Tooth Depth:** The depth of the hole used to capture the teeth of the T-Nut.
* **Tooth Angle:** The angle between the teeth sloths on the fixture. This number comes from dividing the number of teeth (12) by the number of degrees in a circle (360).


<img width="936" height="500" style="display: block; margin: 0 auto" alt="image" src="https://github.com/user-attachments/assets/ab27f577-fc84-41c2-9ff9-c904df7f805b" />

<img width="510" height="428" style="display: block; margin: 0 auto" alt="image" src="https://github.com/user-attachments/assets/c09b99c3-7b6e-4354-8721-ca06fe71fd9f" />


| **Part Dimensions**    |        |
| :--------------------- | -----: | 
| Counterbore Radius     | 10 mm  |
| Counterbore Depth      | 1.6 mm  |
| Thread Radius          | 4 mm  |
| Thread Depth           | 8.4 mm  |
| Wall Thickness         | 1.6 mm  |
| Chamfer Length         | 1 mm  |
| Tooth Spacing          | 9.75 mm  |
| Tooth Width            | 0.75 mm  |
| Tooth Length           | 3 mm  |
| Dimension 3            | 4.4 mm  |
| Dimension 3            | 30 degrees |

## Design Considerations

When designing parts that use this component, you need to keep in mind the following design considerations
* **Overhanging Holes:** Holes in unsupported overhanging material can print poorly and lead to parts not fitting. Refer to the Hydra Research Design Rules [section on overhanging holes](https://www.hydraresearch3d.com/design-rules#unsupported-holes) for how to design an overhanging hole that can print without support
* **Horizontally Printed Holes:** Holes in the wall of a print can sag when printed, while this isn’t an issue for the threaded part of the hole, this can cause the passthrough hole to not pass through wall. When designing a hole meant to print horizontally, use a circumscribed octagon instead to eliminate the steep overhangs at the top of the circle. 

## Purchasing

 | **T-Nuts can be found at these links:** |        |
| :--------------------- | -----: | 
| Amazon     | [Part Amazon Link](https://www.amazon.ca/dp/B01MSVU3WF?ref=fed_asin_title&th=1)|