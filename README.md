# about
A custom mouse that's small and lightweight like a cookie, a little inspiration is from the zero mouse. It's my second using kicad, but it still took a lot of time. Also i used [this repository](https://github.com/badjeff/paw3395-pcb) for the sensor pcb.

# features
A powerful microcontroller with bluetooth and usb-c for charging the lipo battery, nice scroll wheel encoder, optical sensor with up to 12 000 dpi which is low power and sometimes used for gaming and four small micro switches, two for main and other two for the side buttons, you can map them however you want. Last but really good is a build in LED in the microcontroller that is the normal red, yellow and green

# step by step tutorial for firmware
1 - download the file called firmware.uF2   
2 - connect your seeed studio via usb-c                                                                                                                                               
3 - put it into bootloader mode (double tap the **RESET** button the build in led shall start pulsing).                                                                                 
4 - now open your file manager and you should see a new USB drive called `XIAO-BLE`     
5 - drag and drop the file we installed earlier into it and the USB drive should dissaper which means **good** now it shloud work **enjoy**

# dimensions
pcb - 49.5 mm and 50 mm

# why did i create it
My mouse is not that bad, but my felt that it was heavy and actually when I take the top cover off It's more comfortable. I did weanted to spice it up with my preferences, so It's more like my mouse then a customer mouse and I know I had the skills to make that, but still I've learnt a lot.

# pictures
<img width="1190" height="892" alt="2026-06-29-114429_hyprshot" src="https://github.com/user-attachments/assets/bad13071-d826-48b7-a326-c4402e462cb4" />

<img width="1280" height="960" alt="WhatsApp Image 2026-06-11 at 17 54 53" src="https://github.com/user-attachments/assets/570fba60-585d-4b8a-8eba-5a8607e8dd8f" />

<img width="498" height="372" alt="image" src="https://github.com/user-attachments/assets/73e5827a-2f8a-48c1-bdc5-27292c2dc8f5" />


<img width="1070" height="725" alt="2026-06-29-114401_hyprshot" src="https://github.com/user-attachments/assets/5ea6d65a-4c13-4b82-800b-b2585e568815" />

<img width="1540" height="825" alt="image" src="https://github.com/user-attachments/assets/96556a01-ad36-40e1-b7b4-bd93f0748c1f" />

|Name|Purpose|Qty|Total (USD)|Distributor|Link|
-------------------------------------------------------
|TTC Mouse Encoder (Silver Core, 8mm)|Scroll wheel scroll detection|1|$ 6.58|AliExpress|https://www.aliexpress.com/item/1005006514957582.html|
|Seeed Studio XIAO BLE nRF52840|Main microcontroller and wireless chip for the mouse|1|$ 13.03|AliExpress,https://www.aliexpress.com/item/1005006988954136.html|
|3.7V 400mAh LiPo Battery|Wireless power source for the mouse|1|$ 4.88|AliExpress|https://www.aliexpress.com/item/1005007103616809.html|
|Kailh GM 8.0 Micro Switch (2pcs)|Main left and right click switches|1|$ 1.47|AliExpress,https://www.aliexpress.com/item/1005007883133457.html|
|Kailh GM 8.0 Micro Switch (3pcs)|Side buttons and a extra switch|1|$ 1.94|AliExpress|https://www.aliexpress.com/item/1005007883133457.html|
|PixArt PAW3395 Sensor + LM19-LSI Lens Kit,High-performance optical tracking sensor and matching lens,1,11.97,AliExpress,https://www.aliexpress.com/item/1005006293449301.html|
|Custom Main Mouse PCB (gerber drill files_Y7),Main board hosting the MCU and switches (White Solder Mask),5,4.0,JLCPCB,https://jlcpcb.com|
|Custom Sensor breakout PCB (gerbers_Y6),Breakout board for the PAW3395 sensor (White Solder Mask),5,2.1,JLCPCB,https://jlcpcb.com|
|C96446 (10uF ±20% 25V Ceramic Capacitor),Decoupling/Filter Capacitor,20,1.29,LCSC,https://www.lcsc.com|
|C30197477 (TLV74318PDBVR-MS Linear Voltage Regulator IC),1.8V Voltage Regulator for Sensor Power Rail,5,0.46,LCSC,https://www.lcsc.com|
|C86295 (22uF ±20% 10V Ceramic Capacitor),Decoupling/Filter Capacitor,10,0.78,LCSC,https://www.lcsc.com|
|C4241878 (MCT0603MD2004BP500 2MΩ Thin Film Resistor),Pull-up/Pull-down Resistor,5,0.43,LCSC,https://www.lcsc.com|
|C313771 (CRCW06034R70FKEAHP 4.7Ω Thick Film Resistor),Current Limiting / Filter Resistor,5,0.52,LCSC,https://www.lcsc.com|
|C51412 (CL10A335KP8NNNC 3.3uF ±10% 10V Ceramic Capacitor),Decoupling/Filter Capacitor,10,0.31,LCSC,https://www.lcsc.com|
|C161117 (GCJ188R72A104KA01D 100nF ±10% 100V Ceramic Capacitor),Decoupling/Filter Capacitor,20,0.87,LCSC,https://www.lcsc.com|
|C92759 (EMK107B7105KA-T 1uF ±10% 16V Ceramic Capacitor X7R),Decoupling/Filter Capacitor,20,0.65,LCSC,https://www.lcsc.com|
|C394535 (PTFR0603B10K0N9 10kΩ 100V Thin Film Resistor),Pull-up/Pull-down Resistor,5,0.77,LCSC,https://www.lcsc.com|
|TOTAL without shipping|||52.05||
|TOTAL with shipping|||85.43||
