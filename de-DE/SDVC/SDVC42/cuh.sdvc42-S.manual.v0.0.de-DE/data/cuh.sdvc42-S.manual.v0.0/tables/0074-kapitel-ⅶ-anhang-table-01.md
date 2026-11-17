<!-- publish-data-sidecar: section=74 heading='7.4.8 Kommunikations-Parametergruppe' role=generic source_md=doc.md -->

| Funktion | Parameter | Anzeige | Wertebereich/Aufzählungselement | Standardwert |
|---|---|---|---|---|
| P8.01 | 485BUS Kommunikationstyp | 01.485type | ASCII, RTU | RTU |
| P8.02 | 485 Kommunikationsbaudrate | 02.BaudRate | 0,3, 1,2, 2,4, 9,6, 19,2, 57,6, 115,2 Kbps | 115,2 |
| P8.03 | 485 Kommunikations-Slave-Identifikationsnummer | 03.485SlvID | 1~31 | 1 |
| P8.04 | Widerstand des 485 Kommunikationsports aktivieren | 04.Enab485R | None, Valid | None |
| P8.05 | Lokale digitale Synchronisationsadresse | 05.DigSynAd | 1~8 |  |
| P8.06 | Widerstand des digitalen Synchronisations-Kommunikationsports aktivieren | 06.EnabSynR | None, Valid | None |
| P8.07 | Bus-Signaladresse der Hauptausgangs-Port-Logik-Eingangsquelle 1 | 07.BSigMID1 | 1~8 |  |
| P8.08 | Bus-Signaladresse der Hauptausgangs-Port-Logik-Eingangsquelle 2 | 08.BSigMID2 | 1~8 |  |
| P8.09 | Bus-Signaladresse der Port D Logik-Eingangsquelle 1 | 09.BSgD_ID1 | 1~8 |  |
| P8.10 | Bus-Signaladresse der Port D Logik-Eingangsquelle 2 | 10.BSgD_ID2 | 1~8 |  |
| P8.11 | Bus-Signal-Bitadresse der Hauptausgangs-Port-Logik-Eingangsquelle 1 | 11.BSigM_B1 | 1~16 | 5 |
| P8.12 | Bus-Signal-Bitadresse der Hauptausgangs-Port-Logik-Eingangsquelle 2 | 12.BSigM_B2 | 1~16 | 6 |
| P8.13 | Bus-Signal-Bitadresse der Port D Logik-Eingangsquelle 1 | 13.BSigD_B1 | 1~16 | 5 |
| P8.14 | Bus-Signal-Bitadresse der Port D Logik-Eingangsquelle 2 | 14.BSigD_B2 | 1~16 | 6 |
| P8.15 | Lokales Bus-Signal-Bitadresse 1 Signal | 15.LBSig_B1 | Siehe Anhang 7.4.11 | 0 |
| P8.16 | Lokales Bus-Signal-Bitadresse 2 Signal | 16.LBSig_B2 | Siehe Anhang 7.4.11 | 1 |
| P8.17 | Lokales Bus-Signal-Bitadresse 3 Signal | 17.LBSig_B3 | Siehe Anhang 7.4.11 | SpeedA |
| P8.18 | Lokales Bus-Signal-Bitadresse 4 Signal | 18.LBSig_B4 | Siehe Anhang 7.4.11 | SpeedB |
| P8.19 | Lokales Bus-Signal-Bitadresse 5 Signal | 19.LBSig_B5 | Siehe Anhang 7.4.11 | In_PtC |
| P8.20 | Lokales Bus-Signal-Bitadresse 6 Signal | 20.LBSig_B6 | Siehe Anhang 7.4.11 | In_PtE |
| P8.21 | Lokales Bus-Signal-Bitadresse 7 Signal | 21.LBSig_B7 | Siehe Anhang 7.4.11 | FCntSi |
| P8.22 | Lokales Bus-Signal-Bitadresse 8 Signal | 22.LBSig_B8 | Siehe Anhang 7.4.11 | DCntSi |
| P8.23 | Lokales Bus-Signal-Bitadresse 9 Signal | 23.LBSig_B9 | Siehe Anhang 7.4.11 | Ctr_O |
| P8.24 | Lokales Bus-Signal-Bitadresse 10 Signal | 24.LBSigB10 | Siehe Anhang 7.4.11 | Warn |
| P8.25 | Lokales Bus-Signal-Bitadresse 11 Signal | 25.LBSigB11 | Siehe Anhang 7.4.11 | Main |
| P8.26 | Lokales Bus-Signal-Bitadresse 12 Signal | 26.LBSigB12 | Siehe Anhang 7.4.11 | -SpeedA |
| P8.27 | Lokales Bus-Signal-Bitadresse 13 Signal | 27.LBSigB13 | Siehe Anhang 7.4.11 | -SpeedB |
| P8.28 | Lokales Bus-Signal-Bitadresse 14 Signal | 28.LBSigB14 | Siehe Anhang 7.4.11 | -In_PtC |
| P8.29 | Lokales Bus-Signal-Bitadresse 15 Signal | 29.LBSigB15 | Siehe Anhang 7.4.11 | -In_PtE |
| P8.30 | Lokales Bus-Signal-Bitadresse 16 Signal | 30.LBSigB16 | Siehe Anhang 7.4.11 | -FCtSi |
| P8.31 | Netzwerkfunktion hinzufügen aktivieren | 31.EnNetwok | Online, Offlin, Expand, Replace |  |
| P8.32 | Netzwerkgeräte-Nummer entfernen | 32.DeltDevi | 1~8 |  |
| P8.33 | Lokale Frequenzsynchronisationsnummer | 33.FrqncSyn | 1~8 |  |
| P8.34 | Lokale Ferngeschwindigkeitsregelungs-Synchronisationsnummer | 34.RemotSyn | 1~8 |  |
| P8.35 | Fernsteuerungsdaten | 35.RemotDat | ManVol, RemVol, ManSpd, RemSpd | ManVol |
