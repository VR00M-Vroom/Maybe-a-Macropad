---
Title: MacroPAD
Author: Varun Heblikar U0940ULSU15
Description: I wanted to make kiCad easier to use by making a macropad and coding it in KMK.
Created On: 8/10/25
---

# August 10th
The seeds of my idea  havebeen planted in the form of the schematic. The idea was to make 9 key macropad with a I2C Display. The microcontroller would be a Seeed Studios Xiao RP2040
as the MCU. Then there would be 9 lights for each button.
I have just got into the designing part and cant find the right footprint for the leds and the right footprint for the I2C display... Oh how I hat importing files into kicad.
Most of the schematic is done but I chose the wrong I2C display module which makes it even more frustrating since im 2hrs in alr. Hope is all I can last on now... Probably DM soemone about the problem in slack
<img width="707" height="620" alt="Screenshot 2025-08-04 193013" src="https://github.com/user-attachments/assets/32f6d155-79fb-45c9-a925-81902148c69f" />
<img width="575" height="184" alt="Screenshot 2025-08-04 203414" src="https://github.com/user-attachments/assets/e96e1f88-8c67-41d0-a0fa-8beac5bcf9f3" />
Time Spent ~3hrs 

# August 13th
The grind begins.
I got a Dm back from someone who gave me the footprint and the symbol for the display which saved me another five hours. I mean 5 hrs to download a kicad file is wild.
Anyways the projects file for the led was still horribly wrogn and took me an hour to figure out. The schematic changed from 9 to 6 leds and 8 switches. The 8 switches was fora cleaner alignment and different layout. The led matrix was a idea still in progress but it was none the less progress on my behalf.
<img width="744" height="624" alt="Screenshot 2025-08-04 203536" src="https://github.com/user-attachments/assets/8f451341-65fd-4f89-947e-5ff56d048ccd" />
Time ~2.7 hrs

# August 15th
The train is back on track, and I have Finished routing the PCB. There were no major Issues with the routing and PCB execpt for the 12 vias i needed for 3 traces..
Anyways I popped it into the slack to check if there were any errors and I will now go to sleep. Tommorow is going to be for final touches.
<img width="744" height="624" alt="Screenshot 2025-08-04 203536" src="https://github.com/user-attachments/assets/c8a5d69c-291f-4e39-b121-c13398d15c94" />
<img width="1081" height="620" alt="Screenshot 2025-08-14 230142" src="https://github.com/user-attachments/assets/3de04c9c-aaa4-4c97-8aaa-64ec25ae8f95" />

# August 16th
I thought I was finished with my PCB and design but really i was not. This was to blame the LED that I had added to add some flair to my project which was bad. It ended up being the cuase of my downfall or so I thought. I had to test it on a breadboard with an arduino to make sure that I wasn't tweakingou or anything but it was fine so I'll probably finish tommorow if i get the time to. Now I just have to fix the routing...
Its 11:45 and I have fixed the traces and I am dead tired. The Pcb was soo hard to route and I don't want to do that again.

<img width="635" height="779" alt="Screenshot 2025-08-16 225241" src="https://github.com/user-attachments/assets/7aeaf7c8-3238-4ffa-bfcc-d8e7fd833376" />
<img width="655" height="791" alt="Screenshot 2025-08-16 114311" src="https://github.com/user-attachments/assets/03962b64-cac1-4c00-9d2f-e6ccd6c1abaf" /> OLD
<img width="445" height="588" alt="Screenshot 2025-08-16 234413" src="https://github.com/user-attachments/assets/98828cfd-906d-4560-a96d-729e016b3341" /> NEW
Time Spent 6hrs

# August 17th
The time ticks...
Today I just found out that the leds may blink erratically if i just ship it as is so I need to find an alternative for it. _
I changed from a led matrix to a encoder. This also took a while to figure out but I think Im ready to ship.

<img width="482" height="206" alt="Screenshot 2025-08-17 093031" src="https://github.com/user-attachments/assets/06a696c9-f440-449f-ba9c-d62af5030de0" />
<img width="828" height="581" alt="Screenshot 2025-08-17 093041" src="https://github.com/user-attachments/assets/53acbd8b-3a6a-4261-b82b-aa8cc265909e" />
<img width="593" height="790" alt="Screenshot 2025-08-17 132323" src="https://github.com/user-attachments/assets/d72ea35b-015c-4922-be2c-760e81dd501c" />
<img width="889" height="594" alt="Screenshot 2025-08-17 133157" src="https://github.com/user-attachments/assets/e7136e86-fc9f-4e42-aa13-ce5b4cacd839" />
<img width="445" height="588" alt="Screenshot 2025-08-16 234413" src="https://github.com/user-attachments/assets/619c8f2a-10a7-45ab-87dd-3a7615526443" />
time spent 4hrs

