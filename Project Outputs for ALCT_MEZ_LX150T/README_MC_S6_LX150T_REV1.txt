UCLA High Energy Physics
------------------------

Specifications 12/06/2017

Board:   MC_S6_LX150T
Layout Version: 12/06/2017, rev 1 

Contact:
--------

UCLA Physics Department
475 Portola Plaza
1-129 Knudsen Hall
Los Angeles, CA 90095-1547

Specifications:
---------------
Board thickness: 0.06256"
Board size:      4.100" x 5.350"
Trace width/gap  4/4 mils
Plating:         ENIG

Silkscreen:        2 sides, White
Termination pads to be free of mask coating.
Solder mask color: Green

Smallest hole:   0.010

Layer Specifications:
---------------------

|-----+-------------------------------------+----------------+---------------------------|
|     | Top side solder mask                | 0.70   mils    |                           |
| L1  | TOP                  copper+plating | 1.58   mils    |                           |
|     | dielectric layer                    | 2.50   mils    |                           |
| L2  | copper                              | 0.70   mils    |                           |
|     | dielectric layer                    | 10.00  mils    |                           |
| L3  | copper                              | 0.70   mils    |                           |
|     | dielectric layer                    | 5.00   mils    |                           |
| L4  | copper                              | 0.70   mils    |                           |
|     | dielectric layer                    | 3.00   mils    |                           |
| L5  | copper                              | 0.70   mils    |                           |
|     | dielectric layer                    | 3.50   mils    |                           |
| L6  | copper                              | 0.70   mils    |                           |
|     | dielectric layer                    | 3.00   mils    |                           |
| L7  | copper                              | 0.70   mils    |                           |
|     | dielectric layer                    | 3.50   mils    |                           |
| L8  | copper                              | 0.70   mils    |                           |
|     | dielectric layer                    | 3.00   mils    |                           |
| L9  | copper                              | 0.70   mils    |                           |
|     | dielectric layer                    | 5.00   mils    |                           |
| L10 | copper                              | 0.70   mils    | 5/10/5 mils, 100 ohm, 10% |
|     | dielectric layer                    | 10.00  mils    |                           |
| L11 | copper                              | 0.70   mils    |                           |
|     | dielectric layer                    | 2.50   mils    |                           |
| L12 | Bottom               copper+plating | 1.58   mils    |                           |
|     | Top side             solder mask    | 0.70   mils    |                           |
|-----+-------------------------------------+----------------+---------------------------|
|     | TOTAL                               | 62.56     mils |                           |
|-----+-------------------------------------+----------------+---------------------------|


12-Layer Stackup:
-----------------

File extensions are Altium standard 

All copper layers are positively defined

------------------------------------------------------------------------------------------
Layer Extension     Layer Description                      
------------------------------------------------------------------------------------------
.GTL                Top Layer                               
.G1                 Mid-Layer 1                             
.G2                 +3V3                                    
.G3                 Mid-Layer 2                             
.G4                 +1V2                                    
.G5                 Mid-Layer 4                             
.G6                 +2V5                                    
.G7                 Mid-Layer 5                             
.G8                 GND1                                    
.G9                 Mid-Layer 7                             
.G10                GND2                                    
.GBL                Bottom Layer                            
.GTO                Top Overlay                             
.GTP                Top Paste                               
.GTS                Top Solder                              
.GBS                Bottom Solder                           
.GBP                Bottom Paste                            
.GBO                Bottom Overlay                          
.GM16               Board Outline                           
------------------------------------------------------------------------------------------

Special Instructions:
---------------------
(1) Thieving is not allowed; please inform me if thieving is required for any part of the PCB 
(2) Fiducial dots are placed throughout the board; please inform me if additional dots are needed
