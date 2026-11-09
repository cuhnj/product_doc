<!-- publish-data-sidecar: section=68 heading='7.4.8 Communication Parameter Group' role=generic source_md=doc.md -->

| Function | Parameter | Display | Value Range/Enumeration Item | Default value |
|---|---|---|---|---|
| P8.01 | 485BUS Communication Type | 01.485type | ASCII, RTU | RTU |
| P8.02 | 485 Communication Baud Rate | 02.BaudRate | 0.3, 1.2, 2.4, 9.6, 19.2, 57.6, 115.2 Kbps | 115.2 |
| P8.03 | 485 Communication Slave Identification Number | 03.485SlvID | 1~31 | 1 |
| P8.04 | Enable Resistance of 485 Communication Port | 04.Enab485R | None, Valid | None |
| P8.05 | Local Digital Synchronization Address | 05.DigSynAd | 1~8 |  |
| P8.06 | Enable Resistance of Digital Synchronization Communication Port | 06.EnabSynR | None, Valid | None |
| P8.07 | Bus Signal Address of the Main Output Port Logic Input Source 1 | 07.BSigMID1 | 1~8 |  |
| P8.08 | Bus Signal Address of the Main Output Port Logic Input Source 2 | 08.BSigMID2 | 1~8 |  |
| P8.09 | Bus Signal Address of the Port D Logic Input Source 1 | 09.BSgD_ID1 | 1~8 |  |
| P8.10 | Bus Signal Address of the Port D Logic Input Source 2 | 10.BSgD_ID2 | 1~8 |  |
| P8.11 | Bus Signal Bit Address of the Main Output Port Logic Input Source 1 | 11.BSigM_B1 | 1~16 | 5 |
| P8.12 | Bus Signal Bit Address of the Main Output Port Logic Input Source 2 | 12.BSigM_B2 | 1~16 | 6 |
| P8.13 | Bus Signal Bit Address of the Port D Logic Input Source 1 | 13.BSigD_B1 | 1~16 | 5 |
| P8.14 | Bus Signal Bit Address of the Port D Logic Input Source 2 | 14.BSigD_B2 | 1~16 | 6 |
| P8.15 | Local Bus Signal Bit Address 1 Signal | 15.LBSig_B1 | See Appendix 7.4.11 | 0 |
| P8.16 | Local Bus Signal Bit Address 2 Signal | 16.LBSig_B2 | See Appendix 7.4.11 | 1 |
| P8.17 | Local Bus Signal Bit Address 3 Signal | 17.LBSig_B3 | See Appendix 7.4.11 | SpeedA |
| P8.18 | Local Bus Signal Bit Address 4 Signal | 18.LBSig_B4 | See Appendix 7.4.11 | SpeedB |
| P8.19 | Local Bus Signal Bit Address 5 Signal | 19.LBSig_B5 | See Appendix 7.4.11 | In_PtC |
| P8.20 | Local Bus Signal Bit Address 6 Signal | 20.LBSig_B6 | See Appendix 7.4.11 | In_PtE |
| P8.21 | Local Bus Signal Bit Address 7 Signal | 21.LBSig_B7 | See Appendix 7.4.11 | FCntSi |
| P8.22 | Local Bus Signal Bit Address 8 Signal | 22.LBSig_B8 | See Appendix 7.4.11 | DCntSi |
| P8.23 | Local Bus Signal Bit Address 9 Signal | 23.LBSig_B9 | See Appendix 7.4.11 | Ctr_O |
| P8.24 | Local Bus Signal Bit Address 10 Signal | 24.LBSigB10 | See Appendix 7.4.11 | Warn |
| P8.25 | Local Bus Signal Bit Address 11 Signal | 25.LBSigB11 | See Appendix 7.4.11 | Main |
| P8.26 | Local Bus Signal Bit Address 12 Signal | 26.LBSigB12 | See Appendix 7.4.11 | -SpeedA |
| P8.27 | Local Bus Signal Bit Address 13 Signal | 27.LBSigB13 | See Appendix 7.4.11 | -SpeedB |
| P8.28 | Local Bus Signal Bit Address 14 Signal | 28.LBSigB14 | See Appendix 7.4.11 | -In_PtC |
| P8.29 | Local Bus Signal Bit Address 15 Signal | 29.LBSigB15 | See Appendix 7.4.11 | -In_PtE |
| P8.30 | Local Bus Signal Bit Address 16 Signal | 30.LBSigB16 | See Appendix 7.4.11 | -FCtSi |
| P8.31 | Enable to Add Network Function | 31.EnNetwok | Online, Offlin, Expand, Replace |  |
| P8.32 | Remove Network Machine Number | 32.DeltDevi | 1~8 |  |
| P8.33 | Local Frequency Synchronization Number | 33.FrqncSyn | 1~8 |  |
| P8.34 | Local Remote Control Speed Regulation Synchronization Number | 34.RemotSyn | 1~8 |  |
| P8.35 | Remote Control Data | 35.RemotDat | ManVol, RemVol, ManSpd, RemSpd | ManVol |
