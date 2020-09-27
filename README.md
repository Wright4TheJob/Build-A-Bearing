# 3D Printable Ball Bearings

## The Problem
Many people have demonstrated 3D printing complete ball bearings using soluble support material or excellent material calibration. These bearings require clearance between the balls and the races to print separately and have low strength. In short, they are excellent demonstration pieces but do not function well as bearings.

## A Solution
3D printing races which can be filled with mass-manufactured balls creates relatively smooth-running bearings without requiring expensive materials or tooling, other than a 3D printer. In addition, these bearings can be made at larger sizes where industrial bearings are prohibitively expensive.

# The Project
This project holds fully parametric design files for a variety of types of 3D-print-ready bearings. These files can be modified to the size and shape you need and tuned to match your printer's capabilities. The bearings are modeled in @FreeCAD ([Official Website](https://www.freecadweb.org/)) and are licensed for you to use as you please on your next project.

# How to use this project
If you want to dive right in and try printing a bearing, this is a simple and small one to start with. It uses 6mm Airsoft BBs commonly available in sporting stores and does not add any compensation for additional clearance or pre-compression on the balls.

If you would rather test your printer's settings first, download the Clearance Test and tune the settings to match your printer's calibration.

A walkthrough of the settings for each bearing is available along with the design files. This includes overall dimensions of the bearing as well as clearances for your printers needs.

There are pre-exported files ready for slicing in common sizes for each type of bearing if you would rather use the pre-generated files.

For quieter bearing operation, some lubrication may be helpful. Petroleum jelly has worked well for me at low speeds.

# How to contribute to this project
Implement more bearing designs! There are many cool bearings out there for specialized uses. Model them and submit a pull request, and we can add them to a growing library.

# How to choose the right bearing for your project
1. Have reasonable expectations. These bearings are still mostly (or completely) plastic, so will not survive very high speeds or intense loads as well as industrial bearings. Bearing test data and recommended loading would be great to add to this one day.
2. You probably need a ball bearing. For most common applications, this is a good choice. Skateboard wheels, fidget spinners, or the scroll wheel on a high quality mouse all probably use ball bearings. However, if you want to get the most out of your design, using a more specialty bearing may help.
3. Is the bearing rotating constantly or doing positioning? The high load ball bearing distributes the contact between the ball and race along a curved surface which gives higher stiffness and load capacity at the expense of higher friction. If you have a robot arm that is moving back and forth or a rotating display table, this may be a good choice for you. If the bearing is rotating constantly or at higher speeds, the standard ball bearing is probably best.
4. Is the majority of the force the bearing is transmitting along the shaft going through the bearing (axial) or across the races of the bearing (radial)? If most or all of the load is transmitted axially, consider a thrust bearing. Rather than splitting the bearing into an outer and inner race, the thrust bearing splits like a sandwich, with a top and bottom race and balls between. Machines with high forces along the rotating shaft, like the leadscrew on the motion axis of a mill, often use thrust bearings to resist that force. Ball bearings can resist some axial load, but wear out more quickly.
5. Does your design have parts to place the bearings in (bearing housings) or do you need to attach the bearing another way? The flanged ball bearing can be bolted to the face of a part without needing a larger recess. In some cases, this can save space or make it easier to disassemble and service the machine.

# To Do
- [ ] Add links to AMF files for starter bearing
- [ ] Design tolerance test
- [ ] Design thrust bearing
- [ ] Add walkthrough with screenshots for design files

# Acknowledgments
Many thanks to [Jeff Kerr](https://www.thingiverse.com/lobocnc/designs) for his design of a [robot actuator with integrated ball bearing](https://www.thingiverse.com/thing:3293562) for the inspiration for this design.
