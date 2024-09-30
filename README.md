eXtoplasmVR was created because of my love for the SlimeX cases but I wanted to upgrade my trackers to BNO085 IMUs and wanted to include a PCB to reduce issues I was having with reliability of soldered wires. I modelled the tracker cases by eyeballing the original SlimeX cases after designing the PCB to make it fit and kept as much of the design language of the original cases as I could as I loved the compactness and comfort that these cases gave me whilst I used the originals with BMI160 IMU's.

To everyone that worked on the original SlimeX - thank you for inspiring me to brush off my CAD skills - I know there is a lot of stuff wrong with these trackers and a lot of stuff I would like to change and refine and improve but for now, I think I am happy enough with them that I would like to release these in to the wild in the hopes that they help someone or that someone else can find them useful. Also - thank you all for your help when I originally made my trackers. <3

If anyone actually reads this and enjoys this design, please see below for a link to the original design:

https://github.com/Yasu3D/SlimeX-FDM

Also after printing probably about 100 revisions over the months and refining them, my printer needs a rest. She has done well for being 10 years old nearly lol.

![image](https://github.com/user-attachments/assets/da7bfcec-4565-4603-9a2d-250cc24354a4) ![image](https://github.com/user-attachments/assets/273793e3-69f5-493c-9df0-49c7bded62b4)

eXtroplasm v3.0 - Includes bolt closure to securely hold the tracker together with a threaded insert in the top section of the tracker

![image](https://github.com/user-attachments/assets/89f51dc9-802b-497a-963c-0e2f1051f466)
AUX Case

![image](https://github.com/user-attachments/assets/083f9613-9399-4c9f-a2fd-9f97c141dfc8) ![image](https://github.com/user-attachments/assets/5dd6bf3a-07d4-4932-92a6-11de7674c4ec)

eXtoplasm Strack Strap prototype for use with EOZ style straps with 1/4" threaded insert in the centre of the X - shaped bracket - Still experimental, YMMV

Still to do:

- Make a battery protector (I currently just cover the back of the PCB facing the battery with a few layers of blue painters tape I use on my buildplate for my printer.

Current Goals: 

- Make an adaptor that allows for using the EOZ track straps or other straps intended to be used with Vive or Tundra 1/4" thread inserts.

Motivation to use the EOZ style straps was because I was sick of repairing AUX cables and wanted to convert all my trackers to main trackers and have better comfort in VR for longer periods but still have the flexibility of adding AUX trackers if desired.

Current issues:

- Adaptor plates seem to be causing bad tracking quality and higher than excpected drift, particularly on the Chest and Hip straps when using EOZ straps, these STLs have been included in the experimental - not recommended folder. For now, tracking quality is better with the standard tracker bases and using 38mm elastic with velcro patches.
- Motivation to make battery protector plate.

Printing Details: 

- Will require light supports for the USB-C holes, 5-pin connector hole and the sections for the elastic straps if printing the standard version not the EOX adaptor varient.

Hardware Needed:

- SlimeVR BNO085 IMU x1 Per Main Tracker or AUX Tracker
- Wemos D1 Mini v4 Microcontroller
- TP4056 x1 Per main tracker
- SS22F32 Switch x1 Per main tracker
- 180KΩ - 1/4W x1 Per Main Tracker
- JST 2.0mm Ph 2-Pin Female Connector - 1 Per Main Tracker
- 1N5817 x2 Per Main Tracker
- JST-PH 2.0mm Pitch 90 degree female plug x1 Per main tracker. Not strictly required if you have no intention using AUX trackers 

- Elastic+Velcro straps if using the standard version. 38mm width for the main trackers and 25mm for the AUX trackers
- M3x5.7x4.6mm Threaded Knurled Brass Inserts x1 (Per Tracker - If using standard version, x3 per main tracker if using EOZ Style)
- 1/4"-20 Female Thread Brass Threaded Insert (Only required for EOZ Adaptor Plate varient)
- M3 x 12mm Hex Socket Cap Bolt x1 (If using Standard variant)
- M3 x 20mm Hex Sicket Cap Bolt x3 (If using the EOZ Varient)
   
