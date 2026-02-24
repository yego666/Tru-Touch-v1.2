# Tru-Touch-v1.2
# 1.5-Micron Precision Nozzle-Contact Probe for 3D Printers

### Tru-Touch v-1.2 - Ultra-High Precision Nozzle Probe

Tru-Touch v-1.2 is an intelligent, piezoelectric nozzle-contact probe designed for 3D printers. 
It achieves sub-micron precision by using the nozzle itself as the trigger point, 
eliminating the need for offset calibration.

# Key Performance Metrics

<img width="572" height="279" alt="150-150" src="https://github.com/user-attachments/assets/faae50ed-26c4-4f6c-93f7-338cb49ccbdf" />

 ###  Precision (Repeatability):   1.5 Microns (0.0015 mm) verified.
 ###  Typical Standard Deviation : 0.001369 mm (Validated in Klipper).
 ###  Zero Offset: Probes directly with the nozzle — no X/Y offset calibration required.
 ###   Thermal Stability: Remote control board isolates electronics from hot-end heat soak.

### Hardware Features

![20260224_173607](https://github.com/user-attachments/assets/f33079d9-465f-4ba6-b584-bb27677e49cc)


### One-Screw Mounting: Minimalist carriage mount; adds negligible mass to the toolhead.
### Hybrid Processing: Analog preconditioning combined with DSP for superior noise rejection.
### Visual Feedback: Dual LEDs with heartbeat and real-time contact-blink patterns.
### User Tunable: Onboard potentiometer to match the trigger threshold to your gantry resonance.

### CRITICAL: RE-PINNING REQUIRED
Tru-Touch v-1.2 uses a specialized safety-interlock pin-out. You MUST rearrange your JST/DuPont connector to match the TRU-TOUCH row below before applying power.

<img width="433" height="138" alt="pin-colors" src="https://github.com/user-attachments/assets/a95275aa-d3f9-4de7-a7a2-122f89c6eb05" />



### Repository Contents

    TruTouch_v1.2_Manual.pdf: Full technical specs and Klipper configuration.
    TruTouch_v1.2_Mechanical.step: 3D model for designing custom mounts.
    LICENSE: Licensed under CC BY-ND 4.0 (Commercial use permitted).

### Beta Testing & Inquiries

Currently looking for beta testers with rigid-frame machines (Voron, RatRig, etc...) and Hard Surfaces (Glass, G10, Ceramic).
Contact: Reach out to me on Discord: @yego6833 or find me in the Voron Design server.
