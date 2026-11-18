<!-- publish-data-sidecar: section=67 heading='7.4 Lista de parámetros' role=generic source_md=doc.md -->

| | Parámetro | Visualización | Rango de valores/Elementos de enumeración | Predeterminado |
|---|---|---|---|---|
| Grupo de parámetros 4PhotoSen | Sensibilidad del sensor fotoeléctrico inteligente | 01.PortBLimit | PNP, NPN, 1~1000 | 80 |
| Grupo de parámetros 4PhotoSen | Dirección lógica del puerto B | 02.PortBDirec | Const, Inv | Const |
| Grupo de parámetros 4PhotoSen | Retardo de conexión del puerto B | 03.PortBUpDly | 0.0~99.9 s | 0.2 |
| Grupo de parámetros 4PhotoSen | Retardo de desconexión del puerto B | 04.PortBDnDly | 0.0~99.9 s | 0.2 |
| Grupo de parámetros 5On&Off | Tipo de sensor del puerto C | 01.PortType | NPN, PNP, Auto1, Auto0 | Auto0 |
| Grupo de parámetros 5On&Off | Dirección lógica del puerto C | 02.PortCDirec | Const, Inv | Const |
| Grupo de parámetros 5On&Off | Retardo de conexión del puerto C | 03.PortCUpDly | 0.0~99.9 s | 0.2 |
| Grupo de parámetros 5On&Off | Retardo de desconexión del puerto C | 04.PortCDnDly | 0.0~99.9 s | 0.2 |
| Grupo de parámetros 6DCoutput | Fuente de entrada lógica del puerto D 1 | 01.PortDSour1 | 0, 1, PortB, -PortB, PortC, -PortC, PortD, -PortD, Main, -Main, Err, -Err | 0 |
| Grupo de parámetros 6DCoutput | Fuente de entrada lógica del puerto D 2 | 02.PortDSour2 | 0, 1, PortB, -PortB, PortC, -PortC, PortD, -PortD, Main, -Main, Err, -Err | Main |
| Grupo de parámetros 6DCoutput | Relación lógica del puerto D | 03.PortDLogic | And, Or, Xor, RS | Or |
| Grupo de parámetros 6DCoutput | Retardo de conexión del puerto D | 04.PortDUpDly | 0.0~99.9 s | 0.0 |
| Grupo de parámetros 6DCoutput | Retardo de desconexión del puerto D | 05.PortDDnDly | 0.0~99.9 s | 0.0 |
| Grupo de parámetros 6DCoutput | Modo de salida del puerto D | 06.PortDMode | Delay, Hold, Cycle1, Cycle2 | Delay |
| Grupo de parámetros 6DCoutput | Dirección lógica del puerto D | 07.PortDDirec | Const, Revrs, On, Off | Const |
| Grupo de parámetros 6DCoutput | Tipo de salida de control | 08.PortDType | Ou_NPN, Ou_PNP, Ou_P&P | Ou_NPN |
| Grupo de parámetros 7Save | Leer todos los parámetros del grupo de usuario | 01.ReadALLFrm | None, UsrD1, UsrD2, UsrD3 | None |
| Grupo de parámetros 7Save | Guardar todos los parámetros en el grupo de usuario | 02.SaveALLTo | None, Work, UsrD1, UsrD2, UsrD3 | None |
| Grupo de parámetros 7Save | Restauración de la configuración predeterminada | 03.RestorALL | None, Work | None |
| Grupo de parámetros 7Save | Identificador de máquina local | 04.LoadType | None, Circ, Line, Soli | None |
| Grupo de parámetros 7Save | Número de identificación | 05.MachineNum | None, 1~1000 | None |
| Grupo de parámetros 7Save | Contraseña de usuario | 06.PassWord | 0~9999 | 0 |
| Grupo de parámetros 8Monitor | Temperatura | 01.Temperatur | -20~85 ℃ | —— |
| Grupo de parámetros 8Monitor | Corriente de salida | 02.CurrentOut | 0.0~150 mA | —— |
| Grupo de parámetros 8Monitor | Tensión de señal del puerto A | 03.Vol_Remote | 0.0~5.0 V | —— |
| Grupo de parámetros 8Monitor | Tensión de señal del puerto B | 04.Vol_PortB | 0~999 | —— |
| Grupo de parámetros 8Monitor | Tensión de señal del puerto C | 05.Vol-PortC | 0.0~26.0 V | —— |
| Grupo de parámetros 8Monitor | Tensión de señal del puerto D | 06.Vol-PortD | 0.0~26.0 V | —— |
| Grupo de parámetros 8Monitor | Tensión en tiempo real del puerto de 5V | 07.Vol-5V | 0.0~6.0 V | —— |
| Grupo de parámetros 8Monitor | Tensión en tiempo real del puerto de 24V | 08.Vol-24V | 0.0~26.0 V | —— |
| Grupo de parámetros 8Monitor | Versión del software de la placa de control | 09.Version | 0~99.99 | —— |
