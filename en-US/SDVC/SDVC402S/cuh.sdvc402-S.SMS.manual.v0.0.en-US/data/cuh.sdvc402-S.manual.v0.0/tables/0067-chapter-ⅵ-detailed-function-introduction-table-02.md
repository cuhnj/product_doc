<!-- publish-data-sidecar: section=67 heading='7.4 Parameter List' role=generic source_md=doc.md -->

| | Parameter | Display | Value Range/Enumeration Item | Default |
|---|---|---|---|---|
| 4PhotoSen Parameter Group | Intelligent Photoelectric Sensor Sensitivity | 01.PortBLimit | PNP, NPN, 1~1000 | 80 |
| 4PhotoSen Parameter Group | Logical Direction of the Port B | 02.PortBDirec | Const, Inv | Const |
| 4PhotoSen Parameter Group | On Delay of the Port B | 03.PortBUpDly | 0.0~99.9 s | 0.2 |
| 4PhotoSen Parameter Group | Off Delay of the Port B | 04.PortBDnDly | 0.0~99.9 s | 0.2 |
| 5On&Off Parameter Group | Port C Sensor Type | 01.PortType | NPN, PNP, Auto1, Auto0 | Auto0 |
| 5On&Off Parameter Group | Logical Direction of the Port C | 02.PortCDirec | Const, Inv | Const |
| 5On&Off Parameter Group | On Delay of Port C | 03.PortCUpDly | 0.0~99.9 s | 0.2 |
| 5On&Off Parameter Group | Off Delay of Port C | 04.PortCDnDly | 0.0~99.9 s | 0.2 |
| 6DCoutput Parameter Group | Port D Logic Input Source 1 | 01.PortDSour1 | 0, 1, PortB, -PortB, PortC, -PortC, PortD, -PortD, Main, -Main, Err, -Err | 0 |
| 6DCoutput Parameter Group | Port D Logic Input Source 2 | 02.PortDSour2 | 0, 1, PortB, -PortB, PortC, -PortC, PortD, -PortD, Main, -Main, Err, -Err | Main |
| 6DCoutput Parameter Group | Port D Logical Relationship | 03.PortDLogic | And, Or, Xor, RS | Or |
| 6DCoutput Parameter Group | On Delay of Port D | 04.PortDUpDly | 0.0~99.9 s | 0.0 |
| 6DCoutput Parameter Group | Off Delay of Port D | 05.PortDDnDly | 0.0~99.9 s | 0.0 |
| 6DCoutput Parameter Group | Output Mode of Port D | 06.PortDMode | Delay, Hold, Cycle1, Cycle2 | Delay |
| 6DCoutput Parameter Group | Logic Direction of Port D | 07.PortDDirec | Const, Revrs, On, Off | Const |
| 6DCoutput Parameter Group | Control Output Type | 08.PortDType | Ou_NPN, Ou_PNP, Ou_P&P | Ou_NPN |
| 7Save Parameter Group | Read All Parameters From the User Group | 01.ReadALLFrm | None, UsrD1, UsrD2, UsrD3 | None |
| 7Save Parameter Group | Save All Parameters To the User Group | 02.SaveALLTo | None, Work, UsrD1, UsrD2, UsrD3 | None |
| 7Save Parameter Group | Default setting restoration | 03.RestorALL | None, Work | None |
| 7Save Parameter Group | Local Machine Identifier | 04.LoadType | None, Circ, Line, Soli | None |
| 7Save Parameter Group | Identification Number | 05.MachineNum | None, 1~1000 | None |
| 7Save Parameter Group | User Password | 06.PassWord | 0~9999 | 0 |
| 8Monitor Parameter Group | Temperature | 01.Temperatur | -20~85 ℃ | —— |
| 8Monitor Parameter Group | Output Current | 02.CurrentOut | 0.0~150 mA | —— |
| 8Monitor Parameter Group | Signal Voltage of Port A | 03.Vol_Remote | 0.0~5.0 V | —— |
| 8Monitor Parameter Group | Signal Voltage of Port B | 04.Vol_PortB | 0~999 | —— |
| 8Monitor Parameter Group | Signal Voltage of Port C | 05.Vol-PortC | 0.0~26.0 V | —— |
| 8Monitor Parameter Group | Signal Voltage of Port D | 06.Vol-PortD | 0.0~26.0 V | —— |
| 8Monitor Parameter Group | Real time voltage of 5V Port | 07.Vol-5V | 0.0~6.0 V | —— |
| 8Monitor Parameter Group | Real time voltage of 24V Port | 08.Vol-24V | 0.0~26.0 V | —— |
| 8Monitor Parameter Group | Control board software version | 09.Version | 0~99.99 | —— |
