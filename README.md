# Ender3
Supercharge your Ender3 with Guides, Mods and Addons.
Make your Ender3 work and worth like high end machines.

**Note:** I have spend many hours trying put this together so you can supercharge your Ender-3 for "Free", if my work is important to you or you fell this worth a tip i'm open to donations: https://www.paypal.me/SkillTournament

Discussion Groups:
* https://www.facebook.com/groups/Ender3/


## 1. PrusaSlicer

These profiles are based on a quality/speed balance (Universal).
Good prints without sacrifice the speed.
Make sure you have a good leveled printer and bed.

**NOTE:** Fine tune the start gcode for your printer! This is very important since i can't provide a all case profile for every modification and printer.

Modify at your needs.

### 1.1. Instalation
1. Download and install PrusaSlicer from: https://www.prusa3d.com/prusaslicer/
2. Start and configure PrusaSlicer (Wizard)
3. Close PrusaSlicer
4. On different operating systems open:
   * Windows: "%AppData%\PrusaSlicer\", if not exists try: "C:\Users\Public\Documents\Prusa3D\Slic3r settings xxxx"
   * macOS: "/Users/[Username]/Library/Application Support/PrusaSlicer"
   * Linux: 
      * Stable build: "~/.PrusaSlicer/"
      * Alpha build: "~/.PrusaSlicer-alpha/"
5. Copy GitHub PrusaSlicer subfolders ("printer", "filament", "print") to the folder above
7. Open PrusaSlicer and check if profiles are there
8. To clean up interface remove profiles that you will not use: Printers you will not use (OPTIONAL)
9. Go under printer and use your current values for your printer, like max Z, limits, start gcodes or other things you may need to tune
10. Do a simple test print

### 1.2. Ender3 Bed model into slicer

1. For the different operating systems:
    * Windows: Copy "ender3_bed.stl" to instalation directory, often at "C:\Program Files\Prusa3D\PrusaSlicer"
    * macOS: 
        1. Copy "ender3_bed.stl" to "/Applications/[User]/[PrusaSlicer-version_number].app/Contents/Resources/models" if you got the software from Homebrew Cask or "/Applications/[User]/Original Prusa Drivers/PrusaSlicer.app/Contents/Resources/models" if you got it from the manufacturer website. You can access the folders inside the .app contents by right clicking the .app file and choosing "Show package contents".
        2. Start the software and go to the "Printer" tab. Make sure you're viewing the correct profile by choosing it from the dropdown list on the upper left. Then click on "Expert" on the top right corner and after that, click on "Set" next to "Bed Shape· on the first line. In the new window, click the "Load..." button in the "Model" section.
        3. When the Finder window opens to choose the model file, press "Cmd + shift + G" to open the "Go to the folder" dialog, and type the path used in step one. Then press Enter and choose the model file.
        4. If you remove the application, you will have to follow these steps again since the model will be removed along with the package.
		
"ender3_bed_alt.stl" is cut at bed height to improve the overview from top on slicer, if you want to use this instead, copy to slicer directory and rename it to "ender3_bed.stl".

Taken from: https://www.thingiverse.com/thing:3873312

## 2. Hardware

### 2.1. Best parts store:

* **Trianglelab:** https://trianglelab.aliexpress.com/store/1654223
* **Funssor:** https://www.aliexpress.com/store/115344

### 2.2. Recommended Hardware:

**Note:** Somes parts can override others! Study first what you want or need to buy.

* Cloned Bondtech BMG extruder for direct drive or better bowden: https://www.aliexpress.com/store/product/trianglelab-Bowden-Extruder-BMG-extruder-Cloned-Btech-Dual-Drive-Extruder-for-3d-printer-High-performance-for/1654223_32917029058.html
* V6+Volcano 1.75mm 24V: https://www.aliexpress.com/store/product/Trianglelab-v6-Volcano-hotend-12V-24V-remote-Bowen-print-J-head-Hotend-and-cooling-fan-bracket/1654223_32844080369.html
* Volcano Nozzles (1.75 Full Size Kit): https://www.aliexpress.com/store/product/trianglelab-Top-quality-V6-volcano-Nozzle-for-3D-printers-hotend-5pcs-lot-volcano-upgrade-kit-for/1654223_32839344108.html
* Volcano Sock: https://www.aliexpress.com/item/Funssor-1pcs-Volcano-Heater-Block-Silicone-Socks-PT100-cartridge-Type-Silicone-Insulation-Sock-SILICONE-HEATER-BLOCK/32841090475.html
* Extruder gear: https://www.aliexpress.com/store/product/trianglelab-Drivegear-kit-dual-drive-gear-extruder-kit-Cloned-Btech-upgrade-for-Prusa-i3-3d-printer/1654223_32904209624.html
* MK8 Metal Extruder: https://www.aliexpress.com/item/Upgrade-3D-Printer-Parts-MK8-Extruder-Aluminum-Alloy-Block-bowden-extruder-1-75mm-Filament-for-creality/32834380573.html
* 3D Touch: https://www.aliexpress.com/store/product/Trianglelab-2018-NEW-3D-Printer-3D-TOUCH-SENSOR-Free-Shipping-Auto-BED-Leveling-Sensor-for-anet/1654223_32840691571.html
* BLTouch board adaptor: https://www.ebay.co.uk/itm/CR-10-Ender-3-Pin-27-Board-for-BL-Touch-Autobed-Levelling-or-filament-sensor/173475394925?hash=item2863f0756d:g:rpkAAOSwzXxaHscB
* TL Smoother Plus: https://www.aliexpress.com/store/product/Trianglelab-4-pieces-pack-TL-smoother-PLUS-addon-module-for-3D-pinter-motor-drivers-motor-Driver/1654223_32841473812.html
* NEMA 17 Dampers: https://www.aliexpress.com/item/Funssor-12pcs-lot-NEMA-17-Steel-Rubber-Stepper-Motor-Vibration-Dampers-Imported-genuine-42-stepper-motor/32825669027.html
* Official Glass Bed Surface: https://www.aliexpress.com/item/Newest-Creality-3D-Printer-Ender-3-Black-Carbon-Silicon-Crystal-Glass-Platform-Build-Hotbed-Glass-Platform/32890715441.html
* Bed Springs (4x): https://www.aliexpress.com/item/4-pcs-CREALITY-3D-Printer-Parts-Spring-For-Heated-bed-CR-10-CR-10Mini-CR-10S/32864621140.html
* Bed Isolator (300x300): https://www.aliexpress.com/item/3D-Printer-Part-Heated-Bed-Thermal-Insulator-Cotton-Heat-Insulation-Mat-for-Heatbed-Aluminum-Pad-PCB/32879628172.html
* 5015 24v Fan: https://www.aliexpress.com/item/2PCS-Gdstime-2-Pin-Ball-Bearing-DC-24V-Brushless-Cooling-Turbine-Blower-Fan-5015/32841967974.html
* 4010 24v Fan: https://www.aliexpress.com/item/2Pcs-DC-24V-40mm-x-40mm-x-10mm-2-Pin-Ball-Bearing-Computer-PC-Case-Silent/32727867521.html
* Fan speed controler: https://www.aliexpress.com/item/10pcs-lot-PWM-DC-6V-12V-24V-28V-3A-Motor-Speed-Control-New-Switch-Controller-1203B/32714571858.html
* Extreme v wheels (16x): https://www.aliexpress.com/item/High-precision-CNC-clear-Polycarbonate-Xtreme-v-wheel-kits-for-Openbuilds-v-slot-linear-rail-system/32849105844.html
* Belt Tensioner: https://www.aliexpress.com/store/product/Funssor-upgrade-Aluminum-alloy-Tornado-CR-10S-X-Axis-Tensioner-kit-For-Creality-cr-10-Ender/115344_32882354827.html
* XT30 Connectors: https://www.aliexpress.com/item/10pcs-Amass-XT30-Male-Female-Bullet-Connector-Plug-For-RC-FPV-Lipo-Battery-RC-Quadcopter-5/32784217001.html
* Arduino Uno for Stock motherboard bootloader burn: https://www.aliexpress.com/item/high-quality-One-set-UNO-R3-CH340G-MEGA328P-for-Arduino-UNO-R3-NO-USB-CABLE/32697443734.html
* Raspberry Pi 3+ with Octoprint and PiCamera

## 3. Printed Parts

### 3.1. Colections

* **sn4k3** https://www.thingiverse.com/sn4k3/collections/creality-ender-3
* **Nerys** https://www.thingiverse.com/Nerys/collections/ender-3
