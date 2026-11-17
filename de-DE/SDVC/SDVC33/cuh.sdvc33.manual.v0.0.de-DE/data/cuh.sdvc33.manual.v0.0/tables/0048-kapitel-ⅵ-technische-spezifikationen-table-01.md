<!-- publish-data-sidecar: section=48 heading='7.3 Fehlerbehebungsvorschläge und Fehlererläuterungen' role=generic source_md=doc.md -->

| Fehlercode | Definition (Phänomen) | Fehlerbehebungsmethoden |
|---|---|---|
| Er01A/Er01b | Kurzschluss von Kanal A/B<br>(Beide Kanäle stoppen die Ausgänge) | ◆ Stellen Sie sicher, dass die Last nicht kurzgeschlossen ist, und versuchen Sie dann, den Ausgang des Controllers neu zu starten, indem Sie die Ausgangs-EIN/AUS-Taste zweimal drücken oder den Controller neu einschalten. |
| Er02 | Kombinierter Überstrom von Kanal AB<br>(Beide Kanäle pausieren den Ausgang und starten nach 2s neu) | ◆ Reduzieren Sie die Ausgangsspannung entsprechend und starten Sie dann den Ausgang neu. |
| Er02A/Er02b | Einzelner Überstrom von Kanal A/B<br>(Der betroffene Kanal stoppt den Ausgang und startet nach 2s neu) | |
| Er02A./Er02b. | Einzelner Überstrom von Kanal A/B erreicht das eingestellte Maximum | |
| Er03 | Überhitzung oder Unterkühlung<br>(Beide Kanäle stoppen den Ausgang, automatische Wiederherstellung bei -20℃~60℃) | ◆ Installieren Sie den Controller in einer gut belüfteten Umgebung oder vermeiden Sie extreme Kälte. |
| Er041/Er042 | Unter-/Überspannung der Stromversorgung<br>(Beide Kanäle stoppen den Ausgang, automatische Wiederherstellung) | ◆ Stellen Sie sicher, dass die Eingangsspannung zwischen AC 85~250Vac liegt. |
| Er05 | Interne Kommunikation fehlerhaft<br>(Beide Kanäle stoppen den Ausgang) | ◆ Stellen Sie sicher, dass keine externe Stromversorgung an den 24V-Stromport angeschlossen ist, oder kontaktieren Sie unseren technischen Support. |
| Er06 | Temperatursensor fehlerhaft<br>(Beide Kanäle stoppen den Ausgang) | ◆ Stellen Sie sicher, dass die Arbeitstemperatur nicht unter -20℃ liegt, oder kontaktieren Sie unseren technischen Support. |
| Er07A/Er07b | Kurzschluss des Ports D von Kanal A/B<br>(Der Steuerausgang von Kanal A/B stoppt, nach 2s wird ein Neustart versucht) | ◆ Stellen Sie sicher, dass die Last von Port D nicht kurzgeschlossen ist und der Strom 350mA nicht überschreitet. |
| Er10 | 24V-Stromausgang fehlerhaft<br>(Der 24V-Ausgang wird abgeschaltet, nach 2s wird ein Neustart versucht) | ◆ Stellen Sie sicher, dass der 24V-Port nicht kurzgeschlossen ist und der Strom 700mA nicht überschreitet. |
| Er11 | 5V-Stromausgang fehlerhaft<br>(Die Geschwindigkeitsregelungsfunktion wird vorübergehend deaktiviert und nach automatischem Neustart wiederhergestellt) | ◆ Stellen Sie sicher, dass die 5V-Stromversorgung von Port A nicht kurzgeschlossen ist oder keine externe Versorgungsspannung von mehr als 5V angeschlossen ist. |
| Er12 | Spannung der 24V-Stromversorgung fehlerhaft<br>(Beide Kanäle stoppen den Ausgang, Steuerausgang hochohmig, automatische Wiederherstellung) | ◆ Stellen Sie sicher, dass keine externe Stromversorgung an den 24V-Stromport angeschlossen ist. |
