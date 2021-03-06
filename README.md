# Radar-System

Frequency modulated continous wave (FMCW) radar operating at 2.4 GHz. Contains the schematic layouts and PCB designs for the hardware of the project, as well as the necessary code to make it all work.

dsp/      - The Python scripts used for analyzing the radar's output.

firmware/ - The code run on a microcontroller, that is responsible for gathering and transmitting samples to be processed.

hardware/ - Schematics and PCB designs for each of the system's circuit boards.

manual/   - The complete technical manual for this project.

This project is inspired by [MIT's coffee can radar project](https://ocw.mit.edu/resources/res-ll-003-build-a-small-radar-system-capable-of-sensing-range-doppler-and-synthetic-aperture-radar-imaging-january-iap-2011/), as well as [Henrik Forstén's radar build](http://hforsten.com/6-ghz-frequency-modulated-radar.html). Both projects piqued my interest in RF and showed me that tinkering with RF systems could be done at relatively low cost. I was able to learn quite a bit from their incredible work (Henrik's especially, his blog was extrmely helpful with learning about the RF hardware design for the radar), and it was ultimately what guided me through the process of creating my own system. For that, I owe them a great many thanks.
