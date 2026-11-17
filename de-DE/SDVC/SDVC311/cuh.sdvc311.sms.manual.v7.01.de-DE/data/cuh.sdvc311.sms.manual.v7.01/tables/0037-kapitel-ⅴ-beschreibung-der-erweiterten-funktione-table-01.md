<!-- publish-data-sidecar: section=37 heading='5.9 Parameter-Passwortsperrfunktion' role=generic source_md=doc.md -->

| Sperrparameter | Wellenformindex | Beschleunigungsindex | Begrenzung der maximalen Ausgangsspannung | Logikverknüpfung der Signalquellen des Hauptausgangs | Die zweite Signalquelle des Hauptausgangs | Die erste Signalquelle des Hauptausgangs | Logikverknüpfung der Signalquellen von Steuerport D | Die zweite Signalquelle von Steuerport D | Die erste Signalquelle von Steuerport D | Sensortyp von Port C | Bremszyklen/Sanftabschaltung | Ausgangsfrequenz |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1: Gesperrt | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
| 0: Entsperrt | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Multiplikationsfaktor | 4 | 2 | 1 | 4 | 2 | 1 | 4 | 2 | 1 | 4 | 2 | 1 |
| Wertebereich des Passwortwerts (Summierung) | 0~7 (1. Stelle des Passwortwerts) | | | 0~7 (2. Stelle des Passwortwerts) | | | 0~7 (3. Stelle des Passwortwerts) | | | 0~7 (4. Stelle des Passwortwerts) | | |
| Beispiel 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |
| | 0 | | | 0 | | | 0 | | | 1\*1=1 | | |
| Beispiel 2 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 1 |
| | 1\*4=4 | | | 1\*1=1 | | | 0 | | | 1\*1=1 | | |
| Beispiel 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 1 | 1 |
| | 0 | | | 0 | | | 0 | | | 1\*4+1\*2+1\*1=7 | | |
