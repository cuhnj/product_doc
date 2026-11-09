<!-- publish-data-sidecar: section=55 heading='Appendix F: Run State and Network Card Type Description' role=generic source_md=doc.md -->

| State of the controller display | State Type | Description |
|---|---|---|
| RUN | The controller is Run | Output of the controller is valid |
| MAN | The controller is stopped | Short press the “ON/OFF” button to switch the Run/Stop state of output of the controller |
| CND | The count process is finished to stop the controller | When the count process is finished, the output of controller is stopped |
| RMT | Stop the output of the controller remotely | Stop the output of the controller remotely by RS485 or Ethernet communication |
| STP | Port C/E to stop output of the controller | Stop output of the controller by Digital Input Port C/E |
| Lok | Keypad lock | The On/OFF button and Encoding is disable and long press the Encoding Switch to unlock keypad |
| ERR | Stop output of the controller caused by count fault | When the value of "Main Logic" is "Count", if the clear and count up operation occur simultaneously in counting process, the output of controller is stopped |
