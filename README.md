This is a guide to reflash bios via pendrive (bricked or not bricked) 
lenovo h520g and similar (must find the correct bios in this case)

Esse é um guia para recuperar a bios corrompida pelo pendrive, sem solda somente com pendrive

1- Download bios MS-7687 VER 4_2  4m.BIN<br><br> https://cdn.discordapp.com/attachments/960567358395670608/1021749555169075200/MS-7687_VER_4_2_4m.BIN 
2- Delete all data + format USB to fat32(nothing else)<br><br>
3- COPY PASTE MS-7687 VER 4_2  4m.BIN TO THE PENDRIVE<br><br>
4- remove power cable<br><br>
4.1 - Disconnect HD/ cd/dvd/ all peripherics, except pendrive (ethernet cable, wifi card etc)<br><br>
5- Move the TWO Jumpers CMOS_CLR from pin 1-2 to pin 1-3<br><br>(cmos battery was there and did not influence the result for me)<br><br>
6- insert pendrive on usb 3.0 port(you can try other ports but try 3.0 first <br><br>
6.1 - Must be connected only pendrive, nothing else<br><br>
7- turn on AND WAIT AROUND 10 to 15 minutes<br><br>
7.1- DO NOT TOUCH ANYTHING<br><br>
8 - CHECK PENDRIVE LIGHTS<br><br>
9 - When COMPLETE, The machine will Shutdown AUTOMATICALLY <br><br>
10 - DISCONNECT  power cable + Pendrive <br><br>
11- change CMOS_CLR pin to 1-2 again <br><br>
12- Attatch everything + cables + vga etc<br><br>
13- PC WILL BOOT AGAIN ALIVE
