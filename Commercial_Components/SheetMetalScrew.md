---
title: No.4 Sheet Metal Screw
layout: default
nav_order: 3
parent: Commercial Components
---

# #4 Sheet Metal Screw

Used to hold 3D printed parts together, usually the two halves of the enclosure or other structural connections. The screw most used in MMC devices is a 3/8” #4 Sheet Metal Screw
[Test Link to Other page in the repo](https://bradleywell.github.io/OpenAT-Design-Guide-Test/Cable-Ties.html)

<img width="436" height="303" style="display: block; margin: 0 auto" alt="image" src="https://github.com/user-attachments/assets/9854d526-f88e-4fbe-ae1e-c3b95520f021" />

## Dimensions

For this part, there are several primary dimensions, as well as some design considerations. The primary dimensions are:
* **Clearance Diameter:** This is the diameter of the hole that the screw passes through to get to the threaded hole. The screw threads do not screw into this hole.
* **Threaded Hole Diameter:** This is the diameter of the hole that the threads of the screw dig into. If this hole is too large, the threads will not bite, and if it is too small it requires too much force to tighten and can deform the part.
* **Counterbore Diameter:** This is the minimum diameter of the counterbore to accommodate the head of the screw.
* **Counterbore Depth:** This is the minimum depth of the counterbore to keep the head of the screw from protruding past the surface of the device.
* **Hole Depth:** This is the minimum depth of the section that the screw screws into. This is the length of the screw beneath the head. This includes the thickness of the section that the screw passes through. 
* **Screwdriver Clearance:** For deeper holes, the screwdriver itself must also be able to fit through the counterbore to tighten the screw at the bottom of the hole. This diameter is the minimum diameter to allow a common household screwdriver to be used. If using this diameter, it replaces the counterbore diameter. 

<img width="282" height="351" style="display: block; margin: 0 auto" alt="image" src="https://github.com/user-attachments/assets/bb176449-d061-4e35-8d49-5418c4012f12" />


| **#4 Sheet Metal Screw Dimensions** |        |
| :--------------------- | -----: | 
| Clearance Diameter     | 3.2 mm |
| Threaded Hole Diameter | 2.7 mm |
| Counterbore Diameter   | 6 mm   |
| Counterbore Depth      | 2.6 mm |
| Hole Depth             | 10 mm  |
| Screwdriver Clearance  | 8 mm   |

## Design Considerations

When designing parts that use this component, you need to keep in mind the following design considerations
* **Overhanging holes:** holes in unsupported overhanging material can print poorly and lead to parts not fitting. Refer to the Hydra Research Design Rules [section on overhanging holes](https://www.hydraresearch3d.com/design-rules#unsupported-holes) for how to design an overhanging hole that can print without support
* **Horizontally printed holes:** Holes in the wall of a print can sag when printed, while this isn’t an issue for the threaded part of the hole, this can cause the passthrough hole to not pass through wall. When designing a hole meant to print horizontally, use a circumscribed octagon instead to eliminate the steep overhangs at the top of the circle. 
* **Torque:** When the screw is cutting the threads for the first time, this puts a significant amount of stress on the print. This can happen if the hole is an unsupported cylinder coming out of the part, or if it is a hole in a large solid part with low infill. Additional material should be added to ensure the threaded hole is strong enough to withstand the thread cutting. Refer to the entry on screw posts in the 3D printed parts section for more information.

## Purchasing

 | **#4 Sheet Metal screws can be found at these links:** |        |
| :--------------------- | -----: | 
| Digikey     | [#4 Sheet Metal Screw DigiKey Link](https://www.digikey.ca/en/products/detail/serpac/6005/307599)|
| Mouser | [#4 Sheet Metal Screw Mouser Link](https://www.mouser.ca/ProductDetail/SERPAC/6005?qs=f95KBKa1t%252BoPqs5qKc4pog%3D%3D) |
