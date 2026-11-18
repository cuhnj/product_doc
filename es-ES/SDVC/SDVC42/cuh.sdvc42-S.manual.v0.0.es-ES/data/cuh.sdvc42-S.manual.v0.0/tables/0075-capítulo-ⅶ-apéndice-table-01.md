<!-- publish-data-sidecar: section=75 heading='7.4.8 Grupo de parámetros de comunicación' role=generic source_md=doc.md -->

| Función | Parámetro | Visualización | Rango de valores/Elemento de enumeración | Valor predeterminado |
|---|---|---|---|---|
| P8.01 | Tipo de comunicación 485BUS | 01.485type | ASCII, RTU | RTU |
| P8.02 | Velocidad en baudios de la comunicación 485 | 02.BaudRate | 0.3, 1.2, 2.4, 9.6, 19.2, 57.6, 115.2 Kbps | 115.2 |
| P8.03 | Número de identificación del esclavo de la comunicación 485 | 03.485SlvID | 1~31 | 1 |
| P8.04 | Habilitar resistencia del puerto de comunicación 485 | 04.Enab485R | None, Valid | None |
| P8.05 | Dirección de sincronización digital local | 05.DigSynAd | 1~8 |  |
| P8.06 | Habilitar resistencia del puerto de comunicación de sincronización digital | 06.EnabSynR | None, Valid | None |
| P8.07 | Dirección de señal de bus de la fuente de entrada lógica 1 del puerto de salida principal | 07.BSigMID1 | 1~8 |  |
| P8.08 | Dirección de señal de bus de la fuente de entrada lógica 2 del puerto de salida principal | 08.BSigMID2 | 1~8 |  |
| P8.09 | Dirección de señal de bus de la fuente de entrada lógica 1 del puerto D | 09.BSgD_ID1 | 1~8 |  |
| P8.10 | Dirección de señal de bus de la fuente de entrada lógica 2 del puerto D | 10.BSgD_ID2 | 1~8 |  |
| P8.11 | Dirección de bit de señal de bus de la fuente de entrada lógica 1 del puerto de salida principal | 11.BSigM_B1 | 1~16 | 5 |
| P8.12 | Dirección de bit de señal de bus de la fuente de entrada lógica 2 del puerto de salida principal | 12.BSigM_B2 | 1~16 | 6 |
| P8.13 | Dirección de bit de señal de bus de la fuente de entrada lógica 1 del puerto D | 13.BSigD_B1 | 1~16 | 5 |
| P8.14 | Dirección de bit de señal de bus de la fuente de entrada lógica 2 del puerto D | 14.BSigD_B2 | 1~16 | 6 |
| P8.15 | Señal de dirección de bit de la señal de bus local 1 | 15.LBSig_B1 | Véase el apéndice 7.4.11 | 0 |
| P8.16 | Señal de dirección de bit de la señal de bus local 2 | 16.LBSig_B2 | Véase el apéndice 7.4.11 | 1 |
| P8.17 | Señal de dirección de bit de la señal de bus local 3 | 17.LBSig_B3 | Véase el apéndice 7.4.11 | SpeedA |
| P8.18 | Señal de dirección de bit de la señal de bus local 4 | 18.LBSig_B4 | Véase el apéndice 7.4.11 | SpeedB |
| P8.19 | Señal de dirección de bit de la señal de bus local 5 | 19.LBSig_B5 | Véase el apéndice 7.4.11 | In_PtC |
| P8.20 | Señal de dirección de bit de la señal de bus local 6 | 20.LBSig_B6 | Véase el apéndice 7.4.11 | In_PtE |
| P8.21 | Señal de dirección de bit de la señal de bus local 7 | 21.LBSig_B7 | Véase el apéndice 7.4.11 | FCntSi |
| P8.22 | Señal de dirección de bit de la señal de bus local 8 | 22.LBSig_B8 | Véase el apéndice 7.4.11 | DCntSi |
| P8.23 | Señal de dirección de bit de la señal de bus local 9 | 23.LBSig_B9 | Véase el apéndice 7.4.11 | Ctr_O |
| P8.24 | Señal de dirección de bit de la señal de bus local 10 | 24.LBSigB10 | Véase el apéndice 7.4.11 | Warn |
| P8.25 | Señal de dirección de bit de la señal de bus local 11 | 25.LBSigB11 | Véase el apéndice 7.4.11 | Main |
| P8.26 | Señal de dirección de bit de la señal de bus local 12 | 26.LBSigB12 | Véase el apéndice 7.4.11 | -SpeedA |
| P8.27 | Señal de dirección de bit de la señal de bus local 13 | 27.LBSigB13 | Véase el apéndice 7.4.11 | -SpeedB |
| P8.28 | Señal de dirección de bit de la señal de bus local 14 | 28.LBSigB14 | Véase el apéndice 7.4.11 | -In_PtC |
| P8.29 | Señal de dirección de bit de la señal de bus local 15 | 29.LBSigB15 | Véase el apéndice 7.4.11 | -In_PtE |
| P8.30 | Señal de dirección de bit de la señal de bus local 16 | 30.LBSigB16 | Véase el apéndice 7.4.11 | -FCtSi |
| P8.31 | Habilitar función de incorporación a la red | 31.EnNetwok | Online, Offlin, Expand, Replace |  |
| P8.32 | Número de máquina de eliminación de la red | 32.DeltDevi | 1~8 |  |
| P8.33 | Número de sincronización de frecuencia local | 33.FrqncSyn | 1~8 |  |
| P8.34 | Número de sincronización de regulación de velocidad por control remoto local | 34.RemotSyn | 1~8 |  |
| P8.35 | Datos de control remoto | 35.RemotDat | ManVol, RemVol, ManSpd, RemSpd | ManVol |
