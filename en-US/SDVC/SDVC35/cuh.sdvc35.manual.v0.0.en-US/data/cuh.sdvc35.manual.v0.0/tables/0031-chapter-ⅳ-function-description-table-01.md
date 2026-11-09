<!-- publish-data-sidecar: section=31 heading='4.5 Remote Speed Control' role=generic source_md=doc.md -->

| The type of Remote control signal | Remote control signal | Output Voltage/Feeding Speed |
|---|---|---|
| Panel | | Output Voltage and Feeding speed are not controlled by Remote Control Signal |
| 20mA | <2mA | When the Voltage Mode is Manual, Output Voltage = 0<br>When the Voltage Mode is Auto,Feeding Speed = 0<br>LCD display the error information "<2mA Err" |
| | 2mA~4 mA | Output Voltage = 0, Feeding Speed = 0 |
| | 4 mA ~20mA | proportional controlled by Remote Control Signal (0%~100%)<br>When the Voltage Mode is Manual, Output Voltage = (Input Current - 4mA)/16 ×Max Output Voltage<br>When the Voltage Mode is Auto, Feeding Speed = (Input Current - 4mA)/16 ×Max Feeding Speed |
| 1~5V | <0.5V | Output Voltage = 0, Feeding Speed = 0<br>LCD display the error information "<0.5V Err" |
| | 0.5V~1V | Output Voltage = 0, Feeding Speed = 0 |
| | 1V~5V | proportional controlled by Remote Control Signal (0%~100%)<br>When the Voltage Mode is Manual, Output Voltage = (Input Voltage 1V)/4 ×Max Output Voltage<br>When the Voltage Mode is Manual, Output Voltage = (Input Voltage 1V)/4 ×Max Output Voltage |
| 0~5V | 0V~5V | proportional controlled by Remote Control Signal (0%~100%)<br>When the Voltage Mode is Manual, Output Voltage = Input Voltage/5 × Max Output Voltage<br>When the Voltage Mode is Auto, Feeding Speed = Input Voltage/5 ×Max Feeding Speed |
| 0~10V | 0V~10V | proportional controlled by Remote Control Signal (0%~100%)<br>When the Voltage Mode is Manual, Output Voltage = Input Voltage/10 × Max Output Voltage<br>When the Voltage Mode is Auto, Feeding Speed = Input Voltage/10 ×Max Feeding Speed |
| Meter (Potentiometer) | Divider Ratio of Potentiometer <4% | Output Voltage = 0, Feeding Speed = 0 |
| | Divider Ratio of Potentiometer is 4%~96% | proportional controlled by Remote Control Signal (0%~100%)<br>When the Voltage Mode is Manual, Output Voltage = ((Divider Ratio - 4%)/92%)× Max Output Voltage<br>When the Voltage Mode is Auto, Feeding Speed =((Input Voltage Internal Voltage × 4%)/Internal Voltage × 92%) ×Max Feeding Speed |
