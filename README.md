## ElegantRTSS

This is a heavily customized fork of an older version of [ElegantMustard](https://github.com/lscambo13/ElegantMustard).

### Preview
![image](https://github.com/user-attachments/assets/229fd1f2-d803-4960-833a-eaa54b1616c3)

### Installation
1. Open MSI Afterburner
2. Navigate to Settings
3. Go to the Monitoring tab
4. In the Monitoring tab:

   a. Select the first option

   b. Scroll all the way down

   c. Shift+Click the last option

   d. Press the checkmark on the left to enable all options

5. Open Rivatuner Statistics Server
6. Go to Setup
7. Navigate to Plugins
8. In the Plugins section:

   a. Double-click OverlayEditor.dll
   
   b. Press Layouts > Import
   
   c. Import the ovx file

To get the 1% and 0.1% lows counting properly, you need to go into RTSS and do the following:
1. Open Setup
2. In the Statistics Properties subsection:

  - Change Percentile Buffer from Unlimited to Ring

3. In the Compatibility Properties subsection:

  - Check the "Enable benchmark mode" box
