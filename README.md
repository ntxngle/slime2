# slime2
## What and Why

A ESP8266 based SlimeVR tracker with all of the features of the much bigger and cumbersome official/DIY ones.

A friend introduced me to these trackers by building his own. He had purchased the many modules off of aliexpress and him, a friend, and myself gathered at my house to solder them. Apart from the legendary "soldering party" (fumes included) that subsequently happened, we managed to solder together the modules on a carrier board, with the occasional wire jumper when things went wrong. To me, the whole project seemed silly. Why buy IMU, Devboard, and charging modules when all of these can be integrated on one board? Cost for one. But with a little skill you can drastically reduce price by soldering it yourself. Thus began the development of slime2.

It's important to note that there are many like it. But this one is mine. VR and full body tracking attracts many CS types (for worse, not better), and thus many people have tried (and succeeded) to build custom trackers/modules/carriers etc. Regardless, many aimed for the degenerate maximization of battey life to support their double digit hour sessions, and not size. I am doing the opposite. 

Another important execption: it uses Wifi. There are slimevr trackers that use ESB on nRF modules that are the same size and last 10x longer, but are 10x as expensive.

As as result, I present the Wifi SlimeVR tracker with an area 13% than that of a credit card. 

## Tuff photos

<img width="1008" height="846" alt="image" src="https://github.com/user-attachments/assets/bd1577b1-bc4e-4940-b9a8-f77abdedef0e" />
<img width="951" height="649" alt="image" src="https://github.com/user-attachments/assets/e9434ef2-5839-4312-a10d-28b77297f5b5" />
<img width="828" height="717" alt="image" src="https://github.com/user-attachments/assets/34d5001c-8703-49bb-a131-4a23b7457d74" />
<img width="544" height="834" alt="szine" src="https://github.com/user-attachments/assets/42956c98-fa22-4109-bedf-10fb0ed4439d" />
<img width="1240" height="976" alt="image" src="https://github.com/user-attachments/assets/9e710ca5-8a13-44f5-a445-2964b4363319" />
<img width="1188" height="549" alt="image" src="https://github.com/user-attachments/assets/95f4ec28-2dad-4400-9306-35b70b265ca5" />


## How it works

It uses SlimeVR firmware extactly like the normal trackers, and interfaces with pretty much the same hardware/pins, it's just that instead of being modules connected to modules, everything is already mounted to PCB.

## BOM
This bom makes one tracker. repeat as needed.

|Name            |Quantity|Footprint                             |LCSC Id  |Cost (with MOQ)|
|----------------|--------|--------------------------------------|---------|---------------|
|PCB             |1       |                                      |         |2              |
|Battery         |1       |                                      |         |6              |
|Strap           |1       |                                      |         |7.40           |
|SOICbite clip   |1       |                                      |         |0.99           |
|10k             |5       |R_0402_1005Metric                     |https://www.lcsc.com/product-detail/C60490.html   |0.13           |
|2.2k            |2       |R_0402_1005Metric                     |https://www.lcsc.com/product-detail/C2906865.html |0.16           |
|ESP-WROOM-02    |1       |ESP-WROOM-02                          |https://www.lcsc.com/product-detail/C81770.html   |1.60           |
|HX MINI MSK12CO2|1       |SW-SMD_MSK12CO2                       |https://www.lcsc.com/product-detail/C5149840.html |0.77           |
|MCP73831-2-OT   |1       |SOT-23-5                              |https://www.lcsc.com/product-detail/C424093.html  |0.78           |
|ICM-45686       |1       |LGA-14_3x2.5mm_P0.5mm_LayoutBorder3x4y|https://www.lcsc.com/product-detail/C22459454.html|5.26           |
|180k            |1       |R_0402_1005Metric                     |https://www.lcsc.com/product-detail/C25760.html   |0.11           |
|HT7833          |1       |SOT-89-3                              |https://www.lcsc.com/product-detail/C50936.html   |1.66           |
|0.1uF           |5       |C_0402_1005Metric                     |https://www.lcsc.com/product-detail/C100072.html  |0.34           |
|LED             |2       |LED_0402_1005Metric                   |https://www.lcsc.com/product-detail/C21260817.html|0.58           |
|22uF            |1       |C_0402_1005Metric                     |https://www.lcsc.com/product-detail/C415703.html  |1.07           |
|10uF            |1       |C_0402_1005Metric                     |https://www.lcsc.com/product-detail/C7472949.html |0.64           |
|4.7uF           |1       |C_0402_1005Metric                     |https://www.lcsc.com/product-detail/C318563.html  |0.33           |
|2.7k            |1       |R_0402_1005Metric                     |https://www.lcsc.com/product-detail/C2906905.html |0.14           |


