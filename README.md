# pcb-name-card


###PCB Design software and addons used

1. Eagle 7.3.0: I use Standard but Light should still be able to open/modify the files.
2. CR2032 libraries
2. Elecrow Design Rule Check for 2 layers (in repo as `Elecrow_2-layer_eagle_rule.dru`)
3. Elecrow Gerber Generater 2-layer board (in repo as `SeeedElecrow_Gerber_Generater_DrillAlign.cam`)

###Schematic drawings

Images are exported from Eagle at 600dpi.

...

###BOM


###PCB fabrication

PCB fabrication is currently done by [Elecrow (10-layer-link)](http://www.elecrow.com/10pcs-2-layer-pcb-p-1175.html) based on the following settings. Remember to consult the [order submission guidelines](http://support.seeedstudio.com/knowledgebase/articles/422482-fusion-pcb-order-submission-guidelines) before submitting. Use the provided Gerber generator to produce the Gerber files.

Elecrow requires the following gerber files to be zipped up for submission:

Top layer:	pcbname.GTL
Bottom layer:	pcbname.GBL
Solder Stop Mask top:	pcbname.GTS
Solder Stop Mask Bottom:	pcbname.GBS
Silk Top:	pcbname.GTO
Silk Bottom:	pcbname.GBO
NC Drill:	pcbname.TXT
Mechanical layer :	pcbname.GML

The zip file has been uploaded to the Releases section.

####My Fabrication Settings: 

1. Layer: 2
2. PCB Thickness: 0.6mm
3. Copper Weight : 1oz 35um
4. PCB Size : 10cm Max * 10cm Max or 50cm2
5. PCB Color : Black
6. Surface Finish: ENIG
7. PCB Stencil : NO Stencil
8. Lead time : Shipped in 4 to 7 days
9. Panelizing : Single PCB with milling
