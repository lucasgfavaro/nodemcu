# nodemcu
NodeMCU examples

# Windows Install

Windows Drivers Download: https://www.silabs.com/documents/public/software/CP210x_Universal_Windows_Driver.zip

Right click over silabser.inf and select install

# Arduino IDE Install

Select File > Preferences from the Arduino IDE menus.
Enter the following URL into the "Additional Boards Manager URLs" field: https://arduino.esp8266.com/stable/package_esp8266com_index.json
:exclamation: If there are already Boards Manager URLs in the field, separate them with commas.

Click the OK button.

You will now see a "Downloading index: ..." notification at the bottom right corner of the IDE window. Wait for that notification to close.

Select Tools > Board > Boards Manager from the Arduino IDE menus to open the "Boards Manager" view in the left side panel.

Scroll down through the list of boards platforms until you see the "esp8266" entry.
Click the "INSTALL" button at the bottom of the entry.
Wait for the installation to finish.
You should now see the boards of the installed platform under the Tools > Board menu in Arduino IDE.
