## Power Measurement
We built you a **Power Bench** station for hands-on testing of powered electronics. The Bench includes testers, adapters, power supplies in the power bench that come with their own instructions shared below.  The components are affordable off-the-shelf tech that you might also buy for your project.

![Power Bench image](https://i.imgur.com/y8rRf60.jpg ':class=image-25')

### Power Test Bench

For design teams to evaluate electronics & hardware power delivery, consumption, and storage.  Use the provided equipment to set up your own experiment, to measure:
1) How much power does my device use in different operating conditions?
2) Can I source power from my embedded board for an array of sensors?
3) Which battery capacity is necessary to run my system for 1 hour?

Beyond this, discover answers in your troubleshooting:
1) Is my USB cable delivering the expected voltage level?
2) Does my battery voltage drop too low when I am drawing current?
3) Is there a loss of voltage or current in my power converter?

Problems that were solved using the bench (examples):
1) A raspberry Pi resets during operation when a camera or sensor is activated.
2) The battery has sufficient capacity but the voltage is lower than expected during operation.
3) The brushless motor generates noise that interrups our signal lines.

#### Hardware

   _CAD Design files: STL to print, SOLIDWORKS to modify, or STEP to build assemblies in your own CAD software_

  * [DIN rail](https://grabcad.com/library/din-rail-36 "din rail model"), an industrial building block for electronics
  * [DIN brackets](https://grabcad.com/library/compliant-din-brackets-1 "DIN Bracket designs"), 3D-Printed and easily customize
  * [Extrusions](https://grabcad.com/library/extrusion-variants-3030-1), 30x30mm for building frames.


 #### Instruments

| Utility | Device | Link or PDF |
| ------- | ------ | ----------- |
| Power Supply, 600W | Power supply, ATX | [GX2 User Manual](https://www.thermaltakeusa.com/toughpower-gx2-600w.html) |
| Power Supply, USB 120w | 818H GaN hub |  [USB Power Supply - PDF](https://qr.page/g/51rwPdnPbKS) |
| Test & log loads | CBA by West Mountain Radio | [CBA IV User Manual](https://qr.page/g/2Gbm5eF5LD9) PDF |
| Test battery capacity | CBA by West Mountain Radio | [CBA IV User Manual](https://qr.page/g/2Gbm5eF5LD9) PDF |
| Power Meter, DC, 45A | Powerwerx | [Power Meter Manual](https://qr.page/g/40KLe1ff1lB) |
| Power Meter, AC | Amazon Product | [Power Meter, AC](https://qr.page/g/2Gz7zQ1hXL5) PDF |
| Power Meter, USB-C | Amazon Product | [Power Meter, USB-C](https://qr.page/g/2fG6cJvZi27) PDF |
  
#### Components

  * [USB-C Breakout](https://www.amazon.com/gp/product/B09KC1SMGD), on amazon
  * [USB-C PD Trigger](https://www.amazon.com/gp/product/B0B688HK9S) on amazon.
  * [Power Breakout, ATX](https://www.amazon.com/gp/product/B07S91NQL3) on amazon. 

#### Software

  Get Software  
  _Software is only necessary if you wish to use the CBA (computerized battery analyzer)_

 * [CBA IV Power Analyzer](https://www.westmountainradio.com/kb_view_topic.php?id=OT39), ► grab software for model IV

### Power Bench Instructions

* [PDF index](https://qr.page/g/2fG6cJvZi27) breaks down instructions
* [PDF queries](https://qr.page/g/1FG90ytGtOp) shows what you can test
* [PDF Example Results](https://qr.page/g/LcfYDDoNz6) shows example results
* [Video - Power Budgeting](https://qr.scuttlerobot.org/g/RkNMzfI67w) an introduction to creating a power budget (advanced).


## Battery Handling

This section is for proper handling of li-ion cells in the [SCUTTLE Robot battery pack](https://grabcad.com/library/batterypackv3-1) used in MXET300.  The notes also serve for general use of li-ion batteries and charging.

### Terminology:
SOC = state of charge
BMS = battery management system

### Cautions
The batteries are the part of the robot with the most frequent failures due to mistreatment.

The battery may be charged with any 12v power supply as the BMS will prevent excessive current.  Or, cells can be removed and charged in an off-the-shelf 18650 battery charger, for Lithium Ion Cells.

If you need to remove cells, remove them carefully and evenly so the cosmetic wrap does not tear!

When charging, the onboard battery management system (BMS) protects the cells from overcurrent. However, if the input current exceeds around 10A momentarily, the BMS will disconnect current and needs disconnection of charger to reset.  

### Charging from low SoC:

If you allow cells to drop down to low voltage (around 9.0v total) then the initial charging current may be high, and trip the BMS safety.  At low voltages, start your charging with a power supply that limits voltage (ie 10v) or limits current (ie 6A).

These cells are rated TRULY, over 3000 mAh from Panasonic - they are a leading model number in the market and not easy to order small quantities, so take care of cells at all times!

### Helpful features: 
You can charge this battery and operate your robot at the same time!  Connect your power supply to one terminal pair while running your CPU from the other terminal pair, for use cases like testing software and reading sensors, and operating the Pi for long periods.

You may check the cells by multimeter at any time (probe + and - of one cell's terminals) to verify the voltage.  There is no need to remove the cells for measurement. Cells should be balanced within 0.2 volts across the 3 cells.

You can safely charge the batteries with various reasonable sources such as 12v solar panel or a larger battery, provided the current does not exceed shutoff-threshold.  BMS shutoff does not cause damage – test your setup with good engineering planning.

The BMS offers max-voltage shutoff as well, around 14v.  If the input voltage is too high (such as fluctuating solar panel) then the BMS will shut off regardless of current.

### Damaged Cells:

If a cell has a low voltage, it is irreparably damaged.  They may survive as low as 2.8 volts momentarily but if stored below 2.8 volts you can trust the cell is ready for the recycle bin.


