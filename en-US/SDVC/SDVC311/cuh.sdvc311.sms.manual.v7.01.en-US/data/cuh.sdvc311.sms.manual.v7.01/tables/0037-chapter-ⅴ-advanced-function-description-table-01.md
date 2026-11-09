<!-- publish-data-sidecar: section=37 heading='5.9 Parameter Password Lock Function' role=generic source_md=doc.md -->

| Lock parameter | Waveform Index | Acceleration Index | Maximum output voltage limit | Logic operation of signal sources of Main output | The second signal source of Main output | The first signal source of Main output | Logic operation of signal sources of Control Port D | The second signal source of Control Port D | The first signal source of Control Port D | Port C Sensor Type | Breaking cycles/Soft Shutdown | Output Frequency |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1: Locked | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
| 0: Unlocked | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| multiplication factor | 4 | 2 | 1 | 4 | 2 | 1 | 4 | 2 | 1 | 4 | 2 | 1 |
| Password value range (summation) | 0~7 (1st digit of password value) | | | 0~7 (2nd digit of password value) | | | 0~7 (3rd digit of password value) | | | 0~7 (4th digit of password value) | | |
| Example 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |
| | 0 | | | 0 | | | 0 | | | 1\*1=1 | | |
| Example 2 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 1 |
| | 1\*4=4 | | | 1\*1=1 | | | 0 | | | 1\*1=1 | | |
| Example 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 1 | 1 |
| | 0 | | | 0 | | | 0 | | | 1\*4+1\*2+1\*1=7 | | |
