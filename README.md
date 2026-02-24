# Tru-Touch-v1.2
1.5-Micron Precision Nozzle-Contact Probe for 3D Printers

# Tru-Touch v-1.2 - Ultra-High Precision Nozzle Probe
Tru-Touch v-1.2 is an intelligent, piezoelectric nozzle-contact probe designed for 3D printers. 
It achieves sub-micron precision by using the nozzle itself as the trigger point, 
eliminating the need for offset calibration.
🚀 Key Performance Metrics

 #  Precision (Repeatability):   1.5 Microns (0.0015 mm) verified.
 #  Typical Standard Deviation : 0.001369 mm (Validated in Klipper).
 #  Zero Offset: Probes directly with the nozzle — no X/Y offset calibration required.
    Thermal Stability: Remote control board isolates electronics from hot-end heat soak.

<img width="572" height="279" alt="150-150" src="https://github.com/user-attachments/assets/faae50ed-26c4-4f6c-93f7-338cb49ccbdf" />
<img width="572" height="279" alt="150-150" src="https://github.com/user-attachments/assets/faae50ed-26c4-4f6c-93f7-338cb49ccbdf" />


🛠️ Hardware Features


![20260224_173607](https://github.com/user-attachments/assets/f33079d9-465f-4ba6-b584-bb27677e49cc)
![20260224_173607](https://github.com/user-attachments/assets/f33079d9-465f-4ba6-b584-bb27677e49cc)

    One-Screw Mounting: Minimalist carriage mount; adds negligible mass to the toolhead.
    Hybrid Processing: Analog preconditioning combined with STM32 DSP for superior noise rejection.
    Visual Feedback: Dual LEDs with heartbeat and real-time contact-blink patterns.
    User Tunable: Onboard potentiometer to match the trigger threshold to your gantry resonance.

⚠️ CRITICAL: RE-PINNING REQUIRED
Tru-Touch v-1.2 uses a specialized safety-interlock pin-out. You MUST rearrange your JST/DuPont connector to match the TRU-TOUCH row below before applying power.

Pin	Function	      TRU-TOUCH COLOR	      Standard BLTouch Color
1	Ground (GND)	         WHITE	                BROWN
2	VCC (+5V)	             BLACK	                RED
3	Servo (Control)	       YELLOW	                YELLOW
4	Ground (GND)	         RED	                  BLACK
5	Z-Min (Signal)	       BROWN	                WHITE

📂 Repository Contents

    TruTouch_v1.2_Manual.pdf: Full technical specs and Klipper configuration.
    TruTouch_v1.2_Mechanical.step: 3D model for designing custom mounts.
    LICENSE: Licensed under CC BY-ND 4.0 (Commercial use permitted).

🤝 Beta Testing & Inquiries

Currently looking for beta testers with rigid-frame machines (Voron, RatRig, etc...) and Hard Surfaces (Glass, G10, Ceramic).
Contact: Reach out to me on Discord: @yego6833 or find me in the Voron Design server.
