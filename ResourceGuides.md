# Resource Guides and Troubleshooting

## *In-Lab*

### Audio Studio
#### Authorization
[This illustrated guide](media/AudioStudioPrimer.pdf) lives in the Audio Studio for patron reference. The authorization process can be completed by a trained student staffer and takes between 30-45 minutes. 

#### Tips and Troubleshooting
Here are some common problems with the Audio Studio and how to solve them.

- *"I’m not getting any audio in the speakers from my DAW when my track is playing back."*
  - Check the preferences for your software and make sure it’s using the Scarlett 18i20 USB interface as the input/output audio device. Also, make sure the monitor speakers are not muted the volume knob is turned up!
  - If that doesn't work, try resetting the routing in the Focusrite Control software (`File -> Output Presets -> System Playback` in the menu bar)
- *"My microphone is plugged in and the gain is turned up, but I’m not seeing any signal from it!*
  - Condenser microphones need *phantom power* supplied by the Scarlett. Press the “48 V” buttons on the Scarlett to turn on phantom power for channels 1-4 or 5-8.
#### Signal Map
![Audio Studio Signal Flow 2023](media/Audio%20Studio%20Signal%20Flow%202023.png)

#### Plugin Guide
The Audio Studio computer has the following extra plugins available (as Audio Units):

- [Waves Gold Bundle](https://www.waves.com/bundles/gold)
- [Native Instruments Komplete](https://www.native-instruments.com/en/catalog/software/)
- [iZotope Ozone](https://www.izotope.com/en/products/ozone.html)
- [Serum](https://xferrecords.com/products/serum/)
- [Spitfire LABS sample libraries](https://labs.spitfireaudio.com/)

### VR Studio
The multi-use VR studio is a space that can be freely configured depending on the patron's need. It contains a set of "endless" backdrops for photo/video recording, a whiteboard with a table and chairs, a TV on a wheeled cart, and a room-scale HTC Vive Pro VR System.

#### Vive Quick Start Guide

Patrons can follow the [illustrated guide on the wall](media/VRQuickstartPoster.jpg) in the VR Studio, but here are the steps in case staff needs to help them:

1. ***Important for safety: Clear the area within the tape on the floor!***
2. If needed, plug in the TV cart power strip and the computer's ethernet cable into the wall jack.
3. Turn on the VR computer. The `dmcgamer` account should log in automatically.
4. Take the Vive wireless headset from the wall. Plug the USB-A/USB-A cable from the battery pack to the wireless receiver and press the power button on top of the battery pack. The green LED on the headset's wireless receiver should start blinking.
5. Start the `VIVE Wireless` app (shortcut on the Desktop) and make sure it's connected to the headset. Please note that the headset must be a few feet away from the wireless receiver perched on the top of the TV in order to register as connected.
6. Clip the battery pack to your belt or place it securely in your pocket.
7. Start `SteamVR` app (shortcut on the Desktop). The app's indicators show the connection between the headset, the room sensors, and the two controllers. Press the button on each controller to turn it on.
8. Launch your games from SteamVR!

After playing VR, please shut down the computer and unplug the USB cable from the battery pack, and return the controllers, battery pack, and wireless keyboard to the charging station on the TV cart. Hang the Vive headset on the wall hook.

### Lab Projector
The lab projector can be controlled by a remote on the column closest to the projector screen. There are two inputs on the projector, one for the wireless Crestron system which displays instructions on screen, and a direct HDMI connection that can be accessed by where the remotes are stored.

Any computer in the lab can connect to the projector using the [Crestron AirMedia](https://www.crestron.com/Software-Firmware/Software/Air-Media/AirMedia_OSx_Guest_Application/4-1-14) app.

To cast to the projector from a lab computer:
1. Open Crestron AirMedia (icon should be in the Dock)
2. Click "Ask Me" and then "OK" if you get a popup about "Session delegation options."
3. In the Connect screen, you'll see `AM-200-00107FFD4EEF - 10.166.42.218` listed. Click "Connect."
4. Enter in the AirMedia PIN code: `3817`.
5. Click the Control Center icon in the top right of the menu bar and select `Screen Mirroring`.
6. Select `AM-200-00107FFD4EEF` in the menu and enter the AirMedia PIN code again: `3817`.
7. You may need to press "source search" on the projector remote to get to the display.
8. No sound? Select `AM-200-00107FFD4EEF` as the audio output device in the system or specific application.

### 3D Printers

#### 3D Printer Authorization
##### Step 1: [Watch the authorization Video](https://player.vimeo.com/video/672528585)

##### Step 2: "Show Me" Demo with DMC Staff
1. Make sure the Prusa and Raspberry Pi are powered on (Pi should never be turned off)
2. Load filament:
   - Autoload filament: push into extruder tube until the screen prompts to select filament type. Print head will start heating and pull filament in automatically. *Note: if you feel resistance before getting the screen prompt, it may not be going correctly into the tube. Try trimming the end of the filament to a clean point so it can go through the collet at the end of the tube and into the extruder*
   - Confirm that the material is extruding correctly from the print head.
3. Log into the shared dmc3D account on the computer by the 3D printers 
   - Username: `dmc3D` PW: `dmc3Dpatron`
4. Log into the OctoPrint web interface 
   - Username: `dmc3D` PW: `dmc3Dpatron`
   - There is a shortcut on the dmc3D account's desktop for each printer, or you can open [10.166.42.107](http://10.166.42.107) in a web browser (for Prusa 1) or [10.166.42.19](http://10.166.42.19) (for Prusa 2)
5. Check the connection to the printer in OctoPrint using the "Connection" module in the sidebar. If it is not connected, press `Connect`.
6. Slice and send a print from PrusaSlicer to the OctoPrint server. Make sure the correct printer is selected in PrusaSlicer before slicing!
7. There's a little ![This is the button to click](media/PrusaGarrow.png) button in the lower right hand corner of the PrusaSlicer Interface. Click this.
8. Look at the webcam stream you can see anywhere on campus (or VPN into Hopkins)
 [bit.ly/dmcprusa1](http://bit.ly/dmcprusa1) and [bit.ly/dmcprusa2](http://bit.ly/dmcprusa2)
1.  Cancel the test print with OctoPrint and remove the first layer that started depositing on the build plate. Remove the steel sheet from the bed and twist it instead of scraping it off.
2.  Select "Unload filament" from the menu on the Prusa screen and properly secure the filament end in the spool.

#### 3D Printer Tips and Troubleshooting

Here are some common questions about 3D printing from patrons.

Question: *Can I bring my own filament?*

Answer: Generally, yes, but it must be pre-approved by the Multimedia Specialist ahead of time to make sure that it's compatible with the printer and won't damage the printer (some specialty filaments have abrasive elements in them)


Question: *How do I load the filament in the enclosures?*

Answer: Those used to the top-down loading system with the un-enclosed Prusas will notice a bit of a difference. Hang the filament on the hook inside the enclosure and push it up through the tube just inside the right door (there's an arrow marked on it)  and keep unspooling it until it triggers the autoload.

Question: *My print will take too long. How can I make it go faster?*

Answer: There are multiple ways to make a print go faster.
- **[Reduce infill or switch infill patterns](https://help.prusa3d.com/article/infill-patterns_177130).** Most prints that don't need to bear a lot of weight or pressure will be fine with 10-20% infill. A print with less infill will print faster, and certain infill patterns will also print faster!
- **Reorient the print on the build plate to use less support material.** When using automatic supports, you'll want the largest, flattest part of the model touching the plate. The more "overhangs" you have, the more support you need. Experiment with different placements in PrusaSlicer to see which orientation produces fewer supports.
- **Separate your model into multiple parts.** PrusaSlicer has a [handy feature](https://help.prusa3d.com/article/cut-tool_1779) that can slice your model into multiple parts that you can print at different times (or with reduced supports), and you can glue the parts together after printing.
- **Increase layer height.** Prints that don't need a lot of vertical resolution/detail will print MUCH faster if you increase the height of each layer. The DMC's Prusa printers have a 0.4mm nozzle, so 0.3mm is the thickest layer height they can reliably print. You can also set [variable layer height](https://help.prusa3d.com/article/variable-layer-height-function_1750) throughout your print. 

Question: *Can I print overnight?*

Answer: Yes! But you must obtain staff permission before starting your print. Please contact Jason Charney, the Multimedia Specialist, at charney@jhu.edu for permission. 

### Printers

#### Laser Printer

The HP Color LaserJet M750 laser printer at the front desk can print in black and white or full color, single or double-sided. Fun fact: the DMC printer is (as far as we know) the only place on campus you can do 11" x 17" color laser prints. The printing cost is equivalent with printing on campus at the Libraries or elsewhere.

To print at the Front Desk, patrons can email their documents to dmcstaff@jhu.edu and pay for their prints using J-Cash, credit card, or budget code (like other consumables). Please don't print more than ~25 copies of a single document; you can direct patrons to the FedEx next door, or, if it's for a student group event, they can use the [LEED](https://studentaffairs.jhu.edu/leed/) printer upstairs in The LaB.

#### Poster Printers

##### Epson P9880
The Epson P9880 is used only with Matte paper (it's old and we need to use up all the ink!)
Here's the [latest version of the Epson poster printer PDF guide](media/HowToGuide_PosterPrinter_updated080123.pdf) that patrons can follow step-by-step.

##### Epson P9000
The Epson P9000 is used only with Luster/Glossy paper. Follow the same user guide as the Epson P9880.

##### HP DesignJet Z5600
Here's the [latest version of the HP DesignJet poster printer guide.](media/HPDesignJetZ5600.pdf)

##### Poster Printer Maintenance

[maintenance tanks and ink replacement?]

#### Inkjet Photo Printers

##### Epson P5000
Here's the [latest version of the PDF guide](media/HowToGuide_EpsonP5000Printers-updated72723.pdf) that patrons can follow step-by-step.

###### P5000 Troubleshooting
Here are some common problems that patrons run into using the P5000.

Problem: *After sending the job to the printer, the printer displays an error like "wrong paper loaded."*

Solution: Make sure that the print settings are set to feed a "cut sheet" from the "manual feed" and not "roll" or "paper cassette." Cancel and resend the print after checking these settings.

Problem: *The photo prints with strange or unexpected colors.*

Solution: Make sure that Photoshop is set to manage the colors in the print dialogue, not "printer manages colors." Double-check you have the correct paper color profile selected as well.

Problem: *Paper won't load correctly; keep getting an error after putting it in the back tray.*

Solution: The paper must be perfectly straight for it to load correctly. Don't "shove" it in but slowly shimmy it down into the slot. Look through the top lid and make sure the bottom of the sheet is touching the rollers so they can pull it into the printer evenly.


##### Canon Pixma Pro 100

[guide to printing with correct settings
- "printer manages settings" for color vs. Photoshop
- load paper in one sheet at a time
- make sure the lid is closed before pressing print]

###### Printing with Specialty Paper
The Pixma must be used for any inkjet printing that is not on photo paper. Here are the papers that the DMC sells which must be used with the Pixma:

- 5" x 7" postcard (it's too small for the P5000)
- Tattoo paper
- Sticker paper

Patrons can also bring their own paper to use, and pay the ink-only cost.

###### Pixma Troubleshooting

[won't load paper - make sure that it hits the roller. might need to angle paper a little bit]

### Roland GX-24 Vinyl Cutter

### Cricut Maker

### Brother Digital Embroiderer

### Sewing Machines

### Epson Perfection V700 Flatbed Scanner

The Epson Perfection V700 scanner is plugged into the Graphics specialty workstation. Instructions on how to use it for documents and 35mm with the Epson Scan 2 software are posted on/by the scanner itself.

---

## *Circulating Equipment Authorizations*

### Beginner DSLR Cameras
Members must attend an authorization, photo pre-orientation, or photo primer to checkout a DSLR Camera.

If members have completed the photo primer, they are Authorized to use ALL cameras available at the DMC.

When scheduling an Authorization, please remember to reserve a Camera for your appointment.

A note that all camera authorizations should also be accompanied by a [tripod authorization](#tripods)

#### Step 1: [Watch the T5i video](https://vimeo.com/191877122).

#### Step 2: "Show me" demo with DMC Staff

*This Authorization allows patrons to check out the Canon EOS Rebel T5i + EOS 90D.*

After they have watched the video, ask the patron if they have any confusion or questions regarding camera operation.

At the end of the authorization, a member should be able to demonstrate the following skills:

1. Remove/replace the battery.
2. Remove/replace the SD card.
3. Show where the USB input is and explain how to offload footage from the camera.
4. Remove/replace lens.
5. Turn camera on
6. Display white balance options.
7. Scroll through ISO, aperture, and shutter speed options.
8. Display frame rate options.
9. Record a few seconds of footage and play it back.
10. Attach the mic to the camera, turn it on, and manually change the audio levels in the camera.

Ensure patrons know the difference between a **zoom** lens and a **fixed** lens (those included in the kit) and the different on-positions for the mic. Additionally, please make sure the patron knows the difference between “Aperture Priority,” “Shutter Priority,” and “Auto.”

The 70D video is available here: https://vimeo.com/104657931 which though dated, may be helpful to patrons interested in the 90D.

### Advanced DSLR Cameras
Advanced Authorization:

*The Advanced Authorization is for patrons who want to use the: Canon EOS R8, R6, 5D, and 1D. *

#### Step 1: Watch the following videos:

https://vimeo.com/328695247

https://vimeo.com/231555244 

 
#### Step 2: "Show Me" Demo with DMC Staff
Once they’ve finished, have THEM demonstrate the following:

1. How to load/unload the battery
2. How to load/unload SD card.
3. How to change lenses and set the lens to manual focus.
4. Switching between the different focus modes, including Manual, Autofocus, Aperture Priority, and Shutter Priority.
5. Take a few photographs. Have them review the photos and delete them.
6. Set the white balance manually using the white balance card.
7. How to switch between photo and video modes.
8. How to change the image quality to RAW.

The Canon EOS R6/R8 cameras do not have authorization videos; we plan to have these created by the end of Fall 2023. In the meantime, for questions on operating the Canon mirrorless cameras, please watch https://www.youtube.com/watch?v=V4qQH94CZb0.

#### Additional Resources

If a patron has interests in camera operation and photography outside of the scope of an authorization, the following resources can be suggested to them:

[Learning Your Canon DSLR Camera](https://www.linkedin.com/learning/learning-your-canon-dslr-camera)

*Photography Resources available at the JHU Library:*

[The Manual of Photography](https://catalyst.library.jhu.edu/permalink/01JHU_INST/1lu78g9/alma991060278097407861)

[Photographer’s Eye](https://catalyst.library.jhu.edu/permalink/01JHU_INST/1lu78g9/alma991017460309707861)

[Photography: A Very Short Introduction](https://catalyst.library.jhu.edu/permalink/01JHU_INST/1lu78g9/alma991031695489707861 )

*Photo Magazines:*

[Magnum Photos](https://www.magnumphotos.com/)

[Aperture](https://aperture.org/magazine/)

*Photo Documentaries available on Kanopy:*

[Garry Winogrand: All Things Are Photographable](https://www.kanopy.com/en/jhu/video/5734738)

[In No Great Hurry: 13 Lessons in Life with Photographer Saul Leiter](https://www.kanopy.com/en/jhu/video/5346748)

 [Dorothea Lange: Grab a Hunk of Lightning](https://www.kanopy.com/en/jhu/video/132486)

[On the Net](https://www.kanopy.com/en/jhu/video/11745826)

[Leaving Home, Coming Home: A Portrait of Robert Frank](https://www.kanopy.com/en/jhu/video/5950496)

[Bill Cunningham New York: A Portrait of the Beloved Fashion Photographer](https://www.kanopy.com/en/jhu/video/5318363)

### Tripods
Every camera authorization must be accompanied by this tripod authorization if the patron is not already authorized to use the tripods!

#### Step 1: [Watch the Tripod video.](https://vimeo.com/231555948)

#### Step 2: "Show me" demo with DMC Staff

Safely attach a camera to a tripod using its quick release plate. 

***Make sure the camera and the mount plate are securely attached to the tripods and facing the correct direction on the mount.***

| Name                                | Recommended Applications                                                                                                                                                                                                                                                        |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Manfrotto 190X                      | This tripod is optimized for video, since it has a fluid head that allows for smooth camera motion. Can also be used for still photography but there are less bulky options suggested below.<br><br>**NOT for use with the Sony FS5, please use the Heavy Duty tripod instead** |
| Manfrotto Photo Tripod (with 3-Way) | This tripod is optimized for still photography, since it has an adjustable 3-axis head that provides a lot of freedom for camera placement (including portrait orientation).                                                                                                    |
| Pistol-Grip Ball Head               | This is our lightest tripod, useful for both photo and video. Has a ball head that allows for quick adjustments for photos, or relatively smooth camera movements for video.                                                                                                    |
| Manfrotto Heavy Duty Fluid Head     | This tripod is our heaviest, and is intended for use with heavy video cameras such as the Sony FS5. Not ideal for lighter cameras due to its weight and bulkiness.                                                                                                              |

### Lenses
The DMC has several specialty lenses you can attach to our camera kits (or use with your own Canon camera).

The Canon EF-series lenses are used with EOS DSLR cameras (T5i, 5D, and 1D cameras). R-series lenses are used with the full-frame mirrorless cameras (R6 and R8). The DMC's extra lenses are all EF but can be used with the R6 and R8 cameras. Adapter rings are in each of these camera kits.

#### Step 1: Check the chart for compatibility with the camera you want to use.

| Camera         | EF Lenses | EF-S Lenses |
|----------------|-----------|-------------|
| Canon T5i      | Yes       | Yes         |
| Canon 1D Mk IV | Yes       | **No**      |
| Canon 5D Mk IV | Yes       | **No**      |
| Sony FS5       | Yes       | Yes         |
| Canon R6       | Yes*      | Yes*        |
| Canon R8       | Yes*      | Yes*        |

\**Use EF-EOS R adapters included in camera kit*

#### Step 2: [Watch the authorization video.](https://vimeo.com/231555847)

#### Step 3: "Show me" demo with DMC Staff
- Show how to **remove the lens caps** and **where to store them when the lens is in use.**
- How to **put the lens on the camera.**
- Explain the **different types of lenses** and how can they tell which is which (EF vs EF-S)
- **Identify which cameras** they can use this lens with.
- How to switch from **Auto to Manual Focus** on the lenses that have that capability.
- How to **zoom the lens** on the lenses that have that capability.
- How to **clean the lens.**

### Advanced Light Kit
The [Aputure Light Storm (C120d II) LED Light Kit](https://bookit.dmc.jhu.edu/equipment/item/148382) contains three LED lights and all additional accessories needed to create a good lighting setup for photos/video.

#### Step 1: [Watch the authorization video.](https://vimeo.com/521098299)
#### Step 2: "Show me" demo with DMC Staff
1. Set up light stand
2. Adjust yoke on light to desired angle (default in parallel position to light) 
3. Attach light to stand 
4. Remove protective cover from light
5. Attach metal dome reflector hood to light
6. Attach barn doors to reflector hood (make sure to re-secure latch on barn doors)
7. Attach gel holder to barn doors and insert gel if desired 
8. Connect light to a controller box with red XLR cable and secure controller box on light stand (using straps) 
9. Attach and detach a battery (first option for power source) from the V-mount plate on the controller box - mention limitation of battery not being able to go above 95W power
10. After battery is detached, connect controller box to yellow power cable (second option for power source) and plug into outlet
11. Turn on light and adjust brightness (on controller box)
12. Demonstrate how to use and toggle between lighting effect presets (fireworks, TV, etc.)
13. Remove barn doors and reflector dome from light and attach softbox (with diffuser) -- mention how to use gel with softbox
14. Deconstruct the equipment (order: detach controller box, remove light attachments - softbox/reflector hood, cover light, detach light, adjust yoke, break down light stand)

### Sony FS5 Video Camera

### Atomos Video Monitor
The patron should arrange an appointment with a staff member well ahead of time to ensure that the necessary gear and staff will be available for the allotted time. The equipment will need to be reserved in the name of the staff member who can authorize  on the [Atomos Shogun Inferno](https://bookit.dmc.jhu.edu/equipment/item/148420) (Pro Staff only). We recommend doing this authorization in conjunction with the [Sony FS5](https://bookit.dmc.jhu.edu/equipment/item/148452) as they can be used together.

#### Step 1: [Watch the authorization video.](https://vimeo.com/282009019)

#### Step 2: DMC Staff shows you the following.
1. How to turn on and adjust the waveforms
2. How to turn on and adjust focus peaking
3. How to turn on and adjust frame guides
4. How to utilize the ATOMHDR feature
5. How to record slow motion onto the Shogun Inferno with the FS5
   
#### Step 3: "Show me" demo with DMC Staff. 
1. Remove/replace battery and show how to charge it
2. Remove/replace SSD
3. Mount to FS5/DSLR
4. Connect to FS5/DSLR with appropriate cable
5. Adjust settings on camera to get proper output to the Shogun Inferno
6. Adjust settings on Shogun Inferno to be able to see and record footage
7. Change between recording codecs
8. Format SSDs
9. Record a few seconds and playback
10. Offload footage from the SSDs.

### PA Systems
This authorization allows you to check out both the [Yamaha Stagepas](https://bookit.dmc.jhu.edu/equipment/item/147953) and the [Samson Expedition](https://bookit.dmc.jhu.edu/equipment/item/147967) portable PA systems. They function very similarly.

#### Step 1: [Watch the Yamaha PA video.](https://vimeo.com/195515763)
#### Step 2: "Show Me" demo with DMC Staff
1. **Unpack the kit, connect power and speaker cables.** Always lower the master volume when attaching/detaching cables or when powering on/off (to avoid loud POPS).
2. **Connect a microphone with an XLR cable** and a laptop or other small playback device with a 1/8" jack.
   - *Staff:* grab a vocal mic, XLR cable, and aux cable OR 1/8" TRS to 1/4" dual mono cable from the cage)
3. **Plug in** a playback device to a stereo channel, and the microphone into a mono channel. Play some music and speak into the microphone.
4. **Demonstrate adjusting levels**, both **input gain** (per channel) and **output volume** (master) 
5. *Staff:* show EQ adjustments per channel and effect/aux sends. (optional)
6. **Wrap all cables neatly** and **pack the kit back up.**
7. Recommend **speaker stands** for optimal sound quality. 

### Mixers
This authorization allows you to check out both the [Mackie 1202-VLZ Pro Mixer](https://bookit.dmc.jhu.edu/equipment/item/146927) (analog) and the [Presonus AR12c Mixer](https://bookit.dmc.jhu.edu/equipment/item/146930) (digital). The Presonus mixer also has built-in recording, digital effects, and more channels for auxiliary sends, but both mixers have the same basic functions.

1. **Plug in the mixer's power cable.**
2. **Always turn down the master volume** when attaching/detaching cables or when turning mixer on/off (to avoid POPS).
3. **Turn on** the mixer.
4. Point out **XLR** and **1/4" TRS inputs** (i.e. where to plug stuff in). 
5. Point out the **multiple outputs** (XLR and TRS), where to connect cables for **main speakers, monitors, and headphones.**
6. Point out **phantom power switch,** make sure they understand that some mics (condensers) require phantom power and some mics (dynamic) do not.
7. Explain input gain knobs for individual channels, the **individual channel output volume fader** and **master volume fader.**
8. Point out **EQ knobs** for each channel.