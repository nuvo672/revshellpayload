----------------------------------
[Hoaxshell]: https://github.com/t3l3machus/hoaxshell
# Reverse Shell Payload Setup for Raspberry Pi Pico
This repository provides a convenient method to set up your Raspberry Pi Pico as a Rubber Ducky device using the Hoax Shell reverse shell payload.

Please refer to this repository: [Hoax Shell Reverse Shell Payload][Hoaxshell]



## Setting Up Your Raspberry Pi Pico
1. ### Flash Nuke and Adafruit Firmware

In Nuke&Ada, upload the "flash_nuke" firmware, followed by the "adafruit" firmware to your Raspberry Pi Pico.

2. ### Copy HID Files

Navigate to the "HID" directory in this repository.
Copy all files from the "HID" directory.
Paste these files into the "lib" directory of your Raspberry Pi Pico.

3. ### Copy Main Files

Navigate to the "main" directory in this repository.
Copy all files from the "main" directory.
Paste these files into the root Raspberry Pi Pico folder.

4. ### Your Raspberry Pi Pico is Now Ready!

## Loading the Reverse Shell Payload
1. ### Prepare Your Payload Script

Open a text editor or Notepad.
Copy the contents of the "revshell.txt" payload script from this repository.

2. ### Customize Your Script

Replace "{Hoaxshell revshell}" with your actual Hoax Shell reverse shell script.
Adjust DELAY times as needed for your specific use case.

3. ### Save the Payload

Save the file as "payload.dd" in the root directory of your Raspberry Pi Pico.
With these steps completed, your Raspberry Pi Pico is set up as a Rubber Ducky device, and the reverse shell payload is ready to execute when connected to a target system.
