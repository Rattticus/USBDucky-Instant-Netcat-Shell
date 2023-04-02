# USBDucky-Instant-Netcat-Shell

A simple BadUSB/USB Rubber Ducky script that uses a tiny powershell window to open a port, then download and start Netcat through that port.
Netcat is downloaded as a zip from the Nmap website to the C:\Users\Public\Libraries folder, where it is unzipped by a simple powershell tool downloaded from this repository, fce642c6-1963-4a0d-bffe-173f43f02329.zip. 
After Netcat is started, the window is moved out of view with Alt-Space + M + Down Arrow.

This script was originally tested with a Flipper Zero, so the "HOLD DOWNARROW" and "RELEASE DOWNARROW" commands on lines 42 and 44 may need changing to work on a Hak5 Rubber Ducky or other HID Attack device.
