# NXP LPC1343 Return-oriented Programming Exploit

This exploit is metioned in my Blackhat Europe 2019 talk with David Oswald (Breaking Bootloaders on the Cheap):
https://i.blackhat.com/eu-19/Thursday/eu-19-Temeiza-Breaking-Bootloaders-On-The-Cheap-2.pdf

This exploit breaks the CRP-1 of the LPC1343 and also it can break CRP-1 on some other LPC devices (it may need modifications in order to work on the other vulnerable LPC devices). ONLY FOR RESEARCH PURPOSES

# How to use this exploit?
-Encode the exploit using a UU-encoding tool

-Invoke the UART bootloader

-Call the "Write to RAM" command via entering "W 268443476 172"

-Send the econded exploit to the device

For more details please refer to the Blackhat talk.
