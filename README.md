# nothing-3a-orangefox-port
Attempt to port OrangeFox Recovery to Nothing Phone (3a) (Qualcomm-based device)
# OrangeFox Recovery Port Attempt — Nothing Phone (3a / Asteroids)

## Objective

Adapt a generated Android device tree for the Nothing Phone (3a) (“Asteroids”) toward an OrangeFox custom recovery port.

## Repository Scope

* Maintained a public GitHub repository for the Nothing Phone (3a) recovery/device-tree work
* Forked from `twrpdtgen/android_device_nothing_Asteroids`
* Used the generated TWRP device tree as a starting point for OrangeFox-oriented recovery work

## Technical Work Reflected in the Repository

* Worked with Android recovery and device-tree configuration files including:

  * `BoardConfig.mk`
  * `AndroidProducts.mk`
  * `device.mk`
  * `recovery.fstab`
  * `twrp_Asteroids.mk`
  * `omni_Asteroids.mk`
  * `extract-files.sh`
  * `setup-makefiles.sh`
  * `vendorsetup.sh`
* Organized project structure for device-specific recovery bring-up
* Added GitHub workflow files under `.github/workflows` to support repository validation and project checks

## What This Project Demonstrates

* Familiarity with Android device tree structure
* Hands-on work with custom recovery configuration files
* Use of GitHub for source control during Android low-level development
* Early-stage automation and validation mindset for device-tree maintenance

## Current Limitation

* This repository documents the device-tree and project setup side of the port attempt
* Runtime testing results and hardware-debug findings are not fully preserved in the current repo state
