<!-- publish-data-sidecar: section=56 heading='Apéndice F: Descripción del estado de funcionamiento y del tipo de tarjeta de red' role=generic source_md=doc.md -->

| Estado mostrado del controlador | Tipo de estado | Descripción |
|---|---|---|
| RUN | El controlador está en marcha | La salida del controlador es válida |
| MAN | El controlador está detenido | Pulse brevemente el botón “ON/OFF” para conmutar el estado de marcha/parada de la salida del controlador |
| CND | El proceso de conteo ha finalizado para detener el controlador | Cuando el proceso de conteo finaliza, la salida del controlador se detiene |
| RMT | Detener la salida del controlador de forma remota | Detenga la salida del controlador de forma remota mediante comunicación RS485 o Ethernet |
| STP | El puerto C/E detiene la salida del controlador | Detenga la salida del controlador mediante la entrada digital puerto C/E |
| Lok | Bloqueo del teclado | El botón ON/OFF y el codificador están deshabilitados; mantenga pulsado el conmutador codificador para desbloquear el teclado |
| ERR | Detención de la salida del controlador causada por fallo de conteo | Cuando el valor de "Main Logic" es "Count", si la operación de borrado y conteo se produce simultáneamente en el proceso de conteo, la salida del controlador se detiene |
