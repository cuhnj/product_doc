<!-- publish-data-sidecar: section=32 heading='4.5 Fernsteuerung der Geschwindigkeit' role=generic source_md=doc.md -->

| Typ des Fernsteuerungssignals | Fernsteuerungssignal | Ausgangsspannung/Fördergeschwindigkeit |
|---|---|---|
| Panel | | Ausgangsspannung und Fördergeschwindigkeit werden nicht durch das Fernsteuerungssignal gesteuert |
| 20mA | <2mA | Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = 0<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = 0<br>LCD zeigt die Fehlerinformation "<2mA Err" an |
| | 2mA~4 mA | Ausgangsspannung = 0, Fördergeschwindigkeit = 0 |
| | 4 mA ~20mA | proportional gesteuert durch das Fernsteuerungssignal (0%~100%)<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = (Eingangsstrom - 4mA)/16 ×Max. Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = (Eingangsstrom - 4mA)/16 ×Max. Fördergeschwindigkeit |
| 1~5V | <0.5V | Ausgangsspannung = 0, Fördergeschwindigkeit = 0<br>LCD zeigt die Fehlerinformation "<0.5V Err" an |
| | 0.5V~1V | Ausgangsspannung = 0, Fördergeschwindigkeit = 0 |
| | 1V~5V | proportional gesteuert durch das Fernsteuerungssignal (0%~100%)<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = (Eingangsspannung 1V)/4 ×Max. Ausgangsspannung<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = (Eingangsspannung 1V)/4 ×Max. Ausgangsspannung |
| 0~5V | 0V~5V | proportional gesteuert durch das Fernsteuerungssignal (0%~100%)<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = Eingangsspannung/5 × Max. Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = Eingangsspannung/5 ×Max. Fördergeschwindigkeit |
| 0~10V | 0V~10V | proportional gesteuert durch das Fernsteuerungssignal (0%~100%)<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = Eingangsspannung/10 × Max. Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = Eingangsspannung/10 ×Max. Fördergeschwindigkeit |
| Meter (Potentiometer) | Teilerverhältnis des Potentiometers <4% | Ausgangsspannung = 0, Fördergeschwindigkeit = 0 |
| | Teilerverhältnis des Potentiometers beträgt 4%~96% | proportional gesteuert durch das Fernsteuerungssignal (0%~100%)<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = ((Teilerverhältnis - 4%)/92%)× Max. Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit =((Eingangsspannung Internalspannung × 4%)/Internalspannung × 92%) ×Max. Fördergeschwindigkeit |
