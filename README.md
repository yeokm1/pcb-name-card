# pcb-name-card


###PCB Design software and addons used

1. Eagle 7.3.0: I use Standard but Light should still be able to open/modify the files.
2. CR2032 libraries
2. Elecrow Design Rule Check for 2 layers (in repo as `Elecrow_2-layer_eagle_rule.dru`)
3. Elecrow Gerber Generater 2-layer board (in repo as `Elecrow_Gerber_Generater_DrillAlign.cam`)

###Schematic drawings

Images are exported from Eagle at 600dpi.

...

###BOM
Assume minimum order 10 pieces (50 pieces), cost in Singapore dollars. Delivery for BOM not included.

1. Batteries: [CR2025 batteries: $0.42 * 2 ($0.37 * 2)](http://www.digikey.sg/product-detail/en/0/P188-ND)
2. U1 and U2: [CR2016 battery holder (this can also hold CR2025): $0.42 * 2 ($0.38 *  2)](http://www.digikey.sg/product-detail/en/0/BAT-HLD-002-SMT-ND) 
3. SW1 and SW2: SMD Toggle Switch. [SeeedStudio 311030005 Source: $4/20 pieces ($12/60 pieces)](http://www.seeedstudio.com/depot/index.php?main_page=opl_info&opl_id=219) or [Digikey Source: $1.90 * 2 ($1.67 * 2)](http://www.digikey.sg/product-detail/en/AYZ0202AGRLC/401-2013-1-ND/1640122) 
4. LED1: [UV LED in PLCC package: $0.61](http://sg.element14.com/vishay-semiconductor/vlmu3100-gs08/led-ultra-violet-3-2mm-x-2-8mm/dp/2252055)
5. LED2: [Neutral While LED 4500K in PLCC package: $0.52](http://sg.element14.com/avago-technologies/asmt-uwb1-nx3e2/led-smd-plcc2-neutral-white-4500k/dp/1895842)
6. R1: [10 ohm resistor 2010 package: $0.21](http://sg.element14.com/yageo-phycomp/rc2010fk-0710rl/resistor-prc111-2010-10r/dp/9235590)
7. R2: [330 ohm resistor 2010 package: $0.15](http://sg.element14.com/welwyn/asc2010-330rft4/resistor-anti-sulphur-2010-330r/dp/2079044)

Total BOM cost : SG$7.17 (SG$3.19)

###PCB fabrication

PCB fabrication is currently done by [Elecrow (10-pieces-link)](http://www.elecrow.com/10pcs-2-layer-pcb-p-1175.html) or [(50-pieces-link)](http://www.elecrow.com/50pcs-2-layer-pcb-enig-p-1172.html) based on the following settings. Remember to consult the order submission specifications at the bottom of the previos link before submitting. Use the provided Gerber generator to produce the Gerber files.

Elecrow requires the following gerber files to be zipped up for submission:

Top layer:	pcbname.GTL  
Bottom layer:	pcbname.GBL  
Solder Stop Mask top:	pcbname.GTS  
Solder Stop Mask Bottom:	pcbname.GBS  
Silk Top:	pcbname.GTO  
Silk Bottom:	pcbname.GBO  
NC Drill:	pcbname.TXT  
Mechanical layer :	pcbname.GML  

The zip file for this design has been uploaded to the Releases section.

####My Fabrication Settings: 

1. Layer: 2
2. PCB Thickness: 0.6mm
3. Copper Weight : 1oz 35um (NA for 50 pieces)
4. PCB Size : 10cm Max * 10cm Max (or 50cm2 for 50 pieces)
5. PCB Color : Black
6. Surface Finish: ENIG
7. PCB Stencil : NO Stencil
8. Lead time : Shipped in 4 to 7 days (NA for 50 pieces)
9. Panelizing : Single PCB with milling

###Total Cost
Assume US$1 = SG$1.3

####Individual cost at minimum order for 10 Elecrow pieces:  
Total PCB Cost: US$30.80 + US$16.17 (DHL) = US$46.97  
Individual PCB Cost: (US$46.97 * 1.3) / 10 = SG$6.10  
Total Unit Cost: SG$6.10  + SG$7.17 (BOM cost) = SG$13.82  

####Individual cost at minimum order for 50 Elecrow pieces:  
Total PCB Cost: US$62.47 + US$18.81 (DHL) = US$81.28  
Individual PCB Cost: (US$81.28 * 1.3) / 50 = SG$2.11  
Total Unit Cost: SG$2.11  + SG$3.19 (BOM cost) = SG$5.30  


