# What's the project about?

### Background
This project started from a desire to improve medical diagnosis in rural communities of low-income countries. In order to achieve this, we decided to design and build a low-cost microscope, given its versatility and widespread applications. 

The main purpose of the microscope is to serve as a cost-effective tool for the diagnosis of neglected tropical diseases (e.g., Chagas disease, dengue, chikungunya, leishmaniasis, amog many others) in rural areas, for which [fluorescence capabilities are essential](https://apps.who.int/iris/bitstream/handle/10665/119734/dsa281.pdf?sequence=1&isAllowed=y). On the other hand, we are also interested in reading Pap smear slides, given that cervical cancer is still a public health problem in developing countries.

### Target characteristics:
If we want the device to be appropriate in rural communities it should comply with certain characteristics:
- Low cost (we are aiming for ~500 USD).
- Usable by non specialized technicians.
- Not dependant on specialized physicians for a presuntive diagnosis.
- Not dependant on specialized additional equipment.

In orden to satisfy these requirements we envision a device with the following charcteristics:
- Microscope capable of doing brightfield and fluorescence microscopy.
- Motorized stage capable of XY scanning and autofocus.
- Operated via a Raspberry Pi and a touchscreen.
- Capable of capturing digital images and video.
- Linked with ML algorithms for *in situ* image processing.

As of August 2022, we have a functioning prototype with some of the desired characteristics but with some deficiencies that we are trying to overcome:
- Noisy stepper motors that sometimes move the sample when displacing the stage.
- Issues with Z motor control that will not allow an autofocus function.
- The XY movement is not sufficient to scan big samples like Pap smear samples.
- The actual design is an inverted microscope which somtimes makes difficult to work with certain samples.

On the other hand, there are still some features that we need to implement in order to achieve the desired outcome:
- Installation of limit switches in order to have a "Home" position.
- Installation of a fan for cooling.
- Mounting of the touchscreen.
- Add a potentiometer for controlling light intensity.
- Check if image is distorted when we add a bandpass filter in order to be able to perform fluoescence microsocopy.

Here is a picture of the current setup:

<img src="https://github.com/jossoca/OHA_micro/blob/main/Imgs/micro.jpeg" width=50% height=50%>



# Checklist for documentation during program
- [ ] Good intro explaining how the documentation is structured.
- [ ] List of electronic components.
- [ ] PCB design.
- [ ] List of mechanical parts along with their CAD files.
- [ ] Software for operating the device (lighting, XY positioning, photo capturing, etc.).
- [ ] GUI.
- [ ] License.
