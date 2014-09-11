ALL OF THE RAD1 PCB DESIGN IS PROVIDED UNDER THE TERMS OF THIS CREATIVE COMMONS PUBLIC LICENSE ("CCPL" OR "LICENSE"). 
THE WORK IS PROTECTED BY COPYRIGHT AND/OR OTHER APPLICABLE LAW. ANY USE OF THE WORK OTHER THAN AS 
AUTHORIZED UNDER THIS LICENSE OR COPYRIGHT LAW IS PROHIBITED. 

See http://creativecommons.org/licenses/by-sa/3.0/legalcode

Board Name: RF-Combo 			Customer: Range Networks
Fab Part Number: RNRAD1-RF-COMBO-R5	Revision: 5

ARTWORK FILENAME CONTROL CHART:

GERBER FILENAME	   		PCB DESIGN LAYER

layer01.art		=    	top - component side
layer02.art		=	layer 02 - gnd plane
layer03.art		=	layer 03 - pwr plane
layer04.art		=	bottom - solder side

paste_top.art      	=	component side pastemask
paste_bot.art     	=	solder side pastemask
silk_top.art      	=	component side silkscreen
silk_bot.art     	=	solder side silkscreen
solder_top.art		=	component side soldermask
solder_bot.art		=	solder side soldermask

fab.art			=	fabrication drawing
assy.art		=	assembly drawing

Reference Drawings:

fab.PDF			=	fabrication drawing
assy.PDF		=	assembly drawing 


Additional Support Files:
	
RNRAD1-RF-COMBO-R5-1-4.drl	NC Drill information Layer 1 to 4
RNRAD1-RF-COMBO-R5.cad		FABmaster extract file
RNRAD1-RF-COMBO-R5.ipc		Export of IPC 356D netlist
RNRAD1-RF-COMBO-R5.rou		Route file
rnrad1-rf-combo-r5.tgz		Valor ODB++
art_param.txt			Gerber output setup information
ncdrill.log			NC Drill report
nc_param.txt			NC Parameter report
place_txt.txt			Export of assembly component placement
readme.txt	 		Gerber ZIP file content information


Special notes:

1. Two shorts in Valor - U3 and U6 pin 2 connects to their tabs (a mech pin).
2. There are two known dangling traces, leave them please.

=================================================
Rocket EMS, Inc
2380 Bering Drive
San Jose, Ca 95131

Design contact: Craig Schieferstein (408)955-0528 x1203 cell (408)888-7351
Email contact: cschieferstein@rocketems.com
Sales contact: Scott Schaetzle (408)315-5192

If there are any question regarding the data please call Craig Schieferstein. 

