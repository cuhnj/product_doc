<!-- publish-data-sidecar: section=53 heading='Appendix D: Troubleshooting Suggestions and Error Explanation' role=generic source_md=doc.md -->

| | Fault Phenomenon | Troubleshooting Suggestions |
|---|---|---|
| 1 | No display after power on | • Make sure the power outlet is live<br>• Make sure the Input power Cable is reliably connected to the power outlet |
| 2 | Display normally, but no output | • Make sure the output voltage is not small<br>• Make sure the run state of the controller is not “Man” controlled by press the “ON/OFF” button on panel<br>• Make sure the run state of the controller is not “STP” controlled by the Port C/E<br>• Make sure the run state of the controller is not “STP” controlled by the Logical Direction parameter of Port C/E<br>• Reset the controller by Default Setting Restoration adjusted in Function Group 8 |
| 3 | The Port C/E cannot work normally | • Make sure the ON/OFF control signal wire is connected correctly to the Port C/E<br>• Make sure all the parameters of Port C/E which you have adjusted are correct<br>• Reset the controller by Default Setting Restoration adjusted in Function Group 8 |
| 4 | Beat Effect | • Connect the Sync Signal Wire between the controllers and set the slave controller to sync mode |
| 5 | Display normally, sounds can be heard from the vibratory feeder but no output | • Make sure Output Frequency is not far away from resonant frequency of the vibratory feeder<br>• Reset the controller by Default Setting Restoration adjusted in Function Group 8 |
