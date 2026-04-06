**RoveSoPickNPlace GRBL Firmware**

Uses [GRBL-Mega-5X firmware](https://github.com/fra589/grbl-Mega-5X) by fra589 on an Arduino Mega to control an automatic pick and place machine. This is our configuration of the firmware and GRBL configuration.

Drag and drop the grbl folder into Arduino/libraries folder. Open the example in Arduino IDE and upload to the Arduino Mega. Do not edit the grblUpload.ino file in Arduino IDE or the firmware breaks. If you change the firmware, remember to send "$RST=*" to reset to the defaults or the GRBL might behave strange.