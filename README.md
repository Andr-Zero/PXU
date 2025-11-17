
# PXU - Replacement Power Supply for the Orignial Xbox!

## 🛑 VERY IMPORTANT SAFETY DISCLAIMER 🛑
This project involves working with and replacing a power supply unit that was originally designed to handle mains voltage. The original OEM power supply can retain a lethal electrical charge long after it has been unplugged. Proceed with extreme caution.

 **HIGH VOLTAGE RISK**: You are solely responsible for your safety. Improper handling of electronics can lead to serious injury, death, or fire. If you are not experienced and confident in working with electronics, do not attempt to install this hardware.

**USE AT YOUR OWN RISK**: This is a hobbyist project provided "as is" without warranties of any kind. The author, Andr0, is not responsible for any damage to your console, other property, or any personal injury that may occur from the use or misuse of this hardware.
___
## Features
-   ✨Support 1.0 through 1.6 revisions consoles! ✨  
    *1.0/1.1 requires the proper 12-pin connector.  
    *Switching between 1.0-1.4 and 1.6s requires changing several zero ohm resistors, documented on bottom of the PCB.
-   Accepts any DC input from 16-20V, 100W+ (Including 100W USB-C PD chargers).
-   Features user-replaceable input modules.
-   Designed as a direct swap with the OEM power supply, using the same mounting points.

## Installation
**Warning:** The OEM power supply can be dangerous even after being unplugged for long periods. Proceed with caution!

1.  **Make sure the AC power cord is unplugged from the wall!** Then, press the Xbox's power button a few times to help discharge any residual power.
2.  Open the console and remove the hard drive tray.
3.  Unplug the cable connecting the OEM power supply to the mainboard.
4.  Remove the two screws holding the power supply down. Slide it toward the front of the console just enough to disengage it from the shell's retaining clips.
5.  The power supply should now lift out. You may need to angle it to get it out of the shell.
6.  Installation is the reverse of this process.


## FAQ
**Will my "******"  work as a power source?** I cannot test every power source available. I have personally tested an MSI laptop charger (180W) and an Anker 100W USB-C charger. Similar adapters that meet the specification of 16-20V and can deliver 100W or more should work.

**Can you add feature "X"?** The goal of the main PXU board is to be a drop-in replacement that powers the console just like the OEM supply. Additional features can and should be added as daughterboards using the provided mount points.

**I dont see the USB-C Board Here.** That's in another repo: https://github.com/Andr-Zero/PXU-C-PIM

## License

This project is open-source hardware, licensed under the **CERN-OHL-S v2** (CERN Open Hardware Licence - Strongly Reciprocal).

**Copyright © 2025 Andr0**

You are free to:

-   **Use and reproduce** this design for any purpose.
-   **Modify** the design to fit your needs.  
-   **Distribute** the original design or your modifications.
    

In return, you must:

-   **Give credit**
-   **Share your changes** under the same CERN-OHL-S v2 license.
-  **Keep all copyright and license notices intact.** As a condition of the license's attribution requirement, all original markings on the PCB silkscreen must be retained. This includes the copyright notice, the PXU and Team Resurgent logos, and any project URLs present in the original design files. These should not be removed or altered.
