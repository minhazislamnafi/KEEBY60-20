# KEEBY60+20

A moduler 60% mechanical hot-swapble keyboard. With 20% numpad attachment, it will form a proper 80% keyboard.

![License](https://img.shields.io/badge/license-OHL_v2-green.svg)
![QMK](https://img.shields.io/badge/Firmwire-QMK-red)
![pcb](https://img.shields.io/badge/KEEBY-v1.1-blue)
![Layout](https://img.shields.io/badge/layout-60+20-cyan)

<img width="4000" height="5657" alt="GITHUB REPO" src="https://github.com/user-attachments/assets/e5039e64-511a-4fa4-b768-2237ad78c495" />



# Specification

## KEEBY60
* Firmware: QMK
* Layout: Default 60% (main Keyboard)
* Socket: Hot-swapable Kailh Socket
* Switches: Cherry MX blue
* ARGB led: SK6812 mini-E
* MCU: Raspberry Pi RP2040 QFN-56
* USB hub IC: Fe1.1s SSOP-28
* USB IN: 2 type-C (One for USB+Power & another for only power)
* USB OUT: 1 6p magnetic connector & 2 type-c usb 2.0
        
     (2 USB 2.0 is only accessible when only 60% is used)
* Total keys: 63 ANSI layout
* Knob: EC11E rotary encoder (with push switch)
* Diaplay: SSD1306 0.91" I2C Oled 
* PCB: 2-layer (all components bottom mounted)
* Dimensions: pcb - 291* 116 mm (L * W)                                                                        
              case - 304* 130*45 mm  (L * W * H)


## KEEBY20
* firmware: QMK
* Layout: ISO 20% (numpad)
* Socket: Hot-swapable Kailh Socket
* Switches: Cherry MX blue
* ARGB led: SK6812 mini-E
* MCU: Raspberry Pi RP2040 QFN-56
* USB IN: 6p magnetic connector & 1 type-C

     (Both the 6p conn and type-C connector's data pin are connected)
* Total keys: 17 ANSI Numpad
* Knob: EC11E rotary encoder (with push switch)
* Diaplay: SSD1306 0.91" I2C Oled 
* PCB: 2-layer (all components bottom mounted)
* Dimensions: pcb - 81* 116 mm (L * W)                                                                         
              case - 95* 130*45 mm (L * W * H)


# Ask Why KEEBY60+20?

It's a freaking 80% moduler usb2.0 hub, mechanical hot-swappable programmable ARGB LED DIY 3D printed Keyboard with dual knob dual OLED display. wants to know more? It can be use a single 60% ANSI with 2 USB 2.0 HUB or a single 17 keys Numpad macropad or or or as said, a 6-pin magnetic connected ISO 80% Keyboard. 

TL;DR - The KEEBY60+20 is an all-around very versatile keyboard that runs on open-source QMK firmware.


## Onshape Full assembly [Link](https://cad.onshape.com/documents/68f2d0f77eb15a6c900279e4/w/64c05305f9ae419810eaa342/e/0ee3c387e4a094a987680ffc?renderMode=0&uiState=6a25de67f901e47d9e05b22d)

## CAD Render
<img width="5112" height="2000" alt="CAD render" src="https://github.com/user-attachments/assets/95f62c23-f997-4b21-8303-69377bbcc6d0" />


## PCB Render
My PC can't handle KiCad 10.0 now. so no render ;(
But I have some screenshots.

<img width="1365" height="767" alt="Screenshot 2026-05-31 113653" src="https://github.com/user-attachments/assets/70f7497f-7f0f-447b-9c99-b88d4864ef00" />

<img width="1127" height="557" alt="Screenshot 2026-06-07 144513" src="https://github.com/user-attachments/assets/9659e2f6-7f87-4cea-b852-927234ed2846" />

<img width="1365" height="767" alt="Screenshot 2026-05-28 215839" src="https://github.com/user-attachments/assets/f2f5a09d-62ec-4e5b-ac02-2846301a35a1" />

<img width="1365" height="767" alt="Screenshot 2026-05-28 235259" src="https://github.com/user-attachments/assets/165acae5-7079-48ba-9444-78f4cc7fef05" />


## FOLLOW THESE STEPS FOR BUILDING ##

**1. Spend some money $$ to buy the parts mentioned in [BOM](https://github.com/minhazislamnafi/KEEBY60-20/tree/main/PCB/production).**(2 separate BOM)

**2. Order the PCB for KEEBY60 and KEEBY20 using this [GERBER file](https://github.com/minhazislamnafi/KEEBY60-20/blob/main/PCB/production/keeby60/KEEBY_60_v1.1.zip) and [GERBER file](https://github.com/minhazislamnafi/KEEBY60-20/blob/main/PCB/production/keeby20/KEEBY_20_v1.1.zip).**

**3. Solder the SMD components of the PCB by hand ;) Or just order the PCBs with PCBA services, btw it will cost a lot.**

**4. Check with multimeter: Is the MCU getting 3.3v or not? If not diagnose by yourself :)**

**5. Place all the key switches.**

**6. Flash QMK firmware using USB connection ( I will add every step in details, once I have built IRL:)**

**7. 3D print the [Case](https://github.com/minhazislamnafi/KEEBY60-20/tree/main/CAD/CASE%203D%20file) .**

**8. Assemble your KEEBY60 and 20.**

**5. Test and enjoy more RGB= more FPS keyboard ( I will add every step in details, once I have built IRL:).**
