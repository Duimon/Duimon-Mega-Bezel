### **PDP-1 Spacewar! instructions.**   

Install the Mega Bezel and my presets according to the instructions on their respective threads.

[Mega Bezel](https://forums.libretro.com/t/hsm-mega-bezel-reflection-shader-feedback-and-updates/25512?u=duimon)

[Duimon_Mega_Bezel graphics & presets.](https://forums.libretro.com/t/duimon-hsm-mega-bezel-graphics-and-presets-feedback-and-updates/28146/2?u=duimon)


You will need the "Arcade (MAME - Current)" core and the hash folder from a recent version of MAME. (0.237 as of this writing.) (The MAME hash folder needs to be at "retroarch/system/mame/hash")

You will also need the spacewar.zip from the pdp1_ptp folder in the MAME Software Lists. (CRC = 8EC51506) NOT the spacewar.zip from the MAME arcade romset. (CRC = 39AC4C1C)

Create a "pdp1" folder anywhere that is convenient, (i.e. roms/pdp1) and copy the zip to it.

Run Retroarch and load the zip as content... select the "Arcade (MAME - Current)" core when prompted.

Once the content is running, load my "Advanced/PDP-1_Spacewar!/PDP1-[ADV]-[Guest].slangp" or "Standard/PDP-1_Spacewar!/PDP1-[STD]-[Guest].slangp"

**From the "retroarch/system/mame/hash/pdp1_ptp.xml"**



```plaintext
<!-- Spacewar!

Load with Ctrl-Enter


Action            Fat Ship    Thin Ship
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Turn Left         S           Right-arrow
Turn Right        A           Left-arrow
Thrust            D           Up-arrow
Fire              F           Down-arrow
Hyperspace        Z           /


Miscellaneous
~~~~~~~~~~~~~
Toggle on/off main star and its gravity: Num-6
Toggle on/off background stars: Num-4  -->
```


You can also run the visual effects demo Munching Squares, "munching.zip" (CRC = CC558E6E) from the Software Lists.

**From the "retroarch/system/mame/hash/pdp1_ptp.xml"**

```plaintext
<!-- Munching Squares

Load with Ctrl-Enter


At start, it will appear to do nothing. You need to adjust one or more
of the test-word switches (Ctrl+A/S/D/F/G/H/J/K/L/;/\/Z/X/C/V/B/N).

Ctrl+J,K or L will produce the "expected" square patterns. -->
```

Make sure to press "Scroll Lock" to enable game focus before pressing the "F" key, or Retroarch will switch to windowed mode.
