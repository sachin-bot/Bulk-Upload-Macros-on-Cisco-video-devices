# Bulk-Upload-Macros-on-Cisco-video-devices

Pyhton based Script developed using netmiko module which helps to upload macros and Extensions on CE video devices.
Netmiko module is used to SSH in device and fire API command, script then will read extension and Macro code from text files.
Please follow below steps to run script in bulk on list of CE version VC devices that supports API commands.
1) create and Save your UI Extensions in extnesion.txt file (You need to download existing extension XML file and then append new extension XML code for new button that you are trying to add.)
2) create and Save  Macro in JavaScript.txt, it doesnt needs to be JS file, you can paste code in plain text file and name it as JavaScript.txt
3) create results.txt to capture any exceptions during script execution.
4) create IP_DOWN.txt to capture Unreachable IP addresses.
5) create file1.txt and add list of IP addresses of VC devices that you want to bulk upload macros on (each IP on new line).
6) Run main script using python IDLE or pycharm or you can create exe and run it.
7) ENter admin or integrator username and password when prompted for the codecs.
8) when prompted to extension, enter command "xCommand UserInterface Extensions Set ConfigId: webexdialer" (name of the dialer here of your choice I have set this to webexdialer)
9) when prompted to enter macro  "xCommand Macros Macro Save Name: webexdialer Overwrite: True Transpile: False"
10) when prompted to activate macro  "xCommand Macros Macro Activate Name: webexdialer"





Disclaimer::
This example is only a sample and is NOT guaranteed to be bug free and production quality.

This examples Illustrate how to  upload Macros in Bulk on CE version video devices of Cisco.



