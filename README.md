# Bulk-Upload-Macros-on-Cisco-video-devices

Script is developed using netmiko module of python to avoid manual efforts to upload macros on CE video devices.
Netmiko us used to SSH in device and fire API command to add Macro, script then will read extension and Macro code from text files.
Save your UI Extensions in extnesion.txt file.
Save  Macro in JavaScript.txt, it doesnt needs to be JS file, you can paste code in plain text file and name it as JavaScript.txt
You can use sample extension.txt and JavaScript text from repository.
