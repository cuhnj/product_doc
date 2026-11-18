<!-- publish-data-sidecar: section=37 heading='5.9 Función de bloqueo con contraseña de parámetros' role=generic source_md=doc.md -->

| Parámetro de bloqueo | Índice de forma de onda | Índice de aceleración | Límite de tensión de salida máxima | Operación lógica de las fuentes de señal de la salida principal | La segunda fuente de señal de la salida principal | La primera fuente de señal de la salida principal | Operación lógica de las fuentes de señal del puerto de control D | La segunda fuente de señal del puerto de control D | La primera fuente de señal del puerto de control D | Tipo de sensor del puerto C | Ciclos de frenado/Parada suave | Frecuencia de salida |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1: Bloqueado | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
| 0: Desbloqueado | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| factor de multiplicación | 4 | 2 | 1 | 4 | 2 | 1 | 4 | 2 | 1 | 4 | 2 | 1 |
| Rango del valor de contraseña (suma) | 0~7 (1.er dígito del valor de contraseña) | | | 0~7 (2.º dígito del valor de contraseña) | | | 0~7 (3.er dígito del valor de contraseña) | | | 0~7 (4.º dígito del valor de contraseña) | | |
| Ejemplo 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |
| | 0 | | | 0 | | | 0 | | | 1\*1=1 | | |
| Ejemplo 2 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 1 |
| | 1\*4=4 | | | 1\*1=1 | | | 0 | | | 1\*1=1 | | |
| Ejemplo 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 1 | 1 |
| | 0 | | | 0 | | | 0 | | | 1\*4+1\*2+1\*1=7 | | |
