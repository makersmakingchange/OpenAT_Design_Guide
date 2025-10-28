---
title: Cable Ties
layout: default
nav_order: 3
parent: Commercial Components
---

# Cable Ties

Cable ties are typically used for strain relief on cables entering an enclosure or to otherwise attach cables and wires to a 3D print.

<img src="Photos/Cable_Tie/Cable_Tie_Bundle.png" width="300" style="display: block; margin: 0 auto" alt="A bundle of cable ties. ">

The cable ties used in most MMC projects require at least 3 mm of width, and 1 mm of thickness. When the cable tie runs along the exterior of the device, like the ones found at the bottom of the [Open Rocker Switch](https://github.com/makersmakingchange/Open-Rocker-Switch), be aware that it will not bend a perfect 90 degrees and will either need a radiused bend or a slightly deeper channel to allow it to lie flush with the exterior of the device. If it is in the interior bottom of the device, a fillet along the bottom makes it easier to insert the cable without it getting stuck, as seen in the [Spruce joystick](https://github.com/makersmakingchange/Spruce-Mini-Joystick)

## Dimensions

The primary dimensions and considerations of the part. 
* **Minimum Width:** The minimum width of the rectangle required for the cable tie to pass through. If using a circular passthrough, this is also the diameter of the circle.
* **Minimum Height:** The minimum height of the rectangle required for the cable tie to pass through.

<img src="Photos/Cable_Tie/Cable_Tie_Sketch.png" width="600" style="display: block; margin: 0 auto" alt="A bundle of cable ties. ">

| **Cable Tie Dimensions**   |        |
| :--------------------- | -----: | 
| Minimum Width            | 3 mm  |
| Minimum Thickness        | 1 mm  |

## Design Considerations

When designing parts that use this component, you need to keep in mind the following design considerations
* **Overhanging Holes:** Holes in unsupported overhanging material can print poorly and lead to parts not fitting. Refer to the Hydra Research Design Rules [section on overhanging holes](https://www.hydraresearch3d.com/design-rules#unsupported-holes) for how to design an overhanging hole that can print without support
* **Horizontally Printed Holes:** Holes in the wall of a print can sag when printed, while this isn’t an issue for the threaded part of the hole, this can cause the passthrough hole to not pass through wall. When designing a hole meant to print horizontally, use a circumscribed octagon instead to eliminate the steep overhangs at the top of the circle. 
* **Layer Line Orientation:** When the cable tie is used to provide strain relief for a cable, consider the fact that it may be subject to a significant force. Make sure to orient the section that the cable tie is connected to in a way that the layer lines strengthen the section, not weaken it.

## Purchasing

 | **Cable Ties can be found at these links:** |        |
| :--------------------- | -----: | 
| Digikey     | [Cable Tie DigiKey Link](https://www.digikey.ca/en/products/detail/3m/CT4NT18-M/2721151)|
| Mouser | [Cable Tie Mouser Link](https://www.mouser.ca/ProductDetail/3M-Electronic-Specialty/CT4NT18-M?qs=ZWbLE8ZZ2FMuC6MNf0Q4Kw%3D%3D) |