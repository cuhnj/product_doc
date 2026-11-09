<!-- publish-data-sidecar: section=41 heading='7.1 Parameter Table' role=generic source_md=doc.md -->

| Parameter | Definition | Symbol | symbol image | Range | Default |
|---|---|---|---|---|---|
| Standby Parameter | Set Frequency | F | ![Set Frequency 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-00.png) | 2.0~120.0 (Hz) (limited by r and y) | 50.0 |
| Motor Parameter — Long press ⚙ | Forward Start/Stop Control Source 1 | F1 | ![Forward Start/Stop Control Source 1 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-01.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP | C |
| Motor Parameter | Forward Start/Stop Control Source 2 | F2 | ![Forward Start/Stop Control Source 2 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-02.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP | -b |
| Motor Parameter | Forward Start/Stop Logic Relationship | FA | ![Forward Start/Stop Logic Relationship 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-03.png) | And, or, Xor, rS | And |
| Motor Parameter | Reverse Control Source 1 | A1 | ![Reverse Control Source 1 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-04.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP | E |
| Motor Parameter | Reverse Control Source 2 | A2 | ![Reverse Control Source 2 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-05.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP | -b |
| Motor Parameter | Reverse Logic Relationship | AA | ![Reverse Logic Relationship 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-06.png) | And, or, Xor, rS | And |
| Motor Parameter | Forward and Reverse Control Mode | Fr | ![Forward and Reverse Control Mode 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-07.png) | 0 (Forward control source is used to start and stop forward rotation, and reverse control source is used to control reverse rotation start and stop)<br>1 (Forward control source is used to control start and stop, reverse control source is used to control forward and reverse) | 0 |
| Motor Parameter | Emergency Stop Source | Eq | ![Emergency Stop Source 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-08.png) | 0, 1, b, -b, C, -C, E, -E, SA, -SA, Sb, -Sb, ES, -ES, od, -od, oP, -oP, oq, -oq, Er, -Er, Ar, -Ar | ES |
| Motor Parameter | Emergency Stop Type | Sq | ![Emergency Stop Type 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-09.png) | Sto: Safe torque off, Sbc: Safety brake control,<br>SS1: Category 1 safety stop　(Note1) | Sto |
| Motor Parameter | Soft Start Time | t | ![Soft Start Time 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-10.png) | 0.0~99.9 (s) | 10.0 |
| Motor Parameter | Soft Closing Time | d | ![Soft Closing Time 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-11.png) | DC Braking Time: -0.0~-99.9 (s)<br>Soft Closing Time: 0.0~99.9 (s) | 10.0 |
| Motor Parameter | Maximum Frequency | y | ![Maximum Frequency 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-12.png) | 2.0~120.0 (Hz) | 50.0 |
| Motor Parameter | Rated Frequency | b | ![Rated Frequency 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-13.png) | 45.0~65.0 (Hz) | 50.0 |
| Motor Parameter | Rated Voltage | h | ![Rated Voltage 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-14.png) | 70~220 (Vrmn) | 200 |
| Motor Parameter | Intermediate Frequency | n | ![Intermediate Frequency 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-15.png) | r~b (Hz) | 10.0 |
| Motor Parameter | Intermediate Voltage | o | ![Intermediate Voltage 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-16.png) | u~h (Vrmn) | 40 |
| Motor Parameter | Lowest Frequency | r | ![Lowest Frequency 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-17.png) | 2.0~n (Hz) | 2.0 |
| Motor Parameter | Lowest Voltage | u | ![Lowest Voltage 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-18.png) | 0~o (Vrmn) | 8 |
| Motor Parameter | Motor Rated Electrical Power | Pn | ![Motor Rated Electrical Power 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-19.png) | 0.01~0.20 (kW) | 0.20 |
| Motor Parameter | Power Excess Factor | rc | ![Power Excess Factor 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-20.png) | 100~150 (%) | 150 |
| Motor Parameter | Braking Current Coefficient | cb | ![Braking Current Coefficient 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-21.png) | 10~150 (%) | 100 |
| Motor Parameter | Electric Power Overheating Threshold | oL | ![Electric Power Overheating Threshold 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-22.png) | 0~90 (times*seconds)<br>Remarks: If the rated electric power of the motor is exceeded and does not exceed the upper limit of the motor power, if the integral per second exceeds this setting, it will enter the electronic overheating protection state. | 30 |
| Motor Parameter | Power Derating Factor | rL | ![Power Derating Factor 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-23.png) | 0~90(%)<br>0 means shutdown,<br>90 means reducing to 90% of rated power. | 0 |
| Motor Parameter | Rotation Direction Exchange (Note2) | Ph | ![Rotation Direction Exchange 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-24.png) | Abc: standard direction, Acb: direction exchange,<br>A.b.c.: Reversal of the standard direction is forbidden (only forward),<br>A.c.b.: Direction swapping prohibits forward rotation (only reversal) | AbC |
| Motor Parameter | Power On Running Status | PS | ![Power On Running Status 数码管符号](assets/images/cuh.sdmc30.manual.v0.0/page-0047-vcrop-25.png) | run: run, stp: stop, FoL: save the last time | FoL |
