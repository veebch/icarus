[![YouTube Channel Views](https://img.shields.io/youtube/channel/views/UCz5BOU9J9pB_O0B8-rDjCWQ?style=flat&logo=youtube&logoColor=red&labelColor=white&color=ffed53)](https://www.youtube.com/channel/UCz5BOU9J9pB_O0B8-rDjCWQ) [![Instagram](https://img.shields.io/github/stars/veebch?style=flat&logo=github&logoColor=black&labelColor=white&color=ffed53)](https://www.instagram.com/v_e_e_b/)

# Icarus

This is the instruction kit for making the simplest of LED lights. It all centres around a CREE XLamp® CMU2236 LED (available with [CRI](https://en.wikipedia.org/wiki/Color_rendering_index)  of 80 or 90). It is an inexpensive (~$8) and bright (~5.5Klm) LED. It is powered by USB-c and the 100cm² heatsink means that the light is silent. There's lots of room for improvement (tripod mount, active cooling, better enclosure) but we're sharing this early because we find it handy for taking photos/video (example video below).

## Components

- 10cm by 10cm aluminium heat sink
- CREE LED - XLamp® CMU2236
- 20 V USBC PD trigger
- Thermal paste
- Epoxy Glue
- 1000mA Constant Current buck convertor
- Toggle Switch

## Assembly

- Attach LED to the centre of the heatsink using epoxy and thermal paste
- Print the Case and LED cover using the files in the [3d](./3d/) directory
- Place PD trigger, switch and CC power supply into case
- Solder wires from the PD trigger to the CC buck convertor (negative wire goes via the toggle switch), then the wires go from the led in the centre of the heatsink
- Mount the LED cover (we used double sided tape)

## Results

[![demo video](http://img.youtube.com/vi/nvTH3jrjlzU/0.jpg)](http://www.youtube.com/watch?v=nvTH3jrjlzU "Video Title")

## Disclaimer

This light is USB powered but uses a lot of Electrical current and gets hot. If you make one, be careful. it's at your own risk. We take no responsibility for any injury.

