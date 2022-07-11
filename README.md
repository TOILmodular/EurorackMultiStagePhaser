# EurorackMultiStagePhaser
## General
A multi-stage phase shifter in Eurorack format with up to 12 stages selectable.

The design is based on the Eight Stage Phase Shifter from Music From Outer Space.

I extended the number of available stages to 12 and added the possibility to select the output point from the stage chain for two different outputs.

One of them is directly sent to the output path to one of two audio outputs.

The other oner is fed into the feedback loop and the second audio output.

![Phaser Flowchart](https://user-images.githubusercontent.com/97026614/174950328-fcf31c8b-8099-4bc2-b031-ef11fb446f37.jpg)

Using both outputs for left and right audio channels creates a nice pseudo-stereo effect.

The selection of stages has loosely been inspired by the AJH SYNTH Next Phase module.

There is a [YouTube video](https://youtu.be/MpHdmQVAfss) available, showing a demonstration of the sound with my module.

## Module Built and PCBs
If you want to build the module yourself, I uploaded the schematics, the BOM and a set of Gerber files.
For creating a front panel, I added a picture with the dimensions and positions of the control components, fitting to the control PBC layout.

The module is built up by two PCBs, the control board with the control components going to the front panel and the main board behind it.
Those boards are connected via standard male and female headers with a pin distance of 2.54mm (0.1 inch).

There are two different versions for the control board, an "original" and a "Thonk" version.
Reason is that for my own module, I am using specific potentiometers - 16K4 series from Supertech Electronics - and 3.5mm jack sockets - MJ-355 from Marushin - available at my local electronics shop.

However, since most DIY projects for Eurorack modules out there are using potentiometers from ALPHA and so-called THONKICONN jacks, as they are provided by Thonk in the UK, I also created a version with footprints for those components.
Choose the one you need.

I created the Gerber files with the online tool EasyEDA and ordered it at JLCPCB.
I cannot guarantee, if this set of zipped Gerber files works also for other providers, like e.g. PCBWay. I have not tried that. But I saw online, that others did it.

If you want to know about my DIY building process, take a look at those two YouTube videos:
- [How I design PCBs for my Eurorack Synth Modules](https://youtu.be/pXtuV9Pv-m4)
- [Eurorack Module Synth - Building an Electric Druid Wavetable Oscillator Module](https://youtu.be/ECpdo4HfqLg)

## Additional Information about specific Components
If you want to use the Gerber files for having PCBs manufactured, please note the following information about components used.

- The design makes use of the SMD version of the LM13700 IC, called V13700M.
- There is a number of SMD 0.1uF capacitors with the package size 1608.
- For the tranistors 2N3904 and 2N3906, the SMD versions MMBT3904 and MMBT3906 are used on the PCBs.
- In order to save space, I am always using small size resistors, about 3mm length, which are about half the size of usually used resistors.
- On the control board, you will find electrolytic capacitors with a rectangle next to them. Since these capacitors are too tall for standing upright on the board with the main board on top of it, those capacitors need to be mounted in a rectangular position. The rectangle shows the position for each bent-over capacitor.
- The two rotary switches used are the ALPHA SR1712F-0109-15K0A-B9-N-027. The Mouser number is 105-SR1712F-18NS.
- The switch used is a standard SPDT toggle switch.

<img width="359" alt="Screen Shot 2022-06-22 at 15 26 07" src="https://user-images.githubusercontent.com/97026614/174958642-b65b1f33-e615-49bf-8ea9-ad6ecc099233.png">
<img width="359" alt="Screen Shot 2022-06-22 at 15 26 34" src="https://user-images.githubusercontent.com/97026614/174958666-8c2f2e4d-37b8-4c13-b2ad-2ad142b3b192.png">
<img width="401" alt="Screen Shot 2022-06-22 at 15 27 18" src="https://user-images.githubusercontent.com/97026614/174958682-9724aaf2-9ab1-4170-90b1-1d6895cf309b.png">
<img width="401" alt="Screen Shot 2022-06-22 at 15 27 56" src="https://user-images.githubusercontent.com/97026614/174958721-44e65520-f342-4ed7-8a37-06ac870dd1f5.png">

![IMG_6239](https://user-images.githubusercontent.com/97026614/174964178-5953e540-e1ce-4a40-991f-2e0403efb3aa.jpeg)
![IMG_6240](https://user-images.githubusercontent.com/97026614/174964302-207582f5-3a4f-4b96-b60d-7ec0c17e44b7.jpeg)
![IMG_6241](https://user-images.githubusercontent.com/97026614/174964337-eedc10ff-4c9c-4038-a5a6-4f5cf28981f7.jpeg)
![PhaseShifterNew6](https://user-images.githubusercontent.com/97026614/174964448-131ab7c0-5a09-443f-abb0-7dbfd79ef84c.JPG)
![IMG_6242](https://user-images.githubusercontent.com/97026614/174964569-63cf38ae-6a35-48bb-a4fb-4f45cad27e5d.jpeg)
