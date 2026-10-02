# transit-detector
A device that detects exoplanet transits using a photodiode and Arduino 
![Transit Detector Scheme](IMG_20261002_085931.jpg)
# Exoplanet Transit Detector

A device that detects exoplanet transits by measuring the brightness of a star.

## How it works
1. The BPW34 photodiode captures starlight and converts it into a small current.
2. The LM358 op-amp amplifies the signal with a gain of 100 (R2/R1 = 100).
3. The Arduino Nano reads the amplified signal on pin A0 (0-1023).
4. The OLED display shows the light curve in real time.
5. When a planet passes in front of the star, the brightness drops — this is a transit.

## Code
The Arduino code reads the analog value from the photodiode, prints it to the serial monitor, and displays it on the OLED screen.

## Parts
- BPW34 photodiode
- LM358 op-amp
- Arduino Nano V3
- OLED Display 0.96" I2C
- Resistor kit
- Capacitor kit
- Jumper wires
- Project box

## Author
Anna, 14 years old, Gomel, Belarus
