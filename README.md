# What's the project about?

#### Background
This project started from a desire to improve medical diagnosis in rural communities of low-income countries. In order to contribute in this direction, we decided to design and build a microscopy platform with certain relevant characteristics. We went for microscopy, given its simplicity, versatility, and widespread applications. 

The main purpose of the platform is to serve as a cost-effective tool for the diagnosis of neglected tropical diseases (e.g., Chagas disease, dengue, chikungunya, leishmaniasis, and some others) in rural areas, for which [fluorescence capabilities are essential](https://apps.who.int/iris/bitstream/handle/10665/119734/dsa281.pdf?sequence=1&isAllowed=y). Additionally, we are also interested in reading Pap smear slides, given that cervical cancer is still a public health problem in several developing countries.

#### Features
In order to satisfy our main purpose and to be appropriate for its use in rural communities, we envision a device with the following features:
- Low cost (we are aiming for ~500 EUR).
- Microscope capable of doing brightfield and fluorescence microscopy.
- Motorized stage capable of XY scanning and autofocus. The scanning area should be large enough to cover Pap smear samples (50x20mm approx).
- Operated via a Raspberry Pi and a touchscreen.
- Capable of capturing digital images and video.
- Usable by non specialized technicians.
- Not dependant on specialized physicians for a presuntive diagnosis; linked with computer vision algorithms for *in situ* image processing.
- Not reliant on specialized extra equipment.

#### State of the project:
As of August 2022, we have a functioning prototype with some of the desired characteristics:
- Brightfield inverted microscope.
- Optical resolution ~0.3 $\mu m$.
- Motorized movement in three axis with a postitioning resolution of 0.3 $\mu m$ approx. We can move in an area of 40x20mm approx.
- Live sample imaging and capacity for capturing high quality digital images and video.
- Cost: ~500 EUR.

But with some deficiencies that we are trying to overcome:
- Noisy stepper motors that sometimes move the sample when displacing the stage.
- Issues with Z motor control that will not allow an autofocus function.
- The XY movement is not sufficient to scan big samples like Pap smear samples.
- The actual design is an inverted microscope, which sometimes makes it difficult to work with certain samples.

On the other hand, there are still some features that we need to implement in order to achieve the desired outcome:
- Installation of limit switches in order to have a "Home" position.
- Installation of a fan for cooling.
- Mounting of the touchscreen.
- Add a potentiometer for controlling light intensity.
- Check if the image is distorted when we add a bandpass filter in order to be able to perform fluoescence microscopy.

Here is a picture of the current setup:

<img src="https://github.com/jossoca/OHA_micro/blob/main/Imgs/annotated.jpeg" width=70% height=70%>
