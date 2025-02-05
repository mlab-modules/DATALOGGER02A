# PCB

Board size: 101.09x60.45 mm (3.98x2.38 inches)

- This is the size of the rectangle that contains the board
- Thickness: 1.6 mm (63 mils)
- Material: FR4
- Finish: None
- Layers: 4
- Copper thickness: 35 µm

Solder mask: TOP / BOTTOM

- Color: Green

Silk screen: TOP / BOTTOM

- Color: White


Stackup:

| Name                 | Type                 | Color            | Thickness [µm]| Material        | Er        | Loss tan     |
|----------------------|----------------------|------------------|---------------|-----------------|-----------|--------------|
| F.SilkS              | Top Silk Screen      |                  |               |                 |           |              |
| F.Mask               | Top Solder Mask      |                  |            10 |                 |           |              |
| F.Cu                 | copper               |                  |            35 |                 |           |              |
| dielectric 1         | prepreg              |                  |           100 | FR4             |       4.5 |        0.020 |
| In1.Cu               | copper               |                  |            35 |                 |           |              |
| dielectric 2         | core                 |                  |          1240 | FR4             |       4.5 |        0.020 |
| In2.Cu               | copper               |                  |            35 |                 |           |              |
| dielectric 3         | prepreg              |                  |           100 | FR4             |       4.5 |        0.020 |
| B.Cu                 | copper               |                  |            35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   |                  |            10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |               |                 |           |              |
| B.SilkS              | Bottom Silk Screen   |                  |               |                 |           |              |

# Important sizes

Clearance: 0.15 mm (6 mils)

Track width: 0.18 mm (7 mils)

- By design rules: 0.18 mm (7 mils)

Drill: 0.3 mm (12 mils)

- Vias: 0.5 mm (20 mils) [Design: 0.5 mm (20 mils)]
- Pads: 0.3 mm (12 mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.8/0.4 mm (31/16 mils)

- By design rules: 0.8/0.4 mm (31/16 mils)
- Micro via: yes [0.15/0.1 mm (6/4 mils)]
- Buried/blind via: yes
- Total: 262 (thru: 262 buried/blind: 0 micro: 0)

Outer Annular Ring: 0.1 mm (4 mils)

- By design rules: 0.1 mm (4 mils)

Eurocircuits class: 6D
- Using min drill 0.25 mm for an OAR of 0.13 mm


# General stats

Components count: (SMD/THT)

- Top: 6/16 (SMD + THT)
- Bottom: 131/1 (SMD + THT)

Defined tracks:

- 0.3 mm (12 mils)
- 0.4 mm (16 mils)
- 0.5 mm (20 mils)
- 0.6 mm (24 mils)
- 1.0 mm (39 mils)
- 2.0 mm (79 mils)

Used tracks:

- 0.18 mm (7 mils) (57) defined: no
- 0.25 mm (10 mils) (896) defined: no
- 0.28 mm (11 mils) (1) defined: no
- 0.3 mm (12 mils) (22) defined: yes
- 0.33 mm (13 mils) (18) defined: no
- 0.5 mm (20 mils) (47) defined: yes
- 0.51 mm (20 mils) (20) defined: no
- 0.64 mm (25 mils) (8) defined: no
- 0.89 mm (35 mils) (165) defined: no

Defined vias:


Used vias:

- 0.8/0.4 mm (31/16 mils) (Count: 262, Aspect: 2.0 A) defined: no

Holes (excluding vias):

- 0.2 mm (8 mils) (9)
- 0.25 mm (10 mils) (2)
- 0.89 mm (35 mils) (66)
- 1.1 mm (43 mils) (1)
- 1.2 mm (47 mils) (2)
- 1.5 mm (59 mils) (1)
- 1.6 mm (63 mils) (1)
- 1.7 mm (67 mils) (4)
- 3.0 mm (118 mils) (4)

Oval holes:


Drill tools (including vias and computing adjusts and rounding):

- 0.3 mm (12 mils) (9)
- 0.35 mm (14 mils) (2)
- 0.5 mm (20 mils) (262)
- 1.0 mm (39 mils) (66)
- 1.1 mm (43 mils) (1)
- 1.3 mm (51 mils) (2)
- 1.6 mm (63 mils) (2)
- 1.8 mm (71 mils) (4)
- 3.1 mm (122 mils) (4)

Solder paste stats:

Using a paste with 87.75 % alloy, that has an specific gravity for the alloy of 7.4 g/cm³
and 1.0 g/cm³ for the flux. This paste has an specific gravity of  4.15 g/cm³.

The stencil thickness is  0.12 mm.

| Side   | Pads with paste | Area [mm²] | Paste [g] |
|--------|-----------------|------------|-----------|
| Top    |              38 |      65.23 |      0.32 |
| Bottom |             465 |     531.52 |      2.65 |
| Total  |             503 |     596.75 |      2.97 |

Note: this is just an approximation to the theoretical value. Margins of the solder mask and waste aren't computed.



