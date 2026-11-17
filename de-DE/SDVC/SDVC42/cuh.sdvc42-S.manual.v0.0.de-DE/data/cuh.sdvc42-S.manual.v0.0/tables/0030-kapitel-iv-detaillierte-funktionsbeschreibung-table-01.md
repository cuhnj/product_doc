<!-- publish-data-sidecar: section=30 heading='4.4.1.7 Fernsteuerungsquelle' role=generic source_md=doc.md -->

| Fernsteuerungssignal | Fernsteuerungssignal | Ausgangsspannung/Fördergeschwindigkeit |
|---|---|---|
| Panel |  | Ausgangsspannung und Fördergeschwindigkeit werden nicht durch Fernsteuerungssignal gesteuert |
| 20mA | &lt;2mA | Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = 0<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = 0<br>LCD zeigt die Fehlermeldung „Fernsteuerung Unterspannung" an |
| 20mA | 2mA~4mA | Ausgangsspannung = 0, Fördergeschwindigkeit = 0 |
| 20mA | 4mA~20mA | Proportional gesteuert durch Fernsteuerungssignal（0%~100%）<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = (Eingangsstrom - 4mA)/16 × Max. Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = (Eingangsstrom - 4mA)/16 × Max. Fördergeschwindigkeit |
| 1~5V | Unter 0,5V | Ausgangsspannung = 0, Fördergeschwindigkeit = 0<br>LCD zeigt die Fehlermeldung „Fernsteuerung Unterspannung" an |
| 1~5V | 0,5V~1V | Ausgangsspannung = 0, Fördergeschwindigkeit = 0 |
| 1~5V | 1V~5V | Proportional gesteuert durch Fernsteuerungssignal（0%~100%）<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = (Eingangsspannung - 1V)/4 × Max. Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = (Eingangsspannung - 1V)/4 × Max. Fördergeschwindigkeit |
| 0~5V | 0V~5V | Proportional gesteuert durch Fernsteuerungssignal（0%~100%）<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = Eingangsspannung/5 × Max. Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = Eingangsspannung/5 × Max. Fördergeschwindigkeit |
| 0~10V | 0V~10V | Proportional gesteuert durch Fernsteuerungssignal（0%~100%）<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = Eingangsspannung/10 × Max. Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = Eingangsspannung/10 × Max. Fördergeschwindigkeit |
| DigSym | Digital Sync | Die Spannung des Fernsteuerungssignals ist die Fernsteuerungs-Eingangsspannung eines bestimmten Geräts am Bus（spezifiziert durch Fernsteuerungs-Synchronisationsparameter）<br>Proportional gesteuert durch das Fernsteuerungs-Eingangsspannungssignal eines bestimmten Geräts am Bus, mit einem Spannungsbereich von 0% bis 100%.<br>Wenn der Spannungsmodus Manuell ist, Ausgangsspannung = Eingangsspannung/10 × Max. Ausgangsspannung<br>Wenn der Spannungsmodus Auto ist, Fördergeschwindigkeit = Eingangsspannung/10 × Max. Fördergeschwindigkeit |
