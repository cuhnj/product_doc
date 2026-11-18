<!-- publish-data-sidecar: section=55 heading='Apéndice E: Descripción de advertencias y errores y sugerencias de solución de problemas' role=generic source_md=doc.md -->

| Visualización de falla | Tipo de falla | Sugerencias de solución de problemas |
|---|---|---|
| 24VErr | Error de alimentación interna de 24V | Fallo de la alimentación interna de 24V del controlador; contacte con nosotros para la reparación |
| 5VErr | Error de alimentación interna de 5V | Fallo de la alimentación interna de 5V del controlador; contacte con nosotros para la reparación |
| <2mA Err | La corriente de entrada de la señal de control remoto es demasiado baja en el puerto A | La corriente de entrada de la señal de control remoto es demasiado baja en el puerto A; asegúrese de que sea mayor que 2mA |
| <0.5V Err | La tensión de entrada de la señal de control remoto es demasiado baja en el puerto A | La tensión de entrada de la señal de control remoto es demasiado baja en el puerto A; asegúrese de que sea mayor que 0.5V |
| CommErr(1~5) | Error de comunicación | Contacte con nosotros para la reparación |
| decline | Deceleración de conteo | Cuando el número de conteo alcanza el "End Count" que usted ha ajustado, la tensión de salida (o la velocidad de alimentación) disminuye |
| EEPErr | Error al guardar los parámetros preajustados | Contacte con nosotros para la reparación |
| FrqncyHi | La frecuencia de referencia de sincronización es demasiado alta | La frecuencia de entrada de la señal de sincronización del controlador esclavo es superior a 400Hz<br>Asegúrese de que la frecuencia de la señal de sincronización esté entre 25 Hz y 400 Hz |
| FrqncyLo | La frecuencia de referencia de sincronización es demasiado baja | La frecuencia de entrada de la señal de sincronización del controlador esclavo es inferior a 25Hz<br>Asegúrese de que la frecuencia de la señal de sincronización esté entre 25 Hz y 400 Hz |
| OverHot | Sobrecalentamiento | La temperatura interna del controlador supera los 65℃<br>Asegúrese de que el controlador funcione en un entorno bien ventilado |
| OverLoad | Sobrecarga del sensor de vibración | El sensor de vibración ha detectado que la aceleración supera su valor de amplitud absoluta |
| OvrCurrt | Sobrecorriente | La corriente de salida del controlador supera los 3A |
| OvrVoltg | Sobretensión | La tensión de salida del controlador supera los 260V<br>Asegúrese de que el rango de tensión de entrada esté entre 85V y 260V |
| PortDErr | Error del puerto D | La desviación de tensión de salida del puerto D supera los 3V<br>Asegúrese de que la potencia de carga del puerto D no supere los 4.8W |
| PortPErr | Error del puerto P | La desviación de tensión de salida del puerto P supera los 3V<br>Asegúrese de que la potencia de carga del puerto P no supere los 4.8W |
| Saturate | Saturación de salida | Cuando la tensión de salida del controlador es mayor que la tensión de entrada, el controlador entra en el estado de saturación |
| Save | Guardado de parámetros preajustados | Después de la operación de búsqueda automática de la frecuencia de resonancia, sus parámetros relacionados se han guardado correctamente |
| SenorErr | Avería del sensor de vibración | La señal del sensor de vibración es anómala; contacte con nosotros para la reparación |
| SenTypEr | Error de tipo de sensor de vibración | El tipo de sensor de vibración conectado al controlador no coincide con el parámetro "tipo de sensor de vibración" ajustado en el controlador |
| Short | Cortocircuito | La salida del controlador está en cortocircuito; asegúrese de que el terminal de salida no esté en cortocircuito |
| SynchErr | Error de señal de sincronización | El cable de señal de sincronización no está conectado al controlador esclavo<br>Asegúrese de que el cable de señal de sincronización esté conectado correctamente al controlador |
| UndrVolt | Subtensión | La tensión de entrada del controlador es inferior a 85V.<br>Asegúrese de que el rango de tensión de entrada esté entre 85V y 260V |
| UpgradeSlv | Actualización de firmware | El firmware se está actualizando; el controlador vuelve a la normalidad después de la actualización |
