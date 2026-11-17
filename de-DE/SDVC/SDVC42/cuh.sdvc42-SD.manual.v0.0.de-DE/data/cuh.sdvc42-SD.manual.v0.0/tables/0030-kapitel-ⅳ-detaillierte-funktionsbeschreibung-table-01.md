<!-- publish-data-sidecar: section=30 heading='4.4.1.7 Fernsteuerungsquelle' role=generic source_md=doc.md -->

| Fernsteuersignal | Fernsteuersignal | Ausgangsspannung/Fördergeschwindigkeit |
|---|---|---|
| Panel |  | Ausgangsspannung und Fördergeschwindigkeit werden nicht durch Fernsteuersignal gesteuert |
| 20mA | <2mA | Wenn Spannungsmodus Manuell: Ausgangsspannung = 0<br>Wenn Spannungsmodus Auto: Fördergeschwindigkeit = 0<br>LCD zeigt Fehlermeldung „Fernsteuerung Unterspannung" |
|  | 2mA~4mA | Ausgangsspannung = 0, Fördergeschwindigkeit = 0 |
|  | 4mA~20mA | Proportional gesteuert durch Fernsteuersignal (0%~100%)<br>Spannungsmodus Manuell: Ausgangsspannung = (Eingangsstrom - 4mA)/16 × Max. Ausgangsspannung<br>Spannungsmodus Auto: Fördergeschwindigkeit = (Eingangsstrom - 4mA)/16 × Max. Fördergeschwindigkeit |
| 1~5V | Unter 0,5V | Ausgangsspannung = 0, Fördergeschwindigkeit = 0<br>LCD zeigt Fehlermeldung „Fernsteuerung Unterspannung" |
|  | 0,5V~1V | Ausgangsspannung = 0, Fördergeschwindigkeit = 0 |
|  | 1V~5V | Proportional gesteuert durch Fernsteuersignal (0%~100%)<br>Spannungsmodus Manuell: Ausgangsspannung = (Eingangsspannung - 1V)/4 × Max. Ausgangsspannung<br>Spannungsmodus Auto: Fördergeschwindigkeit = (Eingangsspannung - 1V)/4 × Max. Fördergeschwindigkeit |
| 0~5V | 0V~5V | Proportional gesteuert durch Fernsteuersignal (0%~100%)<br>Spannungsmodus Manuell: Ausgangsspannung = Eingangsspannung/5 × Max. Ausgangsspannung<br>Spannungsmodus Auto: Fördergeschwindigkeit = Eingangsspannung/5 × Max. Fördergeschwindigkeit |
| 0~10V | 0V~10V | Proportional gesteuert durch Fernsteuersignal (0%~100%)<br>Spannungsmodus Manuell: Ausgangsspannung = Eingangsspannung/10 × Max. Ausgangsspannung<br>Spannungsmodus Auto: Fördergeschwindigkeit = Eingangsspannung/10 × Max. Fördergeschwindigkeit |
| DigSym | Digitale Synchronisation | Die Spannung des Fernsteuersignals ist die Fernsteuerungs-Eingangsspannung eines bestimmten Geräts am Bus (über Fernsteuerungs-Synchronisationsparameter festgelegt)<br>Proportional gesteuert durch das Fernsteuerungs-Eingangsspannungssignal eines bestimmten Geräts am Bus, Spannungsbereich 0% bis 100%.<br>Spannungsmodus Manuell: Ausgangsspannung = Eingangsspannung/10 × Max. Ausgangsspannung<br>Spannungsmodus Auto: Fördergeschwindigkeit = Eingangsspannung/10 × Max. Fördergeschwindigkeit |
