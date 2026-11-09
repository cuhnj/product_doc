<!-- publish-data-sidecar: section=67 heading='7.4 Parameter List' role=generic source_md=doc.md -->

| | Parameter | Display | Value Range/Enumeration Item | Default |
|---|---|---|---|---|
| 1EditHome Parameter Group | Monitoring Project 1 | Monit 1 | Parameter Group 2~Parameter Group 8 | UsrVoltage |
| | Monitoring Project 2 | Monit 2 | Parameter Group 2~Parameter Group 8 | UsrFreqncy |
| | Monitoring Project 3 | Monit 3 | Parameter Group 2~Parameter Group 8 | CurrentOut |
| | Monitoring Project 4 | Monit 4 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 5 | Monit 5 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 6 | Monit 6 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 7 | Monit 7 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 8 | Monit 8 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 9 | Monit 9 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 10 | Monit 10 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 11 | Monit 11 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 12 | Monit 12 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 13 | Monit 13 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 14 | Monit 14 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 15 | Monit 15 | Parameter Group 2~Parameter Group 8 | |
| | Monitoring Project 16 | Monit 16 | Parameter Group 2~Parameter Group 8 | |
| 2Common Parameter Group | User Set Voltage | 01.UsrVoltage | 0~220 V | 150 |
| | User Set Frequency | 02.UsrFreqncy | 40.0~999.9 Hz | 50.0 |
| | Soft Start Time | 03.SoftStarT | 0.0~10.0 s | 0.5 |
| | Soft Stop Time | 04.SoftStopT | 0.0~10.0 s | 0.0 |
| | Maximum Output Voltage | 05.MaxVoltage | 0~220 V | 220 |
| | Minimum Output Voltage | 06.MinVoltage | 0~220 V | 0 |
| | Maximum Output Frequency | 07.MaxFreqncy | 40.0~999.9 Hz | 999.9 |
| | Minimum Output Frequency | 08.MinFreqncy | 40.0~999.9 Hz | 40.0 |
| | Backlight Off Time | 09.Off_time | On, 1~30 Mi | On |
| | Language | 10.Language | Chines, Englis | Chines |
| 3M_output Parameter Group | Main Output Logic Input Source 1 | 01.MainSourc1 | 0, 1, PortB, -PortB, PortC, -PortC, PortD, -PortD, Main, -Main, Err, -Err | PortB |
| | Main Output Logic Input Source 2 | 02.MainSourc2 | 0, 1, PortB, -PortB, PortC, -PortC, PortD, -PortD, Main, -Main, Err, -Err | PortC |
| | Main Output Port Logic | 03.MainLogic | And, Or, Xor, RS | Or |
| | On Delay of Main Output | 04.MainUpDly | 0.0~99.9 s | 0.0 |
| | Off Delay of Main Output | 05.MainDnDly | 0.0~99.9 s | 0.0 |
| | Main Output Mode | 06.MainMode | Delay, Hold | Delay |
| | Main Output Logical Direction | 07.MainDirect | Const, Revrs, On, Off | Revrs |
| | Power On Status | 08.PowerOnSta | On, Off, Hold | On |
