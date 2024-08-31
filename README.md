## ElegantStatistics

This is a heavily customized fork of an older version of [ElegantMustard](https://github.com/lscambo13/ElegantMustard).

### Preview
![image](https://github.com/user-attachments/assets/229fd1f2-d803-4960-833a-eaa54b1616c3)

### Installation
1. Download the ovx file you want from the repository
2. Open MSI Afterburner
3. Navigate to Settings
4. Go to the Monitoring tab
5. In the Monitoring tab:

   a. Select the first option

   b. Scroll all the way down

   c. Shift+Click the last option

   d. Press the checkmark on the left to enable all options

6. Open Rivatuner Statistics Server
7. Go to Setup
8. Navigate to Plugins
9. In the Plugins section:

   a. Double-click OverlayEditor.dll
   
   b. Press Layouts > Import
   
   c. Import the ovx file

To get the 1% and 0.1% lows counting properly, you need to go into RTSS and do the following:
1. Open Setup
2. In the Statistics Properties subsection:

  - Change Percentile Buffer from Unlimited to Ring

3. In the Compatibility Properties subsection:

  - Check the "Enable benchmark mode" box
