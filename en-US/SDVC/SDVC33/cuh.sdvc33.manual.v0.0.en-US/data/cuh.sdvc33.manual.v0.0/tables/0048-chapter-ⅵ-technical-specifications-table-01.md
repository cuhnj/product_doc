<!-- publish-data-sidecar: section=48 heading='7.3 Troubleshooting Suggestions and Error Explanations' role=generic source_md=doc.md -->

| Error Code | Definition (Phenomenon) | Troubleshooting Methods |
|---|---|---|
| Er01A/Er01b | Channel A/B short circuit<br>(Both channels stop outputs) | ◆ Make sure the load is not short-circuit, then try to restart output of the controller by press Output ON/OFF Button two times or repower the controller. |
| Er02 | Channel AB combined overcurrent<br>(Both channels pause output, after 2s restart) | ◆ Reduce output voltage appropriately, then restart the output. |
| Er02A/Er02b | Channel A/B individual overcurrent<br>(Overcurrent channel stops output, 2s restart) | |
| Er02A./Er02b. | Channel A/B individual overcurrent reaches the set maximum | |
| Er03 | Overheating or undercooling<br>(Both channels stop output, automatic recovery at -20℃~60℃) | ◆ Install the controller in a well-ventilated environment or avoid extreme cold. |
| Er041/Er042 | Power supply under/over voltage<br>(Both channels stop output, automatic recovery) | ◆ Make sure input voltage between AC 85~250Vac. |
| Er05 | Internal communication abnormal<br>(Both channels stop output) | ◆ Make sure no extern power supply connect to the 24V power port or contact our technical support. |
| Er06 | Temperature sensor abnormal<br>(Both channels stop output) | ◆ Make sure the work temperature not under -20℃ or contact our technical support. |
| Er07A/Er07b | Channel A/B Port D port short circuit<br>(Channel A/B control output stops, 2s try to restart) | ◆ Make sure the load of Port D is not short-circuit and the current does not exceed 350mA. |
| Er10 | 24V power output abnormal<br>(Turn off the 24V output, 2s try to restart) | ◆ Make sure 24V port is not short-circuit and the current does not exceed 700mA. |
| Er11 | 5V power output abnormal<br>(The speed control function is temporarily closed, and the automatic restart is restored) | ◆ Make sure the 5V power of Port A is not short-circuit or not connected to external power voltage more than 5V. |
| Er12 | 24V power supply voltage abnormal<br>(Both channels stop output, control output high impedance, automatic recovery) | ◆ Make sure no extern power supply connect to the 24V power port. |
