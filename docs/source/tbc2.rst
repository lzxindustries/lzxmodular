TBC2
===============

.. figure:: lzxart/TBC2Frontpanel.PNG
   :height: 600
   :alt: TBC2 Dual Decoder & Time Base Corrector frontpanel

TBC2 is a dual video input module for your LZX modular system.  Supported are Composite, Component & S-Video inputs capable of SD/HD video decoding and frame synchronization. 

- SD/HD Video Sync Generator supporting NTSC, PAL, 480p, 576p, 720p50, 720p5994, 720p60, 1080i50, 1080i5994, 1080i60, 1080p2398, 1080p24, 1080p25, 1080p2997, 1080p30 sync formats
- Dual SD/HD Video Decoders supporting NTSC, PAL, 480p, 576p, 720p50, 720p5994, 720p60, 1080i50, 1080i5994, 1080i60, 1080p2398, 1080p24, 1080p25, 1080p2997, 1080p30 input sources 
- VESA/VGA input up to 1024x768 with optional 10HP VGA+SCART expander.
- Playback of still images and looping sequences loaded from frontpanel MicroSD card slot
- Adjustable frame delay  
- Color correction controls for each input: Hue, Saturation, Contrast & Brightness
- Auto upscaling and downscaling modes for each input: Fit, Crop, Stretch & Bypass
- MIDI input for remote parameter control

:HP: 16
:Power Consumption +12V: 550mA

MicroSD Card Compatibility
-----------------------------

TBC2 is compatible with some, but not all MicroSD cards.  When you acquire a MicroSD card to use with TBC2, we recommend selecting from the specific brands and models we have tested to be hassle free, listed below. Always purchase MicroSD cards from a trusted vendor with name brand packaging to protect yourself against counterfeits.

+------------------+-----------+
| Brand / Series   | Size      | 
+==================+===========+
| SanDisk          | 8GB, 16GB | 
+------------------+-----------+
| SanDisk EDGE     | 8GB       | 
+------------------+-----------+

MIDI Control Change Map
-----------------------------

+---------+--------------+-------------------------+
| CC      | Module       | Parameter               |
+=========+==============+=========================+
| 0       | Encoder A    | Crossfade               |
+---------+--------------+-------------------------+
| 1       | Decoder A    | SD Processor Hue        |
+---------+--------------+-------------------------+
| 2       | Decoder A    | SD Processor Saturation |
+---------+--------------+-------------------------+
| 3       | Decoder A    | SD Processor Brightness |
+---------+--------------+-------------------------+
| 4       | Decoder A    | SD Processor Contrast   |
+---------+--------------+-------------------------+
| 16      | Encoder B    | Crossfade               |
+---------+--------------+-------------------------+
| 17      | Decoder B    | SD Processor Hue        |
+---------+--------------+-------------------------+
| 18      | Decoder B    | SD Processor Saturation |
+---------+--------------+-------------------------+
| 19      | Decoder B    | SD Processor Brightness |
+---------+--------------+-------------------------+
| 20      | Decoder B    | SD Processor Contrast   |
+---------+--------------+-------------------------+

Firmware Releases
-----------------------------

+-----------+---------------------+-------------------------------------------------------------------------------------+
| Version   | Release Date        | Download                                                                            |
+===========+=====================+=====================================================================================+
| 1.0       | 01.04.2023          | firmware/TBC2_Firmware_1.0.zip                                                      |
+-----------+---------------------+-------------------------------------------------------------------------------------+

Firmware Update
-----------------------------

1. Download the latest firmware package from the releases section, and unzip the files.  Find BOOT.bin and copy it to your MicroSD card.
2. Power down your TBC2 and insert the MicroSD card.
3. Power on your system and wait for TBC2 to finish booting, then activate the Update Firmware button on  the System page.
4. Wait for firmware update to complete, until you see the System Restart prompt.  Activate the Confirm button to restart your system.
5. Confirm that your TBC2 boots to the correct version by comparing version numbers on the System Page.  Power off / power on your system if you see the wrong version initially. 

Factory Reset
-----------------------------

1. To reset your TBC2 firmware to the version shipped from the factory, activate the Reset Firmware button on the System page.
2. Wait for firmware reset to complete, until you see the System Restart prompt.  Activate the Confirm button to restart your system.
3. Confirm that your TBC2 boots to the factory installed version by comparing version numbers on the System Page.  Power off / power on your system if you see the wrong version initially. 


