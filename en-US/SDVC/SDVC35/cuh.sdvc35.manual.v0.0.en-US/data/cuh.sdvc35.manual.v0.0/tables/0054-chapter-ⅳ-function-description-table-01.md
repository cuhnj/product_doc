<!-- publish-data-sidecar: section=54 heading='Appendix E: Warning and Error Description and Troubleshooting Suggestions' role=generic source_md=doc.md -->

| Fault Display | Fault Type | Troubleshooting Suggestions |
|---|---|---|
| 24VErr | Internal 24V Power Error | Internal 24V Power of the controller failure, please contact us for repair |
| 5VErr | Internal 5V Power Error | Internal 5V Power of the controller failure, please contact us for repair |
| <2mA Err | The Input Current of Remote Control Signal is too low to Port A | The Input Current of Remote Control Signal is too low to Port A, so make it is greater than 2mA |
| <0.5V Err | The Input Voltage of Remote Control Signal is too low to Port A | The Input Voltage of Remote Control Signal is too low to Port A, so make it is greater than 0.5V |
| CommErr(1~5) | Communication Error | Please contact us for repair |
| decline | Counting deceleration | When the count number reaches the "End Count" that you set, the output voltage (or Feeding Speed) decreases |
| EEPErr | Saving Preset Parameters Error | Please contact us for repair |
| FrqncyHi | Sync Reference Frequency is too high | Input Frequency of Sync Signal of slave controller is greater than 400Hz<br>Make sure the frequency of sync signal is from 25 Hz to 400 Hz |
| FrqncyLo | Sync Reference Frequency is too low | Input Frequency of Sync Signal of slave controller is less than 25Hz<br>Make sure the frequency of sync signal is from 25 Hz to 400 Hz |
| OverHot | OverHeat | Internal temperature of the controller exceeds 65℃<br>Make sure the controller work at well-ventilated environment |
| OverLoad | OverLoad of vibration sensor | Vibration sensor has detected the acceleration exceeds its absolute amplitude value |
| OvrCurrt | OverCurrent | Output Current of controller exceeds 3A |
| OvrVoltg | OverVoltage | Output Voltage of controller exceeds 260V<br>Make sure the input voltage range is from 85V to 260V |
| PortDErr | Port D Error | Output Voltage Deviation of Port D exceeds 3V<br>Make sure the load power of Port D does not exceed 4.8W |
| PortPErr | Port P Error | Output Voltage Deviation of Port P exceeds 3V<br>Make sure the load power of Port P does not exceed 4.8W |
| Saturate | Output Saturation | When Output Voltage of the controller is greater than Input Voltage, the controller enters the saturation state |
| Save | Saving Preset Parameters | After Automatic Resonant Frequency Search operation, its related parameters are saved successfully |
| SenorErr | Vibration Sensor Fault | The vibration sensor signal is abnormal, please contact us for repair |
| SenTypEr | Vibration Sensor Type Error | The type of vibration sensor connected to the controller is mismatched with the "vibration sensor type" parameter set in the controller |
| Short | Short-circuit | Output of the controller is short-circuit, Make sure the output terminal is not short-circuit |
| SynchErr | Sync Signal Error | Sync signal wire is not connected to the slave controller<br>Make sure the sync signal wire is connected correctly to the controller |
| UndrVolt | UnderVoltage | Input Voltage of the controller is less than 85V.<br>Make sure the input voltage range is from 85V to 260V |
| UpgradeSlv | Firmware Update | The firmware is updating, the controller go back to normal after the update |
