<!-- publish-data-sidecar: section=55 heading='Anhang E: Warnungs- und Fehlerbeschreibung und Vorschläge zur Fehlerbehebung' role=generic source_md=doc.md -->

| Fehleranzeige | Fehlertyp | Vorschläge zur Fehlerbehebung |
|---|---|---|
| 24VErr | Fehler der internen 24V-Stromversorgung | Ausfall der internen 24V-Stromversorgung des Controllers, bitte kontaktieren Sie uns für die Reparatur |
| 5VErr | Fehler der internen 5V-Stromversorgung | Ausfall der internen 5V-Stromversorgung des Controllers, bitte kontaktieren Sie uns für die Reparatur |
| <2mA Err | Der Eingangsstrom des Fernsteuerungssignals ist zu niedrig an Port A | Der Eingangsstrom des Fernsteuerungssignals ist zu niedrig an Port A; stellen Sie sicher, dass er größer als 2mA ist |
| <0.5V Err | Die Eingangsspannung des Fernsteuerungssignals ist zu niedrig an Port A | Die Eingangsspannung des Fernsteuerungssignals ist zu niedrig an Port A; stellen Sie sicher, dass sie größer als 0.5V ist |
| CommErr(1~5) | Kommunikationsfehler | Bitte kontaktieren Sie uns für die Reparatur |
| decline | Zählverlangsamung | Wenn die Zählanzahl den von Ihnen eingestellten "End Count" erreicht, sinkt die Ausgangsspannung (oder Fördergeschwindigkeit) |
| EEPErr | Fehler beim Speichern voreingestellter Parameter | Bitte kontaktieren Sie uns für die Reparatur |
| FrqncyHi | Sync-Referenzfrequenz ist zu hoch | Eingangsfrequenz des Sync-Signals des Slave-Controllers ist größer als 400Hz<br>Stellen Sie sicher, dass die Frequenz des Sync-Signals zwischen 25 Hz und 400 Hz liegt |
| FrqncyLo | Sync-Referenzfrequenz ist zu niedrig | Eingangsfrequenz des Sync-Signals des Slave-Controllers ist kleiner als 25Hz<br>Stellen Sie sicher, dass die Frequenz des Sync-Signals zwischen 25 Hz und 400 Hz liegt |
| OverHot | Überhitzung | Interne Temperatur des Controllers überschreitet 65℃<br>Stellen Sie sicher, dass der Controller in einer gut belüfteten Umgebung arbeitet |
| OverLoad | Überlast des Vibrationssensors | Der Vibrationssensor hat erkannt, dass die Beschleunigung seinen absoluten Amplitudenwert überschreitet |
| OvrCurrt | Überstrom | Ausgangsstrom des Controllers überschreitet 3A |
| OvrVoltg | Überspannung | Ausgangsspannung des Controllers überschreitet 260V<br>Stellen Sie sicher, dass der Eingangsspannungsbereich zwischen 85V und 260V liegt |
| PortDErr | Fehler Port D | Ausgangsspannungsabweichung von Port D überschreitet 3V<br>Stellen Sie sicher, dass die Lastleistung von Port D 4.8W nicht überschreitet |
| PortPErr | Fehler Port P | Ausgangsspannungsabweichung von Port P überschreitet 3V<br>Stellen Sie sicher, dass die Lastleistung von Port P 4.8W nicht überschreitet |
| Saturate | Ausgangssättigung | Wenn die Ausgangsspannung des Controllers größer als die Eingangsspannung ist, tritt der Controller in den Sättigungszustand ein |
| Save | Speichern voreingestellter Parameter | Nach dem Vorgang der automatischen Resonanzfrequenzsuche werden die zugehörigen Parameter erfolgreich gespeichert |
| SenorErr | Vibrationssensorfehler | Das Signal des Vibrationssensors ist ungewöhnlich, bitte kontaktieren Sie uns für die Reparatur |
| SenTypEr | Fehler des Vibrationssensortyps | Der Typ des an den Controller angeschlossenen Vibrationssensors stimmt nicht mit dem im Controller eingestellten Parameter "Vibrationssensortyp" überein |
| Short | Kurzschluss | Der Ausgang des Controllers ist kurzgeschlossen; stellen Sie sicher, dass der Ausgangsanschluss nicht kurzgeschlossen ist |
| SynchErr | Sync-Signalfehler | Das Sync-Signalkabel ist nicht mit dem Slave-Controller verbunden<br>Stellen Sie sicher, dass das Sync-Signalkabel korrekt mit dem Controller verbunden ist |
| UndrVolt | Unterspannung | Eingangsspannung des Controllers ist kleiner als 85V.<br>Stellen Sie sicher, dass der Eingangsspannungsbereich zwischen 85V und 260V liegt |
| UpgradeSlv | Firmware-Aktualisierung | Die Firmware wird aktualisiert; der Controller kehrt nach der Aktualisierung zum Normalbetrieb zurück |
