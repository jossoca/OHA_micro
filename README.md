# Intro
This project started from a desire to improve medical diagnosis in rural communities of low income countries. We have chosen a microscope given its versatility and widespread applications. If we want the device to be appropriate in rural communities it should comply with certain characteristics:
- Low cost.
- Usable by non specialized technicians.
- Not dependant on specialized physicians for a presuntive diagnosis.
- Not dependant on additional equipment.

In orden to satisfy these requirements we envision a device with the following charcteristics:
- Microscope capable of doing brightfield and fluorescence microscopy.
- Motorized stage capable of XY scanning and autofocus.
- Operated via a Raspberry Pi and a touchscreen.
- Capable of capturing digital images and video.
- Linked with ML algorithms for in situ image processing.

As of August 19th 2022, we have a functioning prototype with some of the desired characteristics but with some deficioencies that we are trying to overcome:
- Noisy stepper motors that sometimes can move the sample with the stage displacement.
- The XY movement is not sufficient to scan big samples like Pap smear samples.
- The actual design is an inverted microscope which somtimes makes difficult to work with certain samples.
- We want to add some limit switches in order to have a "Home" position.


# Checklist for documentation during program
- [ ] Good intro.
- [ ] List of electronic components.
- [ ] PCB design.
- [ ] List of mechanical parts along with their CAD files.
- [ ] Software for operating the device (lighting, XY positioning, photo capturing, etc.).
- [ ] GUI.
- [ ] License.
