<!-- publish-data-sidecar: section=19 heading='4.3 Parámetros avanzados' role=generic source_md=doc.md -->

| Definición | Símbolo | Imagen del símbolo | Rango | Predeterminado |
|---|---|---|---|---|
| Retardo de conexión del puerto E | J- | ![Port E On Delay：数码管符号、范围及默认值](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-01.png) | 0.0~99.9 (s) | 0.0 |
| Retardo de desconexión del puerto E | L- | ![Port E Off Delay：数码管符号、范围及默认值](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-02.png) | 0.0~99.9 (s) | 0.0 |
| Retardo de conexión del puerto D | Jd | ![Port D On Delay：数码管符号、范围及默认值](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-03.png) | 0.0~99.9 (s) | 0.0 |
| Retardo de desconexión del puerto D | Ld | ![Port D Off Delay：数码管符号、范围及默认值](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-04.png) | 0.0~99.9 (s) | 0.0 |
| Tipo de puerto D | rd | ![Port D Type：数码管符号、范围及默认值](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-05.png) | nPn, PnP, PSP (push-pull) | nPn |
| Relación lógica del puerto C | F2 | ![Port C Logical Relation：参数符号及正负逻辑显示符号](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-06.png) | Lógica positiva, Lógica negativa | Lógica positiva |
| Relación lógica del puerto E | F1 | ![Port E Logical Relation：参数符号及正负逻辑显示符号](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-07.png) | Lógica positiva, Lógica negativa | Lógica positiva |
| Relación lógica de la salida de control | F3 | ![Ctrl Out Logical Relation：参数符号、逻辑选项及默认显示](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-08.png) | Lógica positiva, Lógica negativa,<br>Control por la señal de alarma | Lógica positiva |
| Operación lógica de la salida principal | F4 | ![Logic Operation of Main Output：参数符号、四种逻辑选项及默认显示](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-09.png) | Lógica positiva, Lógica negativa,<br>La salida principal es controlada por el puerto C, el puerto D es controlado por el puerto E<br>La salida principal es controlada por el puerto E, el puerto D es controlado por el puerto C | Lógica positiva |
| Operación lógica de la salida de control | F8 | ![Logic Operation of Ctrl Output：参数符号、逻辑选项及默认显示](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-10.png) | Lógica principal, El segundo grupo de lógica | Lógica principal |
| Tipo de sensor de conmutación<br>(Controlador con función RS485, sufijo R) | FA | ![Switch Sensor Type（R suffix）：数码管符号、范围及默认值](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-11.png) | Uto, nPn, PnP | Uto |
| Tipo de sensor de conmutación<br>(Controlador con función de conteo, sufijo J) | FA | ![Switch Sensor Type（J suffix）：数码管符号、范围及默认值](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-12.png) | nPn, PnP | nPn |
| Relación lógica de los puertos C y E | ∩ | ![Logic Relation of Port C and E：参数符号、And/or/Xor 图形及默认显示](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-13.png) | And, or, Xor | And |
| Dirección lógica del pulso de conteo<br>(Controlador con función de conteo, sufijo J) | Fb | ![Count Pulse Logic Direction：参数符号、下降沿和上升沿图形及默认显示](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-14.png) | Flanco descendente, Flanco ascendente | Flanco descendente |
| Dirección lógica del reinicio de conteo<br>(Controlador con función de conteo, sufijo J) | FC | ![Count Reset Logic Direction：参数符号、下降沿和上升沿图形及默认显示](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-15.png) | Flanco descendente, Flanco ascendente | Flanco descendente |
| Porcentaje de velocidad al finalizar el conteo<br>(Controlador con función de conteo, sufijo J) | u | ![Speed Percent of Count Ends：数码管符号、范围及默认值](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-16.png) | 0~100 | 30 |
| Número de conteo al final<br>(Controlador con función de conteo, sufijo J) | n | ![Count Number of Ends：数码管符号、范围及默认值](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-17.png) | 0~255 | 3 |
| Tiempo antirrebote de conteo<br>(Controlador con función de conteo, sufijo J) | U | ![Count Anti-jitter Time：数码管符号、范围及默认值](assets/images/cuh.sdvc34.manual.v0.0/page-0021-vcrop-18.png) | 0.001~2.000 (s) | 0.010 |
