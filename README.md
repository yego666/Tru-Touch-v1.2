# Tru-Touch v1.2 – 1.5-Micron Precision Nozzle-Contact Probe for 3D Printers

# 🚀 Tru-Touch v1.2: High-Precision Nozzle Probe
**Beta Program Status: 5 Units Available (EU Only)**

To apply for a beta unit:
1. [**Open a New Issue here**](https://github.com) 
2. **Title:** Beta Application - [Your Printer Model]
3. **Body:** Include your country for shipping (~€8–15).

**Tru-Touch v1.2** is an intelligent, piezoelectric nozzle-contact probe designed for 3D printers.  
It achieves sub-micron precision by using the **nozzle itself** as the trigger point — eliminating offset calibration.

### Key Performance Metrics
<img width="572" height="279" alt="150-150" src="https://github.com/user-attachments/assets/faae50ed-26c4-4f6c-93f7-338cb49ccbdf" />

- **Precision (Repeatability)**:  1.5 Microns (0.0015 mm) verified
- **Typical Standard Deviation**: 0.001369 mm (validated in Klipper, stats provided)
- **Zero Offset on All Axes**:    Probes directly with the nozzle — no X/Y offset calibration
- **Thermal Stability**:          Controller board detached from piezo sensor
- **No Maintenance Solution**:    Install, Fine-tune, Set up, and forget.
- **Perfect for Adaptive Bed Meshing**: Works perfectly with native Klipper Adaptive Bed Meshing
- **Performance Constantly Improving**: Ongoing R & D for better performance, and broader printer base

### Hardware Features
- **One-Screw Mounting**: Minimalist carriage mount; adds negligible mass to the toolhead
- **Easy Installation**:  Reuses existing BL-Touch cabling with minor adjustments
- **Hybrid Processing**:  Analog preconditioning + DSP for superior noise rejection
- **Visual Feedback**:    Dual LEDs with heartbeat and real-time contact-blink patterns
- **User Tunable**:       Onboard potentiometer to match trigger threshold to your gantry resonance

![Tru-Touch Probe](https://github.com/user-attachments/assets/f33079d9-465f-4ba6-b584-bb27677e49cc)

 ***Note*** : Battery not included.
### CRITICAL: SIMPLE PLUG RE-PINNING REQUIRED
Tru-Touch v1.2 uses a specialized safety-interlock pin-out. You **MUST** rearrange your JST/DuPont connector to match the TRU-TOUCH row before applying power.

### Repository Contents
- `README.md`: Introduction to the Tru-Touch Probe and its features
- `TruTouch_v1.2_Mechanical.step`: 3D model for designing custom mounts.
- `LICENSE`: Licensed under CC BY-ND 4.0 (Commercial use permitted).
- `Physical-Installation.pdf`: Full technical specs and physical installation instructions.
- `Klipper_Integration_Guide.pdf`: Detailed Klipper integration instructions.
- `Probe_Tuning_Guide.pdf`: Step by step guide on probe tuning for best performance
- `Printing_notes.pdf`: Some notes on leveling and printing with the Tru-Touch Probe

### Beta Testing & Inquiries
Currently looking for beta testers with rigid-frame machines (Voron, RatRig, etc.) and hard surfaces (glass, G10, ceramic).  
Contact me on Discord: **@yego6833** (Voron Design server).

Installation Guide: [TruTouch_v1.2_Physical-Installation.pdf](https://github.com/yego666/Tru-Touch-v1.2/blob/main/docs/guides/physical-installation.pdf))
