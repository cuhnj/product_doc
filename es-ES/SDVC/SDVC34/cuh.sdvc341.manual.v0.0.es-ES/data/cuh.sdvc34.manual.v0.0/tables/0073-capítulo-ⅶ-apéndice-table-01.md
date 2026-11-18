<!-- publish-data-sidecar: section=73 heading='7.7 Código de advertencia' role=generic source_md=doc.md -->

| Código de advertencia | Visualización | Significado | Método de exclusión |
|---|---|---|---|
| Warn01 | Saturate | Saturación de la salida | Reduzca la tensión de salida |
| Warn02 | decline | Ralentización del conteo | Estado de desaceleración del conteo |
| Warn03 | CND | Fin del conteo | Estado de fin del conteo |
| Warn04 | FrqncyLo | Frecuencia de salida demasiado baja | Aumente el valor del parámetro de desviación de frecuencia |
| Warn05 | FrqncyHi | Frecuencia de salida demasiado alta | Aumente el valor del parámetro de desviación de frecuencia |
| Warn06 | LoMAlarm | Falta de material | Reduzca el valor del parámetro de alarma de falta de material o añada material a la bandeja de material |
| Warn07 | PortDErr | Sobrecorriente de salida del puerto D | Reduzca la carga de control del puerto de salida |
| Warn08 | RemotLow | Tensión/corriente de entrada del control remoto demasiado baja | Aumente la tensión o la corriente de entrada del control remoto |
| Warn09 | MRSErr | Error de lógica RS de la salida principal | Cuando la lógica de salida es un bistable RS, las señales de la fuente principal 1 y de la fuente principal 2 no pueden ser válidas al mismo tiempo |
| Warn10 | 24VErr | Error de 24V | No conecte la alimentación externa de 24V al puerto de salida del controlador |
| Warn11 | 5VErr | Error de 5V | No conecte la alimentación externa de 5V al puerto de salida del controlador |
| Warn12 | CtrlRSErr | Error de lógica RS de la salida de control | Cuando la lógica del puerto D es un bistable RS, las señales de la fuente 1 del puerto D y de la fuente 2 del puerto D no pueden ser válidas al mismo tiempo |
| Warn13 | OverLoad | Sobrecarga del sensor de aceleración | Sustituya el sensor de aceleración por otro con un rango adecuado |
| Warn14 | AcceleEr | Fallo del sensor de aceleración | El sensor está dañado; sustitúyalo por uno nuevo |
| Warn15 | EEPErr | Error al guardar los parámetros | Confirme que la línea de comunicación CUHBus-DS® está correctamente conectada y que la conexión en red se ha realizado correctamente. |
