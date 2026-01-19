# Troubleshooting Log
## Issue 1: No Display Output During Bench Test

**Phase:** Pre-Installation Hardware Validation (Bench Test)

## Description

During the initial bench test, the system powered on but no video output was displayed on the monitor.

## Symptoms Observed

* System powered on successfully

* Fans spinning

* No image displayed on monitor

* No BIOS/POST screen visible

<img/>

## Initial Assessment

Based on the symptoms, potential causes included:

* Faulty or improperly connected HDMI cable

* Graphics card (GPU) not properly seated

* Display cable connected to incorrect video output

## Troubleshooting Steps Taken

1. **HDMI Cable Verification**

    - Connected the same HDMI cable to a Nintendo Switch

    - Verified successful video output on the monitor

    - Result: HDMI cable confirmed functional
  
<img src="https://i.imgur.com/rjkBXLq.jpeg" height="80%" width="80%" alt="Nintendo Switch displaying video output on monitor"/> 

2. **GPU Seating Verification**

    - Inspected GPU installation in the PCIe slot

    - Confirmed GPU was fully seated and secured

    - Result: GPU installation verified as correct

3. **Display Output Check**

    - Noticed HDMI cable was connected to the motherboard HDMI port

    - Reconnected HDMI cable directly to the GPU output port

    - Result: Video output immediately displayed on monitor

<img src="https://i.imgur.com/xSv3ywa.jpeg" height="80%" width="80%" alt="HDMI cable connected directly to GPU output"/>

## Root Cause

HDMI cable was connected to the motherboard video output instead of the discrete GPU. Since the CPU does not provide integrated graphics, no display signal was generated from the motherboard port.

## Resolution

Reconnected the HDMI cable directly to the graphics card, restoring video output and allowing the system to display the BIOS/POST screen successfully.

## Validation

* Monitor displayed BIOS/UEFI screen

* System proceeded with normal POST

* No further display issues observed

<img src="https://i.imgur.com/WDQBcl5.jpeg" height="80%" width="80%" alt="BIOS/UEFI screen displayed after resolution"/>

## Lessons Learned

* Always verify display cable is connected to the correct video output when using a discrete GPU

* Bench testing helps quickly identify and resolve configuration issues before full case installation
