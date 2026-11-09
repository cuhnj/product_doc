<!-- publish-data-sidecar: section=79 heading='7.6 Error Code' role=generic source_md=doc.md -->

| Error Code | Display | Meaning | Method of Exclusion |
|---|---|---|---|
| Error01 | Short | Short circuit | Confirm whether the main output line is short-circuited and rewire it |
| Error02 | OvrCurrt | Overcurrent | Reduce the output voltage or increase the output frequency |
| Error03 | OverHot | Overheat | Place the controller in a well-ventilated and heat-dissipating area |
| Error04 | UndrCool | Undercooling | Place the controller in a place where the ambient temperature is higher than -20℃ |
| Error05 | CommErr | Communication error | Contact company technical support |
| Error06 | TSnerErr | Temperature sensor error | Contact company technical support |
| Error07 | OverVolt | Overvoltage | The input mains voltage cannot exceed 250V effective value |
| Error08 | UndrVolt | Undervoltage | The input mains voltage cannot be lower than 85V effective value |
| Error09 | LoadErr | Load disconnection | Check whether the output line is correctly connected to the vibration plate |
| Error10 | Send_Seed | Failed to send seed | Contact company technical support |
| Error11 | Send_Exit | The command to leave boot failed to execute | Contact company technical support |
| Error14 | SynchEr0 | CUHBus-DS® bus has 2 or more hosts | 1. If an alarm occurs, set the device offline and then set it online again.<br>2. After the newly added device is powered off, connect the CUHBus-DS® cable to the network device. |
| Error15 | SynchEr1 | Bus error | Confirm whether the CUHBus-DS® communication line is correctly connected, and correctly organize the network |
| Error16 | SynchEr2 | Sync device is not online | Synchronization communication network, frequency synchronization device or remote control synchronization device is not online |
