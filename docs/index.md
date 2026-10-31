---
title: Welcome
tags:
- tag1
- tag2
---
<center>
<font size= "6">Zander Datasheet</font><br>
as part of<br>
<font size= "8"> Setting up Git, Github & Datasheet</font><br>
for<br>
<font size= "5"> Team 202 </font><br>

**Submission: September, 09, 2026**
</center>

## Introduction

* This datasheet documents my LCD display subsystem for Team 202’s Weather Gadget. It includes the block diagram, component selection, bill of materials, schematic, and power budget to support construction, testing, and integration with the team’s sensor boards.

### Project Summary

* [Team 202's.](https://asu-egr304-2026-f-202.github.io/ASU-EGR304-2026-F-202/) Weather Gadget is an embedded system designed to collect environmental measurements and present them through a simple user interface. Separate sensor boards measure air pressure, light, and humidity, while the LCD display board provides a central location for viewing their readings.

* My subsystem uses a PIC18F57Q43 Curiosity Nano to communicate with the three sensor boards through UART connections and control a character LCD. The intended interface displays one sensor reading at a time, with each button press selecting the next reading. This design connects the team’s individual sensing subsystems into a device that allows users to access the collected information.
* Add context that ties into the link to your 


### My Contribution

* I am responsible for designing the LCD display board and its interfaces with the team’s sensor boards. My work includes selecting components, developing the KiCad schematic, defining the UART and LCD connections, and documenting the power requirements and bill of materials. The board design includes voltage regulation, LCD contrast adjustment, backlight circuitry, a pushbutton input, and connections for testing.

* The [Block Diagram](https://aboward-cloud.github.io/01-Block-Diagram/Block-Diagram/) explains the subsystem’s organization, while [Component Selection](https://aboward-cloud.github.io/02-Component-Selection/Component-Selection/) describes the hardware choices. The [Schematic](https://aboward-cloud.github.io/04-Schematic/schematic/), and [Power Budget](https://aboward-cloud.github.io/05-Power-Budget/Power-Budget/) provide the supporting design details.
