# Assembly Process
## Overview

This document outlines the step-by-step physical assembly of the system, including component installation and basic validation checks. The process mirrors standard hardware deployment and build procedures used in enterprise and data center environments.

### 1. Workspace Preparation

Description:
Prepared a clean, static-safe workspace prior to assembly.

Actions Taken:

Used a large, flat surface for component layout

Ensured adequate lighting

Grounded myself to reduce static discharge risk

Verified all components against the inventory list

Validation:

No visible damage to components

All required parts accounted for before assembly

<img src="https://i.imgur.com/tR2rGhr.jpeg" height="80%" width="80%" alt="Hardware Conents Laid Out"/>

<br>The motherboard was placed on top of its packaging box to provide a non-conductive, static-safe working surface during installation.</br>
<img src="https://i.imgur.com/z1YLSpC.jpeg" height="80%" width="80%" alt="Motherboard"/>

### 2. CPU Installation
Note: A photo of the CPU installed in the socket was not captured during assembly. Installation was verified during POST, with the system successfully detecting the AMD Ryzen 5 5500 in BIOS.

Description:
Installed the CPU into the motherboard socket following proper orientation and locking procedures.

Actions Taken:

Opened CPU socket retention arm

Aligned CPU using corner marker

Seated CPU without applying force

Locked retention arm

Validation:

CPU seated flush in socket

No bent pins observed

Retention arm locked securely

<img src="https://i.imgur.com/WhuCGau.jpeg" height="80%" width="80%" alt="CPU"/>

### 3. CPU Cooler Installation

Description:
Installed stock CPU cooler to ensure adequate thermal management.

Actions Taken:

Verified thermal paste was pre-applied

Mounted cooler according to AMD specifications

Secured cooler evenly

Connected CPU fan to motherboard CPU_FAN header

Validation:

Cooler firmly mounted with no movement

Fan cable properly connected

No obstruction to surrounding components

<img src="https://i.imgur.com/SB25e3x.jpeg" height="80%" width="80%" alt="CPU Cooler Installed"/>

### 4. Memory (RAM) Installation
<img src="https://i.imgur.com/7KBggLz.jpeg" height="80%" width="80%" alt="RAM"/>
Description:
Installed dual-channel memory modules to optimize performance.

Actions Taken:

Identified correct DIMM slots per motherboard manual

Opened retention clips

Installed RAM modules until clips locked

Validation:

Retention clips fully engaged

RAM seated evenly in slots

Correct dual-channel configuration used

<img src="https://i.imgur.com/T5CH75R.jpeg" height="80%" width="80%" alt="RAM Installed"/>

### 5. Storage (SSD) Installation

Description:
Installed the solid-state drive (SSD) into the motherboard’s M.2 slot and secured it according to manufacturer specifications.

Actions Taken:

Removed the M.2 slot retaining screw

Inserted the SSD at a slight angle into the M.2 slot

Gently pressed the SSD down to align with the standoff

Secured the SSD using the retaining screw

Validation:

Confirmed SSD was firmly seated and properly secured

No visible movement after installation

SSD was later detected in BIOS during system power-on verification



### 6. Graphics Card (GPU) Installation

Description:
Installed discrete graphics card into primary PCIe slot.

Actions Taken:

Removed appropriate expansion slot covers

Inserted GPU into PCIe x16 slot

Secured GPU to case

Connected PCIe power cables

Validation:

GPU fully seated in slot

PCIe retention clip engaged

Power cables firmly connected

📸 (Image: GPU installed)

### 7. Power Supply Installation

Description:
Installed the power supply unit and routed primary power connections.

Actions Taken:

Mounted PSU in case with fan oriented correctly

Secured PSU with mounting screws

Connected 24-pin motherboard power cable

Connected 8-pin CPU power cable

Validation:

PSU firmly mounted

Power cables seated fully

No cable strain on connectors

📸 (Image: PSU installed)

### 8. Pre-Installation Hardware Validation (Bench Test)

Description:
Performed a pre-installation hardware validation (“bench test”) by assembling core components outside the case to verify functionality prior to final installation.

Rationale:

Reduce risk of full teardown if components were defective

Confirm core components functioned before cable management and mounting

Common best practice for first-time system builds and troubleshooting

Actions Taken:

Placed motherboard on a non-conductive surface

Installed CPU, RAM, SSD, and CPU cooler

Connected power supply (24-pin ATX and CPU power)

Performed initial power-on test

Validation:

System powered on successfully

Fans spun and system showed signs of POST

Proceeded with full case installation after validation

### 9. Motherboard Installation

Description:
Installed the motherboard into the case using manufacturer-recommended mounting points.

Actions Taken:

Installed motherboard standoffs in the case

Aligned motherboard with I/O shield

Secured motherboard using appropriate screws

Validation:

Motherboard seated flat with no flex

All mounting screws secured, not overtightened

Rear I/O aligned correctly with case cutout

📸 (Image: motherboard mounted in case)

### 10. Cable Management

Description:
Organized and secured cables to improve airflow and maintainability.

Actions Taken:

Routed cables behind motherboard tray where possible

Used zip ties to bundle excess cables

Ensured cables did not obstruct fans or airflow

Validation:

Clear airflow path

Side panels closed without resistance

Cables accessible for future maintenance

📸 (Optional image: cable management)

### 11. Initial Power-On Test

Description:
Performed initial power-on test prior to OS installation.

Actions Taken:

Connected monitor, keyboard, and power cable

Powered system on

Observed POST behavior

Validation:

System powered on successfully

Fans spinning

BIOS/UEFI screen displayed

No error beeps or warning LEDs

📸 (Image: system powered on / BIOS screen)

Notes & Observations

No hardware issues encountered during assembly

All components recognized during initial POST

System ready for BIOS configuration and OS installation
