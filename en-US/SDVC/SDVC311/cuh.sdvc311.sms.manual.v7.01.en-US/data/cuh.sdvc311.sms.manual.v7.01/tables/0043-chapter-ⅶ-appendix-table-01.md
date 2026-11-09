<!-- publish-data-sidecar: section=43 heading='7.1 Parameter Table' role=generic source_md=doc.md -->

| Category | Definition | Symbol | Symbol Image | Range | Default |
|---|---|---|---|---|---|
| Common parameter | Output Voltage | U | ![Output Voltage segment symbol U](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-00.png) | 0~260 V | 150 |
| Basic Parameter | Output Frequency * | E | ![Output Frequency segment symbol E](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-01.png) | 5.0~400.0 Hz | 50.0 |
| | On Delay of the Intelligent Photoelectric Sensor | J | ![Intelligent photoelectric sensor on-delay segment symbol J](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-02.png) | 0.0~99.9 s | 0.2 |
| | Off Delay of the Intelligent Photoelectric Sensor | L | ![Intelligent photoelectric sensor off-delay segment symbol L](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-03.png) | 0.0~99.9 s | 0.2 |
| | Soft Startup | t | ![Soft Startup segment symbol t](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-04.png) | 0.0~10.0 s | 0.5 |
| | Breaking cycles/Soft Shutdown * | d | ![Breaking cycles/Soft Shutdown segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-05.png) | -100~0 cycle (number of breaking cycles)<br>0.0~10.0 s (Soft Shutdown) | 0.0 |
| | Output Voltage | U | ![Output Voltage segment symbol U](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-06.png) | 0~260 V | 150 |
| Advanced Parameter | Intelligent photoelectric sensor sensitivity | P | ![Sensor sensitivity segment symbol P](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-07.png) | PnP, nPn, 2~1000 | 80 |
| | Port C Sensor Type * | ΓA | ![Port C Sensor Type segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-08.png) | nPn, PnP<br>ut1 (Single scan), ut0 (Continuous scan) | ut0 |
| | On Delay of Port C | J- | ![On Delay of Port C segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-09.png) | 0.0~99.9 s | ![Segment symbol of the default value for Port C on-delay](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-22.png)<br>same as J |
| | Off Delay of Port C | L- | ![Off Delay of Port C segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-10.png) | 0.0~99.9 s | ![Segment symbol of the default value for Port C off-delay](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-23.png)<br>same as L |
| | The first signal source of Main output * | Cq | ![The first signal source of Main output segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-11.png) | 0, 1, b, -b, C, -C, od, -od, oq, -oq | b |
| | The second signal source of Main output * | Eq | ![The second signal source of Main output segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-12.png) | 0, 1, b, -b, C, -C, od, -od, oq, -oq | C |
| | Logic operation of signal sources of Main output * | nq | ![Logic operation of signal sources of Main output segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-13.png) | And, or, Xor, rS | or |
| | On Delay of Main output | Jq | ![On Delay of Main output segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-14.png) | 0.0~99.9 s | 0.0 |
| | Off Delay of Main output | Lq | ![Off Delay of Main output segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-15.png) | 0.0~99.9 s | 0.0 |
| | Output Mode of Main output | Fq | ![Output Mode of Main output segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-16.png) | dLy (Delay Mode), HLd (Hold Mode) | dLy |
| | Logic direction of Main output | oq | ![Logic direction of Main output segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-17.png) | ![Line segment symbols for same phase and reverse, labeled Same phase and Reverse](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-24.png)<br>on (always active), oFF (always inactive) | ![Default line segment symbol of Logic direction of Main output](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-25.png) |
| | The first signal source of Control Port D * | Cd | ![The first signal source of Control Port D segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-18.png) | 0, 1, b, -b, C, -C, od (Output state of Port D), -od, oq (Output state of Main output), -oq | 0 |
| | The second signal source of Control Port D * | Ed | ![The second signal source of Control Port D segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-19.png) | 0, 1, b, -b, C, -C, od (Output state of Port D), -od, oq (Output state of Main output), -oq | oq |
| | Logic operation of signal sources of Control Port D * | nd | ![Logic operation of signal sources of Control Port D segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-20.png) | And, or, Xor, rS | or |
| | On Delay of Port D | Jd | ![On Delay of Port D segment symbol](assets/images/cuh.sdvc311.sms.manual.v7.01/page-0045-vcrop-21.png) | 0.0~99.9 s | 0.0 |
