# Bulk-Upload-Macros-on-Cisco-video-devices

Pyhton based Script developed using netmiko module which helps to upload macros and Extensions on CE video devices.
Netmiko module is used to SSH in device and fire API command, script then will read extension and Macro code from text files.
Please follow below steps to run script in bulk on list of CE version VC devices that supports API commands.
1) create and Save your UI Extensions in extnesion.txt file.
2) create and Save  Macro in JavaScript.txt, it doesnt needs to be JS file, you can paste code in plain text file and name it as JavaScript.txt
3) create results.txt to capture any exceptions during script execution.
4) create IP_DOWN.txt to capture Unreachable IP addresses.
5) You need to download existing extension XML file and then append new extension XML code for new button that you are trying to add.
6) 
You can use sample extension.txt and JavaScript text from repository.
