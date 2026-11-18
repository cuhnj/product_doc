<!-- publish-data-sidecar: section=31 heading='4.4.1.7 Fuente de control remoto' role=generic source_md=doc.md -->

| Señal de control remoto | Señal de control remoto | Tensión de salida/Velocidad de alimentación |
|---|---|---|
| Panel |  | La tensión de salida y la velocidad de alimentación no se controlan mediante señal de control remoto |
| 20mA | &lt;2mA | Cuando el modo de tensión es Manual, Tensión de salida = 0<br>Cuando el modo de tensión es Auto, Velocidad de alimentación = 0<br>La pantalla LCD muestra la información de error "Remote control undervoltage" |
| 20mA | 2mA~4mA | Tensión de salida = 0, Velocidad de alimentación = 0 |
| 20mA | 4mA~20mA | Control proporcional mediante señal de control remoto（0%~100%）<br>Cuando el modo de tensión es Manual, Tensión de salida = (Corriente de entrada - 4mA)/16 × Tensión de salida máx.<br>Cuando el modo de tensión es Auto, Velocidad de alimentación = (Corriente de entrada - 4mA)/16 × Velocidad de alimentación máx. |
| 1~5V | Menos de 0.5V | Tensión de salida = 0, Velocidad de alimentación = 0<br>La pantalla LCD muestra la información de error "Remote control undervoltage" |
| 1~5V | 0.5V~1V | Tensión de salida = 0, Velocidad de alimentación = 0 |
| 1~5V | 1V~5V | Control proporcional mediante señal de control remoto（0%~100%）<br>Cuando el modo de tensión es Manual, Tensión de salida = (Tensión de entrada - 1V)/4 × Tensión de salida máx.<br>Cuando el modo de tensión es Auto, Velocidad de alimentación = (Tensión de entrada - 1V)/4 × Velocidad de alimentación máx. |
| 0~5V | 0V~5V | Control proporcional mediante señal de control remoto（0%~100%）<br>Cuando el modo de tensión es Manual, Tensión de salida = Tensión de entrada/5 × Tensión de salida máx.<br>Cuando el modo de tensión es Auto, Velocidad de alimentación = Tensión de entrada/5 × Velocidad de alimentación máx. |
| 0~10V | 0V~10V | Control proporcional mediante señal de control remoto（0%~100%）<br>Cuando el modo de tensión es Manual, Tensión de salida = Tensión de entrada/10 × Tensión de salida máx.<br>Cuando el modo de tensión es Auto, Velocidad de alimentación = Tensión de entrada/10 × Velocidad de alimentación máx. |
| DigSym | Digital Sync | La tensión de la señal de control remoto es la tensión de entrada de control remoto de un dispositivo determinado en el bus (especificado mediante los parámetros de sincronización de control remoto)<br>Control proporcional mediante la señal de tensión de entrada de control remoto de un dispositivo determinado en el bus, con un rango de tensión del 0% al 100%.<br>Cuando el modo de tensión es Manual, Tensión de salida = Tensión de entrada/10 × Tensión de salida máx.<br>Cuando el modo de tensión es Auto, Velocidad de alimentación = Tensión de entrada/10 × Velocidad de alimentación máx. |
