<!-- publish-data-sidecar: section=67 heading='7.4 Parameterliste' role=generic source_md=doc.md -->

| | Parameter | Anzeige | Wertebereich/Aufzählung | Standard |
|---|---|---|---|---|
| 4PhotoSen-Parametergruppe | Empfindlichkeit des intelligenten fotoelektrischen Sensors | 01.PortBLimit | PNP, NPN, 1~1000 | 80 |
| 4PhotoSen-Parametergruppe | Logikrichtung von Port B | 02.PortBDirec | Const, Inv | Const |
| 4PhotoSen-Parametergruppe | Einschaltverzögerung von Port B | 03.PortBUpDly | 0.0~99.9 s | 0.2 |
| 4PhotoSen-Parametergruppe | Ausschaltverzögerung von Port B | 04.PortBDnDly | 0.0~99.9 s | 0.2 |
| 5On&Off-Parametergruppe | Schaltsensor-Typ von Port C | 01.PortType | NPN, PNP, Auto1, Auto0 | Auto0 |
| 5On&Off-Parametergruppe | Logikrichtung von Port C | 02.PortCDirec | Const, Inv | Const |
| 5On&Off-Parametergruppe | Einschaltverzögerung von Port C | 03.PortCUpDly | 0.0~99.9 s | 0.2 |
| 5On&Off-Parametergruppe | Ausschaltverzögerung von Port C | 04.PortCDnDly | 0.0~99.9 s | 0.2 |
| 6DCoutput-Parametergruppe | Logische Eingangsquelle 1 von Port D | 01.PortDSour1 | 0, 1, PortB, -PortB, PortC, -PortC, PortD, -PortD, Main, -Main, Err, -Err | 0 |
| 6DCoutput-Parametergruppe | Logische Eingangsquelle 2 von Port D | 02.PortDSour2 | 0, 1, PortB, -PortB, PortC, -PortC, PortD, -PortD, Main, -Main, Err, -Err | Main |
| 6DCoutput-Parametergruppe | Logische Beziehung von Port D | 03.PortDLogic | And, Or, Xor, RS | Or |
| 6DCoutput-Parametergruppe | Einschaltverzögerung von Port D | 04.PortDUpDly | 0.0~99.9 s | 0.0 |
| 6DCoutput-Parametergruppe | Ausschaltverzögerung von Port D | 05.PortDDnDly | 0.0~99.9 s | 0.0 |
| 6DCoutput-Parametergruppe | Ausgangsmodus von Port D | 06.PortDMode | Delay, Hold, Cycle1, Cycle2 | Delay |
| 6DCoutput-Parametergruppe | Logikrichtung von Port D | 07.PortDDirec | Const, Revrs, On, Off | Const |
| 6DCoutput-Parametergruppe | Steuerausgangstyp | 08.PortDType | Ou_NPN, Ou_PNP, Ou_P&P | Ou_NPN |
| 7Save-Parametergruppe | Alle Parameter aus der Benutzergruppe lesen | 01.ReadALLFrm | None, UsrD1, UsrD2, UsrD3 | None |
| 7Save-Parametergruppe | Alle Parameter in der Benutzergruppe speichern | 02.SaveALLTo | None, Work, UsrD1, UsrD2, UsrD3 | None |
| 7Save-Parametergruppe | Wiederherstellung der Werkseinstellungen | 03.RestorALL | None, Work | None |
| 7Save-Parametergruppe | Kennung des lokalen Geräts | 04.LoadType | None, Circ, Line, Soli | None |
| 7Save-Parametergruppe | Identifikationsnummer | 05.MachineNum | None, 1~1000 | None |
| 7Save-Parametergruppe | Benutzerpasswort | 06.PassWord | 0~9999 | 0 |
| 8Monitor-Parametergruppe | Temperatur | 01.Temperatur | -20~85 ℃ | —— |
| 8Monitor-Parametergruppe | Ausgangsstrom | 02.CurrentOut | 0.0~150 mA | —— |
| 8Monitor-Parametergruppe | Signalspannung von Port A | 03.Vol_Remote | 0.0~5.0 V | —— |
| 8Monitor-Parametergruppe | Signalspannung von Port B | 04.Vol_PortB | 0~999 | —— |
| 8Monitor-Parametergruppe | Signalspannung von Port C | 05.Vol-PortC | 0.0~26.0 V | —— |
| 8Monitor-Parametergruppe | Signalspannung von Port D | 06.Vol-PortD | 0.0~26.0 V | —— |
| 8Monitor-Parametergruppe | Echtzeitspannung des 5V-Ports | 07.Vol-5V | 0.0~6.0 V | —— |
| 8Monitor-Parametergruppe | Echtzeitspannung des 24V-Ports | 08.Vol-24V | 0.0~26.0 V | —— |
| 8Monitor-Parametergruppe | Softwareversion der Steuerplatine | 09.Version | 0~99.99 | —— |
