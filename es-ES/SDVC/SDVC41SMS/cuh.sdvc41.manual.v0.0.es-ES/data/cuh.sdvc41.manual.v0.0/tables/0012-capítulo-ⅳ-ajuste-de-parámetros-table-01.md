<!-- publish-data-sidecar: section=12 heading='4.3 Parámetros avanzados' role=generic source_md=doc.md -->

| Parámetros comunes | Símbolo | Imagen del símbolo | Rango | Valor predeterminado |
|---|---|---|---|---|
| Retardo de conexión de los puertos E | J- | ![E Ports On Delay 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-01.png) | 0.0~20.0 s | --- |
| Retardo de desconexión de los puertos E | L- | ![E Ports Off Delay 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-02.png) | 0.0~20.0 s | --- |
| Relación lógica de los puertos C | Γ2 | ![C Ports Logical Relation 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-03.png) | `___` Lógica positiva　`_-_` Lógica negativa | --- |
| Relación lógica de los puertos E | Γ7 | ![E Ports Logical Relation 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-04.png) | `___` Lógica positiva　`_-_` Lógica negativa | --- |
| Relación lógica de la salida de control de 24V | Γ3 | ![24V Ctrl Out Logical Relation 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-05.png) | `___` Lógica positiva　`_-_` Lógica negativa<br>Afectado por la señal de alarma![Effect by alarm signal 对应阶梯形段码符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-19.png) | --- |
| Si la salida del controlador está o no controlada por la señal de control ON/OFF | Γ4 | ![ON/OFF Control Signal 控制使能数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-06.png) | `___` Relevante,　`_-_` No relevante | --- |
| Conmutación del grupo de parámetros lógicos predeterminado/alternativo | Γ8 | ![Default/Spare logic parameter group switch 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-07.png) | `___` Grupo de parámetros lógicos predeterminado<br>`_-_` Grupo de parámetros lógicos alternativo<br>`_=_` Clave de configuración del parámetro lógico alternativo | --- |
| Tipo de sensor de conmutación | ΓA | ![Switch Sensor Type 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-08.png) | Uto: Automático<br>nPn: Sensor tipo NPN<br>PnP: Sensor tipo PNP | Uto |
| Relación lógica de los puertos C y E | Π | ![Logical Relation of C Ports and E Ports 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-09.png) | OR, AND, XOR![OR、AND、XOR 的三组逻辑段码符号及文字](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-20.png) | AND |
| Tensión de salida máxima ajustable | h | ![Max Adjustable Output Voltage 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-10.png) | 20~220 V | 220 |
| Visualización de temperatura | C | ![Temperature Display 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-11.png) | -10.0~80.0 ℃ | Temperatura actual |
| Protocolo Modbus RS485 | Ver figura | ![RS485 Modbus Protocol 异形数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-12.png) | ASC, rtu | rtu |
| Dirección de comunicación | Ver figura | ![Communication Address 异形数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-13.png) | 1~31 | 1 |
| Velocidad en baudios de comunicación | Ver figura | ![Communication Baud Rate 异形数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-14.png) | 0.3, 1.2, 2.4, 9.6, 19.2, 57.6, 115.2 kbps | 9.6 |
| Contraseña de bloqueo de parámetros | Ver figura | ![Parameter Lock Password 异形数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-15.png) | 0~999 | --- |
| Estado de salida del controlador tras el encendido | Γd | ![Controller output status after powering on 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-16.png) | `___` On,　`_-_` Off,　Keep![On、Off、Keep 对应的段码符号及文字](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-21.png) | --- |
| Versión de firmware | Ur | ![Firmware Version 数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-17.png) | \ | Versión actual |
| Restablecimiento del controlador | 8.8.8.8.8. | ![Controller Reset 全段点亮数码管符号](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-18.png) | Listo para restablecer<br>Restablecimiento completado<br>![Controller Reset：全段点亮表示 Ready for Reset，五条横线表示 Reset Completed](assets/images/cuh.sdvc41.manual.v0.0/page-0014-vcrop-22.png) | \ |
