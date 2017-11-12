///To get all the softwares and things needed to use this library blocks
You can download the IRobot Create 2 mathlab toolbox from online. This Toolbox has all the functions you will need for interfacing with IRoomba.

This is the link to download the matlab toolbox- https://www.mathworks.com/matlabcentral/fileexchange/52644-matlab-toolbox-for-the-irobot-create-2

Download wifi scanner 3.4 from the internet Below is the link http://www.softpedia.com/get/Network-Tools/Network-Monitoring/Wi-Fi-Scanner.shtml

In order to use this library you would have to have your laptop connected to your IRoomba using an Edimax nano wifi chip adapter and a WiFi to serial for the serial port on the Roomba. Below is the link for the edimax nano usb and roomba wifi-card

https://www.walmart.com/ip/Edimax-Network-EW-7811UN-Wi-Fi-N-150M-2-0-Mini-Nano-Wi-Fi-Adapter-NEW/17419471?wmlspartner=wlpa&selectedSellerId=0&adid=22222222227014437374&wl0=&wl1=g&wl2=c&wl3=40882078712&wl4=pla-78811760912&wl5=9007300&wl6=&wl7=&wl8=&wl9=pla&wl10=8175035&wl11=online&wl12=17419471&wl13=&veh=sem

http://www.robotshop.com/en/roowifi-wifi-module-roomba-v2.html?gclid=EAIaIQobChMIxb3T84r71gIVg0CGCh1Ccgo5EAYYASABEgIFiPD_BwE

Connect to your Roomba using Wi-fi scanner .Right click on the wifi name and click connect. You will know it is connected when the device youre trying to connect to is in bold font.


# project2
This project is a continuation from project 1. This includes more function and the Roomba can move and avoid obstacles. It
will simultaneously monitor the IR sensors and the temperature of the Roomba. 


Open the "project2lib" file to get the library blocks

From there copy all The blocks to a blank model space

Connect the wifi block as an input to the Temperature block and 

the Ir Block and also to the main block. Connect the temp to the main block and the ir to the main block

Run the simulation. This should move the roomba and when there is an object in front of the ir sensors it will turn 

and if all the ir sensors are blocked it will move backwards. This will also monitor the temperature of the Roomba . This

will monitor all 6 of the IR sensors on the Roomba. When there is a object blocking any of the sensos and depending on how many sensors

are blocked the Roomba will respond accrodingly. If all 6 IR are blocked, the roomba will stop and rotate 180 degrees and contnue

forward. If the right most 3 IR are blocked it will move left 15 degrees and avoid the onbstacle and then continue straight. It will

continuously monitor all the IR sensors and will move accordingly to which ever way to avoid the obstacle. 
