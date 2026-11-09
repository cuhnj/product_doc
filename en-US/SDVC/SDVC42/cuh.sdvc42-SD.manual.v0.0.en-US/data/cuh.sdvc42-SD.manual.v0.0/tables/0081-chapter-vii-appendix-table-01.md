<!-- publish-data-sidecar: section=81 heading='7.7 Warning Code' role=generic source_md=doc.md -->

| Warning Code | Display | Meaning | Method of Exclusion |
|---|---|---|---|
| Warn01 | Saturate | Output saturation | Reduce output voltage |
| Warn02 | decline | count slowdown | Counting deceleration state |
| Warn03 | CND | End of count | Count end status |
| Warn04 | FrqncyLo | Output frequency is too low | Increase frequency offset parameter value |
| Warn05 | FrqncyHi | Output frequency is too high | Increase frequency offset parameter value |
| Warn06 | LoMAlarm | Lack of material | Reduce the material shortage alarm parameter value, or add materials to the material tray |
| Warn07 | PortDErr | Port D output overcurrent | Reduce output port control load |
| Warn08 | RemotLow | Remote control input voltage/current is too low | Increase the remote control input voltage or current |
| Warn09 | MRSErr | Main output RS logic error | When the output logic is an RS flip-flop, the main source 1 and main source 2 signals cannot be valid at the same time |
| Warn10 | 24VErr | 24V error | Do not connect the 24V external power supply to the controller output port |
| Warn11 | 5VErr | 5V error | Do not connect 5V external power supply to the controller output port |
| Warn12 | CtrlRSErr | Control output RS logic error | When the logic of D port is RS flip-flop,D port Source 1 and D port Source 2 signals cannot be valid at the same time |
| Warn13 | OverLoad | Acceleration sensor overload | Replace the acceleration sensor with an appropriate range |
| Warn14 | AcceleEr | Acceleration sensor failure | The sensor is damaged, replace it with a new one |
| Warn15 | EEPErr | Error saving parameters | Confirm that the CUHBus-DS® communication line is connected properly and the networking has been completed correctly. |
