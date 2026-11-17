<!-- publish-data-sidecar: section=24 heading='4.4.1.5 Hauptmodus' role=generic source_md=doc.md -->

| Fernsteuerungssignal | Fernsteuerungssignal | Ausgangsspannung/Fördergeschwindigkeit |
|---|---|---|
| Panel |  | Ausgangsspannung und Fördergeschwindigkeit werden nicht durch das Fernsteuerungssignal gesteuert |
| 20mA | <2mA | Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = 0<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = 0<br>LCD zeigt die Fehlerinformation „Fernsteuerung Unterspannung" an |
|  | 2mA~4mA | Ausgangsspannung = 0, Fördergeschwindigkeit = 0 |
|  | 4mA~20mA | Proportional gesteuert durch das Fernsteuerungssignal (0%~100%)<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = (Eingangsstrom - 4mA)/16 × maximale Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = (Eingangsstrom - 4mA)/16 × maximale Fördergeschwindigkeit |
| 1~5V | Weniger als 0.5V | Ausgangsspannung = 0, Fördergeschwindigkeit = 0<br>LCD zeigt die Fehlerinformation „Fernsteuerung Unterspannung" an |
|  | 0.5V~1V | Ausgangsspannung = 0, Fördergeschwindigkeit = 0 |
|  | 1V~5V | Proportional gesteuert durch das Fernsteuerungssignal (0%~100%)<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = (Eingangsspannung - 1V)/4 × maximale Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = (Eingangsspannung - 1V)/4 × maximale Fördergeschwindigkeit |
| 0~5V | 0V~5V | Proportional gesteuert durch das Fernsteuerungssignal (0%~100%)<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = Eingangsspannung/5 × maximale Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = Eingangsspannung/5 × maximale Fördergeschwindigkeit |
| 0~10V | 0V~10V | Proportional gesteuert durch das Fernsteuerungssignal (0%~100%)<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = Eingangsspannung/10 × maximale Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = Eingangsspannung/10 × maximale Fördergeschwindigkeit |
| DigSym | Digital Sync | Die Spannung des Fernsteuerungssignals ist die Fernsteuerungseingangsspannung eines bestimmten Geräts am Bus (festgelegt über die Fernsteuerungssynchronisationsparameter)<br>Proportional gesteuert durch das Fernsteuerungseingangsspannungssignal eines bestimmten Geräts am Bus, mit einem Spannungsbereich von 0% bis 100%.<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = Eingangsspannung/10 × maximale Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = Eingangsspannung/10 × maximale Fördergeschwindigkeit |
