<!-- publish-data-sidecar: section=24 heading='4.4.1.5 Modo principal' role=generic source_md=doc.md -->

| Señal de control remoto | Señal de control remoto | Tensión de salida/Velocidad de alimentación |
|---|---|---|
| Panel |  | La tensión de salida y la velocidad de alimentación no están controladas por la señal de control remoto |
| 20mA | <2mA | Cuando el modo de tensión es Manual, tensión de salida = 0<br>Cuando el modo de tensión es Auto, velocidad de alimentación = 0<br>La pantalla LCD muestra la información de error "Remote control undervoltage" |
|  | 2mA~4mA | Tensión de salida = 0, velocidad de alimentación = 0 |
|  | 4mA~20mA | Control proporcional mediante la señal de control remoto（0%~100%）<br>Cuando el modo de tensión es Manual, tensión de salida = (Corriente de entrada - 4mA)/16 × tensión de salida máxima<br>Cuando el modo de tensión es Auto, velocidad de alimentación = (Corriente de entrada - 4mA)/16 × velocidad de alimentación máxima |
| 1~5V | Menos de 0.5V | Tensión de salida = 0, velocidad de alimentación = 0<br>La pantalla LCD muestra la información de error "Remote control undervoltage" |
|  | 0.5V~1V | Tensión de salida = 0, velocidad de alimentación = 0 |
|  | 1V~5V | Control proporcional mediante la señal de control remoto（0%~100%）<br>Cuando el modo de tensión es Manual, tensión de salida = (Tensión de entrada - 1V)/4 × tensión de salida máxima<br>Cuando el modo de tensión es Auto, velocidad de alimentación = (Tensión de entrada - 1V)/4 × velocidad de alimentación máxima |
| 0~5V | 0V~5V | Control proporcional mediante la señal de control remoto（0%~100%）<br>Cuando el modo de tensión es Manual, tensión de salida = Tensión de entrada/5 × tensión de salida máxima<br>Cuando el modo de tensión es Auto, velocidad de alimentación = Tensión de entrada/5 × velocidad de alimentación máxima |
| 0~10V | 0V~10V | Control proporcional mediante la señal de control remoto（0%~100%）<br>Cuando el modo de tensión es Manual, tensión de salida = Tensión de entrada/10 × tensión de salida máxima<br>Cuando el modo de tensión es Auto, velocidad de alimentación = Tensión de entrada/10 × velocidad de alimentación máxima |
| DigSym | Digital Sync | La tensión de la señal de control remoto es la tensión de entrada de control remoto de un dispositivo especificado en el bus (especificado mediante parámetros de sincronización de control remoto)<br>Control proporcional mediante la señal de tensión de entrada de control remoto de un dispositivo especificado en el bus, con un rango de tensión del 0% al 100%.<br>Cuando el modo de tensión es Manual, tensión de salida = Tensión de entrada/10 × tensión de salida máxima<br>Cuando el modo de tensión es Auto, velocidad de alimentación = Tensión de entrada/10 × velocidad de alimentación máxima |
