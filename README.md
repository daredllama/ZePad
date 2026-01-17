# ZePad

ZePad is six key hack pad that has an OLED screen, a rotary encoder, and three LEDs.

Was created using KiCad and Onshape and used QMK firmware.

## Features:
- 2 Layer Case with a plate in the middle
- 6 Keys
- 128x32 OLED
- EC11 Rotary Encoder
- 3 LEDs

## CAD Model
The case uses 5 M3 screws and 5 heatset inserts. There are 4 assembly holes on the perimeter of the case and one in the middle through the PCB.

The middle plate holding the keys is sandwiched between the cover and the plate.

<img width="1772" height="1325" alt="Image" src="https://github.com/user-attachments/assets/69519e31-4f51-4164-9d64-2ae387b8d48b" />

Made in Onshape

## PCB
This is the PCB, made using KiCAD. I found the image off of the internet and converted it to a silkscreen for the design you see

Schematic

<img width="1669" height="953" alt="Image" src="https://github.com/user-attachments/assets/6bc32c10-e4dd-4547-9092-d132dac47bc4" />

PCB

<img width="897" height="589" alt="Image" src="https://github.com/user-attachments/assets/c295c634-c499-4123-b455-1603b81e4261" />

## Firmware
This hack pad's firmware uses QMK firmware.

Features include:
- 4 Keys mapped currecntly to W,A,S,D,Q,E
- Rotary Encoder to zoom in or out
- OLED that displays "ZePad"

I am preobably going to include more advanced features(different layers, complex keycodes, animations) but I wanted to keep it relatively simple for now.

## BOM
Here is what is needed to make ZePad:

- 6x Cherry MX Switches (preferably MX Blacks)
- 6x DSA Keycaps
- 5x M3x5x4 Heatset inserts
- 5x M3x16mm Screws
- 6x 1N4148 Diodes
- 3x WS2812B LEDs
- 1x 0.91" 128x32 OLED Display
- 1x EC11 Rotary Encoder
- 1x XIAO RP2040
- 1x Case (3 printed parts)

## Reflection
This was my first experience with any sort of hack pad. KiCad was pretty intuitive once I had learned the basic stuff, but THANK GOD to Tom Scotto for teaching me how to use it. I think the QMK firmware was a lot simpler becuase I could use the templates already provided by other people and work off. I had already had tons of previous experience in Onshape, so it wasn't too hard to desgin the case. Also the orpheuspad inspired this hack pad heavily.

