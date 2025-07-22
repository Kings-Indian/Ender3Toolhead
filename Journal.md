---
title: "Ender3Toolhead"
author: "Tanishq"
description: "This is an advanced toolhead designed around an ender 3"
created_at: "2025-05-28"
---
## I Decided the Scope of My Project

- It will be on a 300 mm Stainless Steel MGN12H Linear Guide. Linear rails are stiffer, more precise, and simpler to mount than linear rods, reducing backlash and ringing artifacts in 3D printing. Unlike rods, a single rail can achieve linear motion without rotation, making setups lighter.
- It will rely on direct drive extrusion. This is due to its more consistent extrusion and lack of slipping.
  - **2a.** It will contain dual gear extrusion. This is due to its lack of slippage.
  - **2b.** It will most likely be based around the ProtoXTruder but modified to have the advantage of a Sherpa Mini's dual gear. Other extruders like the Orbiter were considered, but due to price and difficulty in manufacturing (I plan to print it, and the planetary may be difficult to make and expensive with bought parts) aren't likely to be used.
- Cooling will likely have a 2510 fan on the hotend and two 5015s on the nozzle.
- The Hot End will most likely be a Dragon Hotend UHF due to its impressive flow rate of 70.5 mm³/s.

### 5/28/2025 - 1 hours spent
### 6/29-30/2025 - So I forgot to commit so everything got deelelted but heres a rundown opf the p[ast few days:

1. Im using a lancer long with a  CHT Volcano Nozzle. <img width="610" height="696" alt="image" src="https://github.com/user-attachments/assets/e57756fc-0448-4793-b0b8-577a360abb73" /> <img width="1075" height="784" alt="image" src="https://github.com/user-attachments/assets/e2f5b49b-0e2d-49c0-a956-1b319651f213" />
<img width="1336" height="835" alt="image" src="https://github.com/user-attachments/assets/ebbeb340-757d-4472-baf6-72e448dad283" />
<img width="1126" height="992" alt="image" src="https://github.com/user-attachments/assets/21db17d4-3e95-42b1-829f-5475136b276b" />
for the cooling ill use a 301 fan on the hotend and a cpap fan on the tip

<img width="489" height="534" alt="image" src="https://github.com/user-attachments/assets/d382d9d3-a37c-49b7-9207-eb12ab044933" />
Time spent: 10 hours 
6/31/2025:

I decided the following changes:

1. I will add a skr mini e3v3board to make it quiter and improve performance. I also need it for the Independent Fan Control
2. Ill switch out the CR touch with a btt microprobe, a mroe accurate touch probe
3. I will add a ebb36 board
4. I will route the cpap fan bettter by making it on the back and using vzbot ducts

ill start by designing the beginnings and ends of the ducts. I will then likely connect them, put the ebb36 board below the belt tensioner, and then but a microprobe on the front middle. 
<img width="875" height="705" alt="image" src="https://github.com/user-attachments/assets/77fea19e-3fb0-431f-8291-c543cf931968" />

<img width="688" height="607" alt="image" src="https://github.com/user-attachments/assets/ce2f3741-420c-4e0a-beb5-9a8823702816" />

optimally I have the same volume as the input all the way/2 since I split it. 9.5^2*pi/2=#ductz* the y length. <img width="402" height="362" alt="image" src="https://github.com/user-attachments/assets/4fd5f913-8032-48b3-aa5b-562dce246fcb" />

Time spent: 3.5h
<img width="686" height="604" alt="image" src="https://github.com/user-attachments/assets/f45b26ce-ff07-4d07-9c5f-fd03dfe04cef" />
Having a lot of t rouble with lofts 😭this is the best I got it
time spent: 5h
