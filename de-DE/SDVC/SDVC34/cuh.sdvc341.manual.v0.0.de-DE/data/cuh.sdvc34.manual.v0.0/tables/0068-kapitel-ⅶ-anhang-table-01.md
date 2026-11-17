<!-- publish-data-sidecar: section=68 heading='7.4.8 Kommunikations-Parametergruppe' role=generic source_md=doc.md -->

| Funktion | Parameter | Anzeige | Wertebereich/Aufzählungselement | Standardwert |
|---|---|---|---|---|
| P8.01 | 485BUS-Kommunikationstyp | 01.485type | ASCII, RTU | RTU |
| P8.02 | Baudrate der 485-Kommunikation | 02.BaudRate | 0.3, 1.2, 2.4, 9.6, 19.2, 57.6, 115.2 Kbps | 115.2 |
| P8.03 | Slave-Identifikationsnummer der 485-Kommunikation | 03.485SlvID | 1~31 | 1 |
| P8.04 | Aktivierung des Anpassungswiderstands des 485-Kommunikationsports | 04.Enab485R | None, Valid | None |
| P8.05 | Lokale Adresse der digitalen Synchronisation | 05.DigSynAd | 1~8 |  |
| P8.06 | Aktivierung des Anpassungswiderstands des digitalen Synchronisations-Kommunikationsports | 06.EnabSynR | None, Valid | None |
| P8.07 | Bus-Signaladresse der Logik-Eingangsquelle 1 des Hauptausgangsports | 07.BSigMID1 | 1~8 |  |
| P8.08 | Bus-Signaladresse der Logik-Eingangsquelle 2 des Hauptausgangsports | 08.BSigMID2 | 1~8 |  |
| P8.09 | Bus-Signaladresse der Logik-Eingangsquelle 1 von Port D | 09.BSgD_ID1 | 1~8 |  |
| P8.10 | Bus-Signaladresse der Logik-Eingangsquelle 2 von Port D | 10.BSgD_ID2 | 1~8 |  |
| P8.11 | Bus-Signal-Bitadresse der Logik-Eingangsquelle 1 des Hauptausgangsports | 11.BSigM_B1 | 1~16 | 5 |
| P8.12 | Bus-Signal-Bitadresse der Logik-Eingangsquelle 2 des Hauptausgangsports | 12.BSigM_B2 | 1~16 | 6 |
| P8.13 | Bus-Signal-Bitadresse der Logik-Eingangsquelle 1 von Port D | 13.BSigD_B1 | 1~16 | 5 |
| P8.14 | Bus-Signal-Bitadresse der Logik-Eingangsquelle 2 von Port D | 14.BSigD_B2 | 1~16 | 6 |
| P8.15 | Signal der lokalen Bus-Signal-Bitadresse 1 | 15.LBSig_B1 | Siehe Anhang 7.4.11 | 0 |
| P8.16 | Signal der lokalen Bus-Signal-Bitadresse 2 | 16.LBSig_B2 | Siehe Anhang 7.4.11 | 1 |
| P8.17 | Signal der lokalen Bus-Signal-Bitadresse 3 | 17.LBSig_B3 | Siehe Anhang 7.4.11 | SpeedA |
| P8.18 | Signal der lokalen Bus-Signal-Bitadresse 4 | 18.LBSig_B4 | Siehe Anhang 7.4.11 | SpeedB |
| P8.19 | Signal der lokalen Bus-Signal-Bitadresse 5 | 19.LBSig_B5 | Siehe Anhang 7.4.11 | In_PtC |
| P8.20 | Signal der lokalen Bus-Signal-Bitadresse 6 | 20.LBSig_B6 | Siehe Anhang 7.4.11 | In_PtE |
| P8.21 | Signal der lokalen Bus-Signal-Bitadresse 7 | 21.LBSig_B7 | Siehe Anhang 7.4.11 | FCntSi |
| P8.22 | Signal der lokalen Bus-Signal-Bitadresse 8 | 22.LBSig_B8 | Siehe Anhang 7.4.11 | DCntSi |
| P8.23 | Signal der lokalen Bus-Signal-Bitadresse 9 | 23.LBSig_B9 | Siehe Anhang 7.4.11 | Ctr_O |
| P8.24 | Signal der lokalen Bus-Signal-Bitadresse 10 | 24.LBSigB10 | Siehe Anhang 7.4.11 | Warn |
| P8.25 | Signal der lokalen Bus-Signal-Bitadresse 11 | 25.LBSigB11 | Siehe Anhang 7.4.11 | Main |
| P8.26 | Signal der lokalen Bus-Signal-Bitadresse 12 | 26.LBSigB12 | Siehe Anhang 7.4.11 | -SpeedA |
| P8.27 | Signal der lokalen Bus-Signal-Bitadresse 13 | 27.LBSigB13 | Siehe Anhang 7.4.11 | -SpeedB |
| P8.28 | Signal der lokalen Bus-Signal-Bitadresse 14 | 28.LBSigB14 | Siehe Anhang 7.4.11 | -In_PtC |
| P8.29 | Signal der lokalen Bus-Signal-Bitadresse 15 | 29.LBSigB15 | Siehe Anhang 7.4.11 | -In_PtE |
| P8.30 | Signal der lokalen Bus-Signal-Bitadresse 16 | 30.LBSigB16 | Siehe Anhang 7.4.11 | -FCtSi |
| P8.31 | Funktion zum Hinzufügen zum Netzwerk aktivieren | 31.EnNetwok | Online, Offlin, Expand, Replace |  |
| P8.32 | Gerätenummer aus dem Netzwerk entfernen | 32.DeltDevi | 1~8 |  |
| P8.33 | Lokale Frequenzsynchronisationsnummer | 33.FrqncSyn | 1~8 |  |
| P8.34 | Lokale Nummer der Fernsteuerungs-Geschwindigkeitssynchronisation | 34.RemotSyn | 1~8 |  |
| P8.35 | Fernsteuerungsdaten | 35.RemotDat | ManVol, RemVol, ManSpd, RemSpd | ManVol |
