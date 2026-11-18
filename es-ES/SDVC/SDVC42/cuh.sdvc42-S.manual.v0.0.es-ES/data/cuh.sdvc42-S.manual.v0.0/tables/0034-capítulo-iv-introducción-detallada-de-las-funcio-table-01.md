<!-- publish-data-sidecar: section=34 heading='4.5 Control de señales' role=generic source_md=doc.md -->

| Parámetro | Significado |
|---|---|
| Auto | Independientemente del tipo de sensor, se detecta siempre si el acceso al puerto es válido mediante el cambio de la señal de nivel alto y bajo; el valor predeterminado de fábrica es el reconocimiento automático |
| NPN | Sensor de tipo NPN |
| PNP | Sensor de tipo PNP |
| Ato1 | Antes de que la señal del sensor deje de ser válida, se detecta si el puerto es válido mediante el cambio de nivel alto y bajo. Una vez detectada una señal válida, se determina el tipo de sensor del puerto y ya no se explora |
