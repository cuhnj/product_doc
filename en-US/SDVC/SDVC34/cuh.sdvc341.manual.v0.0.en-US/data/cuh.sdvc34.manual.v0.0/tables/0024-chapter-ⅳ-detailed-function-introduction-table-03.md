<!-- publish-data-sidecar: section=24 heading='4.4.1.5 Main Mode' role=generic source_md=doc.md -->

| Remote Control Signal | Remote Control Signal | Output Voltage/Feeding Speed |
|---|---|---|
| Panel |  | Output Voltage and Feeding speed are not controlled by Remote Control Signal |
| 20mA | <2mA | When the Voltage Mode is Manual, Output Voltage = 0<br>When the Voltage Mode is Auto, Feeding Speed = 0<br>LCD display the error information "Remote control undervoltage" |
|  | 2mA~4mA | Output Voltage = 0, Feeding Speed = 0 |
|  | 4mA~20mA | Proportionally controlled by Remote Control Signal（0%~100%）<br>When the Voltage Mode is Manual, Output Voltage = (Input Current - 4mA)/16 × Max Output Voltage<br>When the Voltage Mode is Auto, Feeding Speed = (Input Current - 4mA)/16 × Max Feeding Speed |
| 1~5V | Less than 0.5V | Output Voltage = 0, Feeding Speed = 0<br>LCD display the error information "Remote control undervoltage" |
|  | 0.5V~1V | Output Voltage = 0, Feeding Speed = 0 |
|  | 1V~5V | Proportionally controlled by Remote Control Signal（0%~100%）<br>When the Voltage Mode is Manual, Output Voltage = (Input Voltage - 1V)/4 × Max Output Voltage<br>When the Voltage Mode is Auto, Feeding Speed = (Input Voltage - 1V)/4 × Max Feeding Speed |
| 0~5V | 0V~5V | Proportionally controlled by Remote Control Signal（0%~100%）<br>When the Voltage Mode is Manual, Output Voltage = Input Voltage/5 × Max Output Voltage<br>When the Voltage Mode is Auto, Feeding Speed = Input Voltage/5 × Max Feeding Speed |
| 0~10V | 0V~10V | Proportionally controlled by Remote Control Signal（0%~100%）<br>When the Voltage Mode is Manual, Output Voltage = Input Voltage/10 × Max Output Voltage<br>When the Voltage Mode is Auto, Feeding Speed = Input Voltage/10 × Max Feeding Speed |
| DigSym | Digital Sync | The voltage of the remote control signal is the remote control input voltage of a specified device on the bus (specified through remote control synchronization parameters)<br>Proportionally controlled by the remote control input voltage signal of a specified device on the bus, with a voltage range of 0% to 100%.<br>When the Voltage Mode is Manual, Output Voltage = Input Voltage/10 × Max Output Voltage<br>When the Voltage Mode is Auto, Feeding Speed = Input Voltage/10 × Max Feeding Speed |
