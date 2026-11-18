<!-- publish-data-sidecar: section=32 heading='4.5 Control de velocidad remoto' role=generic source_md=doc.md -->

| Tipo de señal de control remoto | Señal de control remoto | Tensión de salida/Velocidad de alimentación |
|---|---|---|
| Panel | | La tensión de salida y la velocidad de alimentación no están controladas por la señal de control remoto |
| 20mA | <2mA | Cuando el modo de tensión es manual, tensión de salida = 0<br>Cuando el modo de tensión es automático, velocidad de alimentación = 0<br>La pantalla LCD muestra la información de error "<2mA Err" |
| | 2mA~4 mA | Tensión de salida = 0, velocidad de alimentación = 0 |
| | 4 mA ~20mA | Control proporcional mediante la señal de control remoto (0%~100%)<br>Cuando el modo de tensión es manual, tensión de salida = (corriente de entrada - 4mA)/16 × Tensión de salida máxima<br>Cuando el modo de tensión es automático, velocidad de alimentación = (corriente de entrada - 4mA)/16 × Velocidad de alimentación máxima |
| 1~5V | <0.5V | Tensión de salida = 0, velocidad de alimentación = 0<br>La pantalla LCD muestra la información de error "<0.5V Err" |
| | 0.5V~1V | Tensión de salida = 0, velocidad de alimentación = 0 |
| | 1V~5V | Control proporcional mediante la señal de control remoto (0%~100%)<br>Cuando el modo de tensión es manual, tensión de salida = (tensión de entrada 1V)/4 × Tensión de salida máxima<br>Cuando el modo de tensión es manual, tensión de salida = (tensión de entrada 1V)/4 × Tensión de salida máxima |
| 0~5V | 0V~5V | Control proporcional mediante la señal de control remoto (0%~100%)<br>Cuando el modo de tensión es manual, tensión de salida = tensión de entrada/5 × Tensión de salida máxima<br>Cuando el modo de tensión es automático, velocidad de alimentación = tensión de entrada/5 × Velocidad de alimentación máxima |
| 0~10V | 0V~10V | Control proporcional mediante la señal de control remoto (0%~100%)<br>Cuando el modo de tensión es manual, tensión de salida = tensión de entrada/10 × Tensión de salida máxima<br>Cuando el modo de tensión es automático, velocidad de alimentación = tensión de entrada/10 × Velocidad de alimentación máxima |
| Meter (potenciómetro) | Relación de división del potenciómetro <4% | Tensión de salida = 0, velocidad de alimentación = 0 |
| | La relación de división del potenciómetro es 4%~96% | Control proporcional mediante la señal de control remoto (0%~100%)<br>Cuando el modo de tensión es manual, tensión de salida = ((relación de división - 4%)/92%)× Tensión de salida máxima<br>Cuando el modo de tensión es automático, velocidad de alimentación = ((tensión de entrada tensión interna × 4%)/tensión interna × 92%) × Velocidad de alimentación máxima |
