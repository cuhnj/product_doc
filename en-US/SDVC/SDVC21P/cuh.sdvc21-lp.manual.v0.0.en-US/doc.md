---
doc_id: cuh.sdvc21-lp.manual.v0.0.en-US
doc_key: cuh.sdvc21-lp.manual.v0.0
doc_type: manual
lang: en-US
product: sdvc21-lp
source_pdf: /Users/wangle/Documents/Python开发/说明书转换/典型文档/SDVC2/20250905_67_IDP1000415_SDVC21P_SMS-EN_5_01-文档发布.pdf
source_sha256: 498080965b2b80cef117cf2a0b76db36363c17872ba737f216c6681fca9b974f
title: 20250905 67 IDP1000415 SDVC21-lp SMS-EN 5 01-文档发布
updated_at: 2026-09-17 02:18:38
version: 0.0
---



# Variable Voltage Digital Controller for Vibratory Feeder

**IP67**

![Product photo of two CUH variable voltage digital controllers for vibratory feeder](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0001-vcrop-00.png)

## Instruction Book of SDVC21P Series

**Variable Voltage Digital Controller for Vibratory Feeder**



---

## Preface

Thank you for choosing CUH Digital Vibratory Feeder Controllers. (The controller for short in the following text)

This instruction book includes notes for installing, debugging, parameter setting, maintaining and trouble shooting of the controller. Please read this instruction book carefully before operating the controller and keep it properly.

### This instruction book applies to the following model:

➔Intelligent Digital Voltage Stabilizing Vibratory Feeder Controller SDVC21-LP  
➔Intelligent Digital Voltage Stabilizing Vibratory Feeder Controller SDVC21-XLP

---


---

## Notice

- Never hot swap nor touch the contacts in any case to avoid electric shock or other accidents.
- Never switch the input of the controller by way of cutting off power supply through a relay or other devices, otherwise service life of the controller may reduced severely.
- Don't open the shell without authorization, otherwise its water-proof, oil-proof and dust-proof may be failure.
- Never operate the controller under the condition that beyond its designed limits.
- Operate the controller in accordance with this instruction book strictly. We will not assume any civil or criminal liability if the equipment damage or personal injury is caused by incorrect operation.

> **!**
>
> Never open the controller shell to avoid electric shock. Contact CUH if the controller breaks down.
>
> Never try to revamp the controller since the solid state circuit boards inside the controller can not be repaired, and there's no adjustable part.

---


# Operating Environment

## Inspections Before Using

Every controller will go through rigorous quality inspection before delivery and is packed with crash-proof packaging.

## Please Check the Following Items After Unpacking:

- Whether the controller is damaged in appearance
- Whether model of the controller are exactly what you ordered

## Runtime Environment

Please follow the notes below to ensure better performance and longer lifetime of the controller

- Well-ventilated environment
- Keep away from the corrosive and flammability gas and liquid
- Firmly fixed to avoid vibration
- Keep away from electromagnetic interference
- Operating within the temperature range of 0 °C to 40 °C
- For use at altiude 2000m or lower

---


# Contents

| Section | Page |
|---|---:|
| Chapter I　Features | 1 |
| Chapter II　Installation Guide | 3 |
| Chapter III　Components Descriptions | 4 |
| Chapter IV　Function Descriptions | 6 |
| 4.1 Output Voltage Setting | 6 |
| 4.2 Output Frequency Setting | 7 |
| 4.3 Frequency Display Character parameter Setting | 7 |
| 4.4 Soft Startup Time Setting | 8 |
| 4.5 Output Switch | 8 |
| 4.6 Maximum Output Voltage Restriction | 9 |
| 4.7 Default Settings Restoration | 10 |
| Chapter V　Sensors and Signal Control | 11 |
| 5.1 Intelligent Photoelectric Sensing | 11 |
| 5.2 Using Method of the Switch Sensor | 15 |
| 5.3 Using Method of the 2ⁿᵈ Switch Sensor | 18 |
| 5.4 Logical Relation Setting of the Control Signal | 21 |
| 5.5 Controlling Output | 22 |
| 5.6 Remote Speed Control | 26 |
| 5.7 Preset Speed Switch | 27 |
| Chapter VI　Security Functions | 28 |
| 6.1 Automatic Digital Voltage Stabilizing | 28 |
| 6.2 Short-Circuit Protection | 28 |
| 6.3 Current Overload Protection | 28 |
| 6.4 Overheat Protection | 28 |
| 6.5 Ambient temperature derating curve (only applied for SDVC21-XLP) | 28 |

## Appendix

| Section | Page |
|---|---:|
| Appendix A: Dimensions | 29 |
| Appendix B: Output Interface Definition | 31 |
| Appendix C: Signal Interface Definition | 31 |
| Appendix D: LED Displayed Characters Definition | 34 |
| Appendix E: Electrical Specification | 35 |
| Appendix F: Trouble Shooting Tips and Error Explanations | 36 |
| Appendix G: Absolute Parameters | 37 |

---



# ChapterⅠ Features

The controller is specially designed for controlling vibratory feeder in the automation systems. Combined with the latest electronic technology and elaborate design, the controller provides the following convenient and practical features:

**Protection Level:** IP67, This controller can work in the environment which are wet, oil pollution or dust.

**Ultra Wide Operating Voltage Range:** This controller's input voltage range is from AC 85V to 440V.

**Automatic Voltage Stabilizing:** The controller can eliminate feeding speed variation caused by mains voltage fluctuation.

**Voltage Adjusting:** Output voltage ranges from 0V to 440V.

**Soft Startup:** In order to avoid sudden shock to the work pieces, the controller can gently increase output voltage from 0 to the pre-set value when startup.

**Soft Startup Time Setting:** Soft Startup Time can be set exactly in digital numbers.

**Halt when Work-pieces are full:** A switch sensor can help to halt the controller when work-pieces are full and to fulfill the functions of Soft Startup Time Setting, Startup Delay, Shutdown Delay, and Logical Relation Adjusting.

**Controlling Output:** The Controlling Output signal outgoing from the transistor can coordinate a solenoid or other external devices with the controller.

**Overheat Protection:** The controller will halt its output to protect itself when operation temperature is too high.

**Current Overload Protection:** The controller will halt its output to ensure operating safety of the equipment when operation current exceeds its rated value.

## The Following Features Can be Customized:

**Dual Control Signals Input:** Dual control signals input of Work-pieces-Full and Work-piece-Empty could form the logical control relation of AND, OR, NOT, XOR, and all the others.

**Output Voltage Preset Function:** Up to four preset output voltage values can be chosen by external control signals.

**Intelligent Photoelectric Sensing:** Our adaptive Intelligent Photoelectric Sensor can help to stall the controller when work-pieces are full or work-pieces are empty and to fulfill the functions of Inching Startup Time Setting, Startup Delay, Shutdown Delay, and Logical Relation Adjusting.

**Remote Speed Control:** Output voltage of the controller can be controlled by an external potentiometer, a PLC, or a voltage control signal ranging form 1V to 5V.

---


---

**CUH** attaches great importance to the product quality management and safety performance. Apart form the high-quality components we use and rigorous quality control system, **CUH** has taken account of possible accidents users may encounter and provides the following protective functions to maximum the controller's practicability.

**Short-Circuit Protection:** If output of the controller is short-circuited, the controller will halt its output until restarted.

**Current Overload Protection:** The controller will halt its output to ensure equipments' operating safety when operation current exceeds its rated value.

**Overheat Protection:** The controller will halt its output to protect itself when operation temperature is too high.

**CUH** controllers are strictly compliant with CE certification.

---


# Chapter Ⅱ Installation Guide

## Step One:

Open the packing box and connect the Output Power Cable to the vibrator's electromagnetic coils.

![Output power cable connection diagram: the two Output Pins of the White Wire are connected to the vibrator's electromagnetic coils; the Ground Wire (Yellow and Green Dual Color) is connected to the grounding point.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0009-vcrop-00.png)

**⚠ Note:**

Make sure the vibrator's electromagnetic coils is connected to the two output pins of the Output Power Cable and the electromagnetic coils is reliably grounded otherwise series security incident may occur.

## Step Two:

![Input power cable diagram: the Black Wire branches into L Wire (Brown), L Wire (380V) / N Wire (220V) (Blue) and Ground Wire (Yellow and Green Dual Color).](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0009-vcrop-01.png)

---


# Chapter III Components Descriptions

There are 4 buttons on the control panel including the `FUNC` button to shift among different functions, the ▲ button to increase the parameter value, the ▼ button to decrease the parameter value and the `ON/OFF` button.

## Keyboard Description

![Controller appearance and keypad description diagram, with callouts for indicators, parameter increase/decrease buttons, FUNC button and ON/OFF button.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0010-vcrop-00.png)

- **Output Voltage Indicator:** The indicator lights up as the controller enters Output Voltage Adjusting status.
- **Output Frequency Indicator:** The indicator lights up as the controller enters Output Frequency Adjusting status.
- **Startup Delay Indicator:** The indicator lights up as the controller enters Startup Delay Time Adjusting status.
- **Shutdown Delay Indicator:** The indicator lights up as the controller enters Shutdown Delay Time Adjusting status.
- **Advanced Parameter Increasing Button & Advanced Parameter Decreasing Button:** Advanced parameters can be adjusted by these two buttons.
- **FUNC Button:** Shift advanced parameters by pressing this button.
- **Soft Power Switch Button:** Startup or shutdown output of the controller by pressing this button

---


## Descriptions of the Status Indicators

![Controller status indicator diagram with labeled callouts](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0011-vcrop-00.png)

- **Remote Speed Control Indicator:** The indicator lights up when Remote Speed Control signal is available.
- **Speed A Indicator:** The indicator lights up as the corresponding external control signal is available.
- **Speed B Indicator:** The indicator lights up as the corresponding external control signal is available.
- **Saturation Indicator:** The indicator lights up when the preset Output Voltage value exceeds Input Voltage value.
- **Stop Indicator:** The indicator lights up as Output of the controller is shutdown by the ON/OFF button.
- **LED displayer:** The LED displayer indicates the adjustable parameter at present.

## I/O Interface Descriptions

![SDVC21-LP (10A) I/O interface diagram](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0011-vcrop-01.png)

**SDVC21-LP (10A)**

- Fuse
- Waterproof breathable valve
- Signal Wire Inlet (Black Wire)
- Output Power Socket (White Wire)
- Input Power Socket (Black Wire)

![SDVC21-XLP (25A) I/O interface diagram showing Signal, Output and Input](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0011-vcrop-02.png)

**SDVC21-XLP (25A)**

Note: When used in high oil pollution environments, it is necessary to regularly check the surface of the waterproof and breathable valve to prevent the exhaust hole of the waterproof and breathable valve from being blocked by oil pollution.

---


## Chapter Ⅳ Function Descriptions

### 4.1 Output Voltage Setting

The output voltage can be set directly and digitally through the control panel. Benefit from the unique voltage stabilizing function, output voltage of the controller won't fluctuate as the input voltage does. So that a vibrator can work stably in unstable input voltage environment.

- Turn on the controller by connecting Input power cable.
- The Output Voltage Indicator lights up as the controller enters Output Voltage Adjusting status when the LED displays the voltage symbol H and the previously set voltage value.
- Adjust the Output Voltage value by pressing the ▲ or ▼ button.

![Output voltage setting panel diagram: H–represents Output Voltage; Output Voltage value is set as 80V at present; Output Voltage Indicator. A hand points to the ▲ button.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0012-vcrop-00.png)

- Output Voltage value of the controller can not exceed Input Voltage value. If Output Voltage value is set close to Input Voltage value, the controller fails to stabilize its voltage output and the Saturation Indicator lights up.
- If Output Voltage value is set too close to zero, the controller fails to stabilize its voltage output and the Saturation Indicator lights up.

![Saturation indicator diagram: the Saturation Indicator callout points to the illuminated Saturated indicator on the panel.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0012-vcrop-01.png)

---


## 4.2 Output Frequency Setting

For SDVC21-LP, there are two output frequencies to choose from, Full Wave-Doubled input frequency value and Half Wave -input frequency value.

For SDVC21-XLP, there are four output frequencies to choose from, full wave, half wave, one third of full wave and one quarter of full wave.

- Press the **FUNC** button repeatedly until Shifting to the Output Frequency Adjusting status (E) as the Output Frequency Indicator lights up.
- Press the ▲ or ▼ button to adjust the output frequency.

![Output frequency setting controller diagram: E-represents Output Frequency; Frequency Setting Indicator; hand pressing FUNC.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0013-vcrop-00.png)

> The displayed characters of the output frequency value can be set through the Frequency Display Character parameter.Please refer to section 4.3.

## 4.3 Frequency Display Character parameter Setting

- Press the **FUNC** and hold for two seconds to enter the Advanced parameters setting interface.
- Press the **FUNC** button repeatedly to switch to the “ΓE” parameter which defines frequency display character.
- Press ▲ or ▼ to adjust this parameter value.

![Frequency display character setting controller diagram: ΓE-represents frequency display; frequency display character.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0013-vcrop-01.png)

> When the “ΓE” parameter is set to “-5”, the displayed characters will be 100, 50, 33 or 25.  
> When the “ΓE” parameter is set to “-6”, the displayed characters will be 120, 60, 40 or 30.  
> When the “ΓE” parameter is set to “-E”, the displayed characters will be “FUL”, “HAF”, “trd” or “Foh”.

---


## 4.4 Soft Startup Time Setting

In order to avoid sudden shock to the work pieces, the controller can gently increase Output Voltage from 0 to the pre-set value when startup.

Soft Startup Time (t): The period of time it takes for the controller to gently increase Output Voltage from 0 to the pre-set value when startup.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until Shifting to the Soft Startup Time djusting status (t) as the Soft Startup Indicator lights up.
- Press ▲ or ▼ button to adjust the parameter value. The parameter unit is second, and the numerical precision is 0.1.

*Adjustable Soft Startup Time ranges from 0.0 second to 9.9 seconds.*

*Default value of the Soft Startup Time parameter is 1 second.*

![Soft Startup Time setting diagram: t represents Soft Startup Time; Soft Startup Time is set as 1.0 second at present. A hand presses the FUNC button.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0014-vcrop-00.png)

## 4.5 Output Switch

The soft-touch Output Switch Button on the panel can turn on/off the controller's output quickly and easily.

- Press the **ON/OFF** button to turn on/off the controller's output. The Stop Indicator lights up as output of the controller is turned off.

> Due to the soft-touch switch and digital signal control technology, no spark will generate to spoil the contact. As a result, life-span of the controller and the vibrator will be extended greatly.

![Output Switch diagram: The Stop Indicator lights up as the controller is shutdown by the ON/OFF button. A hand presses ON/OFF.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0014-vcrop-01.png)

---


## 4.6 Maximum Output Voltage Restriction

Maximum Output Voltage of the controller can be set to prevent damage to the vibrator. Remote Speed Control function is affected by this parameter.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Maximum Output Voltage Restriction status (h).
- Press the ▲ or ▼ button to adjust the parameter value.

![Controller panel showing h440, with callouts: “h-represents Maximum Output Voltage” and “Maximum Output Voltage Value is set as 440V at present”.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0015-vcrop-00.png)

*Default value of the Maximum Output Voltage is 380V*

---


## 4.7 Default Settings Restoration

This function allows the operator to restore all default parameter settings.

Due to the abundant functions of the controller, many parameters can be adjusted. In order to avoid the circumstance that after too many times modification by a beginner, the controller can not work properly, this function allows the operator to restore default settings to the controller in an easy way.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until full screen is flashing, and then press the ▲ button and hold until “----” is displayed which means default settings have been restored.
- After releasing the ▲ button, the controller enters Output Voltage Adjusting status (H). By this time, all parameters have been restored to default values.

![Ready to restore: the controller display flashes in full screen](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0016-vcrop-00.png)

![Restore successfully: the controller restores default settings successfully](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0016-vcrop-01.png)

---


# Chapter V Sensors and Signal Control

The controller can be controlled by many kinds of external signals and sensors. This chapter mainly elaborates using method of the Intelligent Photoelectric Sensor, the Switch Sensors and the PLC.

## 5.1 Intelligent Photoelectric Sensing

Combined with the SDVC-S1 Photoelectric Sensor the function of Intelligent Photoelectric Sensing can be achieved. The SDVC-S1 sensor can filter the interference of background light impacting on the sensitivity of the controller. As a result, the controller can work reliably without manual sensitivity adjustment.

### 5.1.1 Connection Method of the SDVC-S1 Intelligent Photoelectric Sensor

Connect the SDVC-S1 sensor to the terminals of the controller according to the diagram

![SDVC-S1 sensor wiring diagram showing TX and RX, Red, White and Copper Wire connections to the numbered 15-pin connector.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0017-vcrop-00.png)

*Notice:*  
*Default logical relation of the sensor is set as work-pieces are empty*

---


## 5.1.2 Startup Delay Time and Shutdown Delay Time Adjusting of the Intelligent Photoelectric Sensor

In most actual applications, the output of the controller should be delayed for a period of time when Startup or Shutdown of the controller is controlled by external signals. Startup Delay Time and Shutdown Delay Time Adjusting function made this kind of application possible. Furthermore, shocks to the work pieces as the controller starts up can be eliminated by adjusting Soft Startup Time.

### Startup Delay (J)

The period of time the controller goes through from receiving a startup control signal to outputting.

- Press the **FUNC** button repeatedly until shifting to the Startup Delay Time Adjusting status (J) as the Startup Delay Time Indicator on the panel lights up.
- Adjust the parameter by pressing the ▲ or ▼ button. The parameter unit is second, and the numerical precision is 0.1.

*Adjustable range of the parameter is from 0.0 to 9.9 seconds*  
*Default value of the parameter is 0.2 seconds*

![Startup Delay control panel diagram: J represents Startup Delay Time; the On Delay indicator lights up; a hand presses the FUNC button.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0018-vcrop-00.png)

### Shutdown Delay (L)

The period of time the controller goes through from receiving a shutdown control signal to cutting off output.

- Press the **FUNC** button repeatedly until shifting to the Shutdown Delay Time Adjusting status (L) as the Shutdown Delay Time Indicator on the panel lights up.
- Adjust the parameter by pressing the ▲ or ▼ button. The parameter unit is second, and the numerical precision is 0.1.

*Adjustable range of the parameter is from 0.0 to 9.9 seconds*  
*Default value of the parameter is 0.2 seconds*

![Shutdown Delay control panel diagram: L represents Shutdown Delay Time; the Off Delay indicator lights up; a hand presses the FUNC button.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0018-vcrop-01.png)

---


### 5.1.3 Logical Relation Adjusting of the Intelligent Photoelectric Sensor

Under normal circumstances, the receiving end of the Intelligent Photoelectric Sensor receives no optical signal, and the controller runs by default. But in some special applications the controller needs to be stopped when the receiving end receives no optical signal. Adjusting this parameter can fulfill these kind of applications.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until Shifting to the Logical Relation Adjusting status of the Intelligent Photoelectric Sensor.
- Adjust the parameter by pressing the ▲ or ▼ button.

![Logical Relation of the Intelligent Photoelectric Sensor — Normal Open: controller LED display, callouts and FUNC button operation.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0019-vcrop-00.png)

- When Logical Relation is set as Normal Open, namely no optical signal received, the controller runs.
- When Logical Relation is set as Normal Close, namely no optical signal received, the controller stops.

![Logical Relation of the Intelligent Photoelectric Sensor — Normal Close: controller LED display, callouts and FUNC button operation.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0019-vcrop-01.png)

*The parameter is set as Normal Open by default*

---


## 5.1.4 The CUH Intelligent Photoelectric Sensor Sensitivity Parameter Setting

Parameter P means the sensitivity of the CUH intelligent photoelectric sensor, i.e. sensing distance of the CUH intelligent photoelectric sensor.

The smaller parameter P value is, the more sensitive the sensor will be and the longer distance it can receive.

- Press the **FUNC** and hold for two seconds to enter the Advanced parameters setting interface.
- Press the **FUNC** button repeatedly for entering to the Intelligent Photoelectric Sensitivity adjustment parameter interface. The LED symbol of this parameter is “P”.
- Press ▲ or ▼ to adjust this parameter value.

![Controller panel displaying P 80, with callouts: “P-represents intelligent photoelectric sensitivity” and “The default value is 80”.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0020-vcrop-00.png)

The parameter value range is from 0 to 999, and the default value is 80.

---


## 5.2 Using Method of the Switch Sensor

The controller can operate with many kinds of sensors such as switch sensors, optical switch sensors and fiber optic sensors.

### 5.2.1 Connection Method of the Switch Sensor

Connect the Proximity Switch Sensor to the terminals of the controller according to the diagram.

![Proximity switch sensor connection diagram: Signal Wire to pin 10, Ground Wire to pin 12, and +24V Output to pin 11.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0021-vcrop-00.png)

### Convention

The blue wire represents ground wire  
The black wire represents signal wire  
The brown wire represents power wire.

---


## 5.2.2 Startup Delay Time and Shutdown Delay Time Setting of the Switch Sensor

By default, Intelligent Photoelectric Sensor and Switch Sensor share the same Startup Delay Time and Shutdown Delay Time. Operators can also set Startup Delay Time and Shutdown Delay Time of the Switch Sensor independently.

### Startup Delay (J-)

The period of time the controller goes through from receiving a startup control signal to outputting.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Startup Delay Time Adjusting status (`J---`).
- Adjust the parameter by pressing the ▲ or ▼ button. The parameter unit is second, and the numerical precision is 0.1.

*Adjustable range of the parameter is from 0.0 to 9.9 seconds*  
*Default value of the parameter is J---*  
*The independent Startup Delay of the Switch Sensor will be closed when the parameter value is adjusted to 0*

![Startup Delay controller panel and callouts: J represents Startup Delay Time, - represents Switch Sensor; Startup Delay Time is set as 3 seconds.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0022-vcrop-00.png)

### Shutdown Delay (L-)

The period of time the controller goes through from receiving a shutdown control signal to cutting off output.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Shutdown Delay Time Adjusting status (`L---`).
- Adjust the parameter by pressing the ▲ or ▼ button. The parameter unit is second, and the numerical precision is 0.1.

*Adjustable range of the parameter is from 0.0 to 9.9 seconds*  
*Default value of the parameter is L---*  
*The independent Shutdown Delay of the Switch Sensor will be closed when the parameter value is adjusted to 0*

![Shutdown Delay controller panel and callouts: L represents Shutdown Delay Time, - represents Switch Sensor; Shutdown Delay Time is set as 2 seconds.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0022-vcrop-01.png)

> ➔ When J- and L- values are adjusted to 0, Startup Delay Time and Shutdown Delay Time of the Switch Sensor will be the same with Startup Delay Time and Shutdown Delay Time of the Intelligent Photoelectric Sensor.
>
> ➔ Startup Delay Time and Shutdown Delay Time of the Intelligent Photoelectric Sensor will not affected by the parameter of J- or L-.

---


## 5.2.3 Logical Relation Setting of the Switch Sensor (Halt when work-pieces are full)

Under normal circumstances, the controller receives no signal from the Switch Sensor and runs by default. But in some special applications the controller needs to be stopped when receives no signal from the Switch Sensor. Adjusting this parameter can fulfill these kind of applications.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until Shifting to the Logical Relation Adjusting status of the Switch Sensor (Γ1).
- Adjust the parameter by pressing the ▲ or ▼ button.

![Switch Sensor logical relation setting: Γ1 represents Logical Relation of the Switch Sensor; Normal Open. Controller display and FUNC button operation illustration.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0023-vcrop-00.png)

> ➔ When Logical Relation is set as Normal Open, namely no signal received, the controller runs.
>
> ➔ When Logical Relation is set as Normal Close, namely no signal received, the controller stops.

![Switch Sensor logical relation setting: Γ1 represents Logical Relation of the Switch Sensor; Normal Close. Controller display and FUNC button operation illustration.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0023-vcrop-01.png)

*The parameter is set as Normal Open by default*

---


## 5.3 Using Method of the 2<sup>nd</sup> Switch Sensor

The controller allows three sensors connecting to it, one Intelligent Photoelectric Sensor and two Switch Sensors. The functions of Halt when work-pieces are full and Halt when work-pieces are empty can work with the help of these sensors.

### 5.3.1 Connection Method of the 2<sup>nd</sup> Switch Sensor

Connect the 2<sup>nd</sup> Proximity Switch Sensor to the terminals of the controller according to the diagram.

![Second proximity switch sensor wiring diagram: Signal Wire to terminal 14, Ground Wire to terminal 12, and +24V Output to terminal 11.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0024-vcrop-00.png)

**Commonly**

The blue wire represents ground wire  
The black wire represents signal wire  
The brown wire represents power wire

---


### 5.3.2 Startup Delay Time and Shutdown Delay Time Setting of the 2ⁿᵈ Switch Sensor

By default, Intelligent Photoelectric Sensor and the two Switch Sensors share the same Startup Delay Time and Shutdown Delay Time. Operators can also set Startup Delay Time and Shutdown Delay Time independently for the 2ⁿᵈ Switch Sensor.

**Startup Delay (J_):** The period of time the controller goes through from receiving a startup control signal to outputting.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Startup Delay Time Adjusting status (`J_--`)
- Adjust the parameter by pressing the ▲ or ▼ button. The parameter unit is second, and the numerical precision is 0.1.

*Adjustable range of the parameter is from 0.0 to 9.9 seconds*  
*Default value of the parameter is `J_--`*  
*The independent Startup Delay of the 2ⁿᵈ Switch Sensor will be closed when the parameter value is adjusted to 0*

![Startup Delay setting diagram: J represents Startup Delay Time, the underscore represents 2ⁿᵈ Switch Sensor; displays J_3.0, Startup Delay Time is set as 3 seconds. The On Delay indicator on the panel lights up; a hand points to the FUNC button.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0025-vcrop-00.png)

**Shutdown Delay (L_):** The period of time the controller goes through from receiving a shutdown control signal to cutting off output.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Shutdown Delay Time Adjusting status (`L_--`).
- Adjust the parameter by pressing the ▲ or ▼ button. The parameter unit is second, and the numerical precision is 0.1.

*Adjustable range of the parameter is from 0.0 to 9.9 seconds*  
*Default value of the parameter is `L_--`*  
*The independent Shutdown Delay of the 2ⁿᵈ Switch Sensor will be closed when the parameter value is adjusted to 0*

![Shutdown Delay setting diagram: L represents Shutdown Delay Time, the underscore represents 2ⁿᵈ Switch Sensor; displays L_3.0, Shutdown Delay Time is set as 3 seconds. The Off Delay indicator on the panel lights up; a hand points to the FUNC button.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0025-vcrop-01.png)

- When J_ and L_ values are adjusted to 0, Startup Delay Time and Shutdown Delay Time of the 2ⁿᵈ Switch Sensor will be the same with Startup Delay Time and Shutdown Delay Time of the Intelligent Photoelectric Sensor.
- Startup Delay Time and Shutdown Delay Time of the Intelligent Photoelectric Sensor will not affected by the parameter of J_ or L_.

---


## 5.3.3 Logical Relation Setting of the 2ⁿᵈ Switch Sensor (Halt when work-pieces are full)

Under normal circumstances, the controller receives no signal from the 2ⁿᵈ Switch Sensor and runs by default. But in some special applications the controller needs to be stopped when receives no signal from the 2ⁿᵈ Switch Sensor. Adjusting this parameter can fulfill these kind of applications.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Logical Relation Adjusting status of the 2ⁿᵈ Switch Sensor (Γ3)
- Adjust the parameter by pressing the ▲ or ▼ button.

![2nd Switch Sensor logical relation: Normal Open. Controller panel with Γ3 display, leader lines and FUNC button operation.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0026-vcrop-00.png)

> - When Logical Relation is set as Normal Open, namely no signal received, the controller runs.
> - When Logical Relation is set as Normal Close, namely no signal received, the controller stops.

![2nd Switch Sensor logical relation: Normal Close. Controller panel with Γ3 display, leader lines and FUNC button operation.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0026-vcrop-01.png)

*The parameter is set as Normal Open by default*

---


## 5.4 Logical Relation Setting of the Control Signal

The controller can set the logical relation of the Intelligent Photoelectric Sensor and the Switch Sensor when they work simultaneously.

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Logical Relation Adjusting status of the Control Signal (Π).
- Adjust the parameter by pressing the ▲ or ▼ button.

![Logical Relation parameter set to OR: LED display, callouts and FUNC button operation.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0027-vcrop-00.png)

![Logical Relation parameter set to AND: LED display, callouts and FUNC button operation.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0027-vcrop-01.png)

![Logical Relation parameter set to XOR: LED display, callouts and FUNC button operation.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0027-vcrop-02.png)

- **Logical relation AND:** The controller runs only when both the Intelligent Photoelectric Sensor and the Switch Sensor asks the controller to.
- **Logical relation OR:** The controller runs when the Intelligent Photoelectric Sensor or the Switch Sensor asks the controller to.
- **Logical relation XOR:** The controller runs only when the Intelligent Photoelectric Sensor and the Switch Sensor output the opposite control signal.

*Logical relation of the parameter is set as AND by default.*

---


## 5.5 Controlling Output

The controller can output low-voltage controlling signal to cooperate with other devices such as a solenoid valve, a PLC or an electrical relay.

### 5.5.1 Connection Method of the Controlling Output

**Connection method of the controlled PLC**

Connect signal wire and ground wire of the controller to the terminals of the controller according to the diagram.

![PLC and controller interface wiring diagram, including Controlling Output, Controlling Output +24V and interface pin numbers.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0028-vcrop-00.png)

> Relay type or source type of output port of PLC can be connected to the controller and the voltage specification of output port is 24V.

---


### 5.5.2 Connection Method of the Controlled Solenoid Valve

![Solenoid Valve wiring diagram: Controlling Output to terminal 15, Controlling Output +24V to terminal 11.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0029-vcrop-00.png)

➔ The controller can directly drive a solenoid valve whose rated voltage is 24V and rated power lower than 4W.

### 5.5.3 Connection Method of the Electrical Relay

![Electrical relay wiring diagram: relay terminal 4 connects to interface terminal 15 via Controlling Output, relay terminal 5 connects to interface terminal 11 via Controlling Output +24V; contact terminals 2, 1, 3 also shown.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0029-vcrop-01.png)

➔ The controller can directly drive an electrical relay whose rated voltage is 24V and rated power lower than 4W.

---


## 5.5.4 Logical Relation Setting of the Controlling Output

- Press the **FUNC** button and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Logical Relation Adjusting status of the Controlling Output (Γ4).
- Adjust the parameter by pressing the ▲ or ▼ button.

![Controlling output logical relation setting diagram: Γ4 represents Logical Relation of the Controlling Output; Normal Open. Including controller LED display, buttons and FUNC operation.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0030-vcrop-00.png)

![Controlling output logical relation setting diagram: Γ4 represents Logical Relation of the Controlling Output; Normal Close. Including controller LED display, buttons and FUNC operation.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0030-vcrop-01.png)

> - When Logical Relation is set as Normal Open, the Controlling Output works as the controller runs.
> - When Logical Relation is set as Normal Close, the Controlling Output doesn't work as the controller runs.

---


## 5.5.5 Parameter Setting of Allocating the Control Signals to the Output of the Controller or DC Output for Controlling Separately

- Press the **FUNC** and hold for two seconds to enter the Advanced parameters setting interface.
- Press the **FUNC** button repeatedly for entering to the adjustment parameter interface. The LED symbol of this parameter is “Γ5”.
- Press ▲ or ▼ to adjust this parameter value.

![Controller panel and callouts: Γ5-represents adjustment parameter interface; Factory Default Status](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0031-vcrop-00.png)

- When the Γ5 is set to “![Both digits show only the bottom horizontal segment](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0031-vcrop-01.png)”, the output to the vibrator and the DC output are all controlled by the ON/OFF button on the control panel and the logical operation result of the CUH intelligent photoelectric sensor and two switch sensors.
- When the Γ5 is set to “![Left digit shows the bottom horizontal segment, right digit shows the top horizontal segment](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0031-vcrop-02.png)”, the output to the vibrator is controlled by ON/OFF button on the control panel. The DC output is controlled by the logical operation result of the CUH intelligent photoelectric sensor and two switch sensors.
- When the Γ5 is set to “![Left digit shows the bottom horizontal segment, right digit shows the top and bottom horizontal segments](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0031-vcrop-03.png)”, the output to the vibrator is controlled by ON/OFF button on the control panel and controlled by logical operation result of two switch sensors. The DC output is controlled by the CUH intelligent photoelectric sensor.
- When the Γ5 is set to “![Left digit shows the top horizontal segment, right digit shows the top and bottom horizontal segments](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0031-vcrop-04.png)”, output to the vibrator is controlled by ON/OFF button on the control panel and the CUH intelligent photoelectric sensor. The DC output is controlled by the logical operation result of two switch sensors.

---


## 5.6 Remote Speed Control

The function of Remote Speed Control allows the operator to control the Output Voltage by an external potentiometer or a control signal ranging from 1V to 5V. Thus, external remote speed control can be easily achieved by a PLC, a DCS or some other devices.

Remote Speed Control function becomes effective to the controller when the controlling signal exceeds 0.5V. Meanwhile, Remote Speed Control Indicator on the panel lights up and the ▲ and ▼ buttons lose effectiveness. The LED displayer shows current Output Voltage if the controller is running in the Output Voltage Adjusting status.

There are linear relationship between 1~5 V controlling voltage and 0~440V Output Voltage

### Connection method of the external potentiometer

![External potentiometer connection diagram. Note: Please select linearity potentiometer with the resistance of 1k. Labels: Remote Speed Control Power Supply; Remote Speed Control Input; Ground Wire of the Remote Speed Control.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0032-vcrop-00.png)

### Connection method of the PLC

![PLC connection diagrams: 1~5V Output to External Voltage Input Port, with Ground; 4~20mA Output to External Current Input Port, with Ground.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0032-vcrop-01.png)


## 5.7 Preset Speed Switch

The function of Preset Speed Switch can choose the preset speed by means of external control signals, such as a PLC, a PC, sensors or other signal sources to build up a multi-speed feeding control system.

The controller supports two remote speed control switch. The Speed A switch and the Speed B switch are both Low Level effective.

![Speed A and Speed B switch wiring diagram](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0033-vcrop-00.png)

Each speed control switch has a corresponding indicator on the panel. When the controller receives an effective signal, the corresponding indicator will light up.

The two indicators indicate 4 statuses. (A lights up and B goes out, A goes out and B lights up, both light up, both go out). The diagram to the right shows the status that both speed control switches are given effective signals.

![Controller panel with Speed A Indicator and Speed B Indicator](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0033-vcrop-01.png)

By means of speed control switches, the controller shifts to the corresponding speed. The output voltage corresponding to the speed can be adjusted by pressing ▲ or ▼ button. And the adjusted voltage will be stored automatically. As soon as the speed control signal is received, the controller outputs the corresponding voltage immediately.

---


## Chapter VI Security Functions

### 6.1 Automatic Digital Voltage Stabilizing

The internal digital voltage stabilizing function of the controller can stabilize feeding speed regardless of mains voltage fluctuation.

### 6.2 Short-Circuit Protection

If output is short-circuited, the controller will halt its output and display Err02 until restarting the controller.

### 6.3 Current Overload Protection

The controller will halt its output if output current exceeds rated current caused by faulty operation and display Err02 to protect the controller and customer equipments.

### 6.4 Overheat Protection

The controller will halt its output if operation temperature exceeds 65⁰C and display Err03 to protect the controller until operation temperature drops to 60⁰C.

### 6.5 Ambient temperature derating curve (only applied for SDVC21-XLP)

Under the condition of air nature convection, when the ambient temperature rises, due to the limitation of the heat dissipation capacity of the controller, the controller can't continuously output 25A current. Refer to the derating curve as below for using.

If you want the controller can continuously output 25A current, please provide better cooling conditions.

![Ambient temperature derating curve: Output Current (A) versus Ambient Temperature (°C). Output remains at 25 A up to 31.6 °C, then decreases linearly to 0 A at 60 °C.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0034-vcrop-00.png)

---


## Appendix A: Dimensions (mm)

### SDVC21-LP

![SDVC21-LP top view dimension drawing: 174±0.2, 110±0.1, 90, 10, 4-R2.50, 60±0.2, 2-R2.10, 2-R4.10, unit mm.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0035-vcrop-00.png)

![SDVC21-LP side view dimension drawing: 190±0.20, 98.9±0.2, unit mm.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0035-vcrop-01.png)

---


## SDVC21-XLP

![SDVC21-XLP outline top view dimension drawing, marked 174±0.2, 170±0.2, 120, 10, 4-R2.50, 90±0.2, 2-R2.10, 2-R4.10.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0036-vcrop-00.png)

![SDVC21-XLP outline side view dimension drawing, marked 98.9±0.2, 190±0.20.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0036-vcrop-01.png)

---


## Appendix B: Output Interface Definition

![Device interface diagram: Signal Wire Inlet (Black Wire), Output Power Socket (White Wire), Input Power Socket (Black Wire).](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0037-vcrop-00.png)

### Cross Section View:

![Cable cross section: the brown and blue wires of the White Wire (Output) correspond to the two Output pins, the yellow-green dual color wire corresponds to GND; the brown wire of the Black Wire (Input) corresponds to L, the blue wire corresponds to N, the yellow-green dual color wire corresponds to GND.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0037-vcrop-01.png)

**⚠ Notice:**

A: Make sure the electromagnetic coils of the vibrator is connected to the two output pins of the Output Power Cable socket and the shell of the vibrator is reliably earthed, otherwise series security incident may occur.

B: After welding, make sure the blank area is enswathed by insulating tape or heat-shrinkable tube before insert it into the Output Power Cable socket to avoid electrical leakage or short-circuit.

## Appendix C: Signal Interface Definition

![15-pin signal interface definition diagram. 1: Remote Speed Control (+5V); 2: Photosensor (GND); 3: Photosensor Rx; 4: Photosensor (GND); 5: Photosensor Tx; 6: Remote Speed Control (GND); 7: RGND; 8: Remote Speed Control (Input); 9: Pset A (Low voltage level is valid); 10: Switch Sensor Input (NPN type: Low voltage level is valid; PNP type: High voltage level is valid); 11: Control Output (+24V); 12: Control Output (GND); 13: Pset B (Low voltage level is valid); 14: Switch Sensor II Input (NPN type: Low voltage level is valid; PNP type: High voltage level is valid); 15: Control Output.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0037-vcrop-02.png)

---


## Port A: Remote Speed Control

![Port A: Remote Speed Control circuit and interface definition, with +5V, 10uF, 249Ω callouts.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0038-vcrop-00.png)

| Port | Pin | Signal |
|---|---|---|
| A3 | ① | +5V |
| A2 | ⑧ | Input |
| A1 | ⑦ | RGND |

## Port B: Intelligent Photosensor

![Port B: Intelligent Photosensor circuit and interface definition, with P+12, +5V callouts.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0038-vcrop-01.png)

| Port | Pin | Signal |
|---|---|---|
| B4 | ⑤ | Tx |
| B3 | ④ | GND |
| B2 | ③ | Rx |
| B1 | ② | GND |

## Port C: Switch Sensor

![Port C: Switch Sensor circuit and interface definition, with NPN, PNP, +24V callouts.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0038-vcrop-02.png)

| Port | Pin | Signal |
|---|---|---|
| C1 | ⑫ | GND |
| C2 | ⑩ | Input |
| C3 | ⑪ | +24V |

## Port D: Control Output

![Port D: Control Output circuit and interface definition, with 28V, +24V callouts.](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0038-vcrop-03.png)

| Port | Pin | Signal |
|---|---|---|
| D1 | ⑮ | Output |
| D2 | ⑪ | +24V |
| D3 | ⑫ | GND |

---


## Port E: Switch Sensor II

![Port E wiring schematic, including NPN, PNP input circuits and E1–E3 pin definitions](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0039-vcrop-00.png)

| Port | DB pin | Signal |
|---|---|---|
| E1 | ⑫ | GND |
| E2 | ⑭ | Input |
| E3 | ⑪ | +24V |

## Port G: Speeds Preset

![Port G preset speed interface circuit, including P+24, G1–G4 and Pset A, Pset B](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0039-vcrop-01.png)

| Port | DB pin | Signal |
|---|---|---|
| G1 | ⑫ | GND |
| G2 | ⑨ | Pset A |
| G3 | ⑫ | GND |
| G4 | ⑬ | Pset B |

## Port I: 24V DC Power

![Port I 24V DC power interface circuit, including I1 GND and I2 +24V](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0039-vcrop-02.png)

| Port | DB pin | Signal |
|---|---|---|
| I1 | ⑫ | GND |
| I2 | ⑪ | +24V |

Note: the numbers in the circle represent the pins of DB plug.

---


## Appendix D: LED Displayed Characters Definition

| Displayed Character | Definition | Symbol Image |
|---|---|---|
| H | Output Voltage | ![Output Voltage segment symbol H](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-00.png) |
| E | Output Frequency | ![Output Frequency segment symbol E](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-01.png) |
| t | Soft Startup | ![Soft Startup segment symbol t](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-02.png) |
| J | Startup Delay Time of the Intelligent Photoelectric Sensor | ![Intelligent photoelectric sensor on-delay segment symbol J](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-03.png) |
| J- | Startup Delay Time of the Switch Sensor | ![Switch sensor on-delay segment symbol J-](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-04.png) |
| J_ | Startup Delay Time of the 2ⁿᵈ Switch Sensor | ![2ⁿᵈ switch sensor on-delay segment symbol J_](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-05.png) |
| L | Shutdown Delay Time of the Intelligent Photoelectric Sensor | ![Intelligent photoelectric sensor off-delay segment symbol L](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-06.png) |
| L- | Shutdown Delay Time of the Switch Sensor | ![Switch sensor off-delay segment symbol L-](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-07.png) |
| L_ | Shutdown Delay Time of the 2ⁿᵈ Switch Sensor | ![2ⁿᵈ switch sensor off-delay segment symbol L_](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-08.png) |
| Γ1 | Logical Relation of the Switch Sensor | ![Logical relation of the switch sensor segment symbol](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-09.png) |
| Γ2 | Logical Relation of the Intelligent Photoelectric Sensor | ![Logical relation of the intelligent photoelectric sensor segment symbol](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-10.png) |
| Γ3 | Logical Relation of the 2ⁿᵈ Switch Sensor | ![Logical relation of the 2ⁿᵈ switch sensor segment symbol](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-11.png) |
| Γ4 | Logical Relation of the Controlling Output | ![Logical relation of the controlling output segment symbol](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-12.png) |
| Γ5 | Parameter Setting of Allocating the Control Signals to the Output of the Controller or DC Output for Controlling Separately | ![Control signal allocation parameter segment symbol](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-13.png) |
| ΓE | Frequency Display Character parameter setting | ![Frequency display character parameter segment symbol](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-14.png) |
| h | Maximum Output Voltage | ![Maximum Output Voltage segment symbol h](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-15.png) |
| A | Logical Relation of the Control Signal | ![Logical Relation of the Control Signal segment symbol A](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-16.png) |
| P | The CUH intelligent photoelectric sensor sensitivity parameter setting | ![Intelligent photoelectric sensor sensitivity parameter segment symbol P](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-17.png) |
| 8.8.8.8. | Default Settings Restore | ![Default Settings Restore: four digits and decimal points all lit](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-18.png) |
| ---- | Default Settings Restore Successful | ![Default Settings Restore Successful: four middle horizontal line segments](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-19.png) |
| Err | Error Information | ![Error Information segment symbol Err](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0040-vcrop-20.png) |


## Appendix E: Electrical Specification

| Item | Range: Min | Range: Typical | Range: Max | Unit | Description |
|---|---|---|---|---|---|
| Input Voltage | 85 | 380 | 440 | V | AC RMS |
| Adjustable Output Voltage Range | 35 | —— | Vin-10 | V | Half Wave |
| Adjustable Output Voltage Range | 45 | —— | Vin-5 | V | Full Wave |
| Voltage Adjustment Accuracy | | 1 | | V | |
| Response Time of Voltage Regulation | 0 | 0.01 | 0.02 | s | |
| Adjustable Output Current Range | 0 | —— | 10 | A | SDVC21-LP |
| Adjustable Output Current Range | 0 | —— | 25 | A | SDVC21-XLP |
| Output Power | 0 | —— | 3800 | VA | SDVC21-LP |
| Output Power | 0 | —— | 9500 | VA | SDVC21-XLP |
| Output Frequency | 90 | 100/120 | 130 | Hz | Full Wave |
| Output Frequency | 45 | 50/60 | 65 | Hz | Half Wave |
| Output Frequency | 30 | 33/40 | 43 | Hz | 1/3 full wave<br>SDVC21-XLP |
| Output Frequency | 22 | 25/30 | 32 | Hz | 1/4 full wave<br>SDVC21-XLP |
| Output Waveform | | Phase cut sine | | | |
| Soft Start Time | 0.0 | —— | 9.9 | s | Factory Default Value:0.5 |
| On/Off Delay Time Range | 0.0 | —— | 9.9 | s | Factory Default Value:0.2 |
| On/Off Delay Time Accuracy | | 0.1 | | s | |
| Overheat Protection Trigger Temperature | 58 | 60 | 66 | ℃ | |
| DC Control Output Voltage | 22 | 24 | 26 | V | |
| DC Control Output Current | 0 | —— | 200 | mA | |
| Analog Control Signal | | 1-5 | | V | Remote speed Control Voltage |
| Digital Control Signal | | 24 | | V | Switching Signal |
| Adjustment Method | | 4 | | Button | |
| Fuse Capacity | | 16 | | A | SDVC21-LP |
| Fuse Capacity | | 30 | | A | SDVC21-XLP |
| Standby Power Consumption | —— | 4 | —— | W | |
| Display Method | | 4 | | Digit | LED Digital Tubes |
| Ingress Protection Level | | IP67 | | | |
| Weight | | 4600 | | g | SDVC21-LP |
| Weight | | 5800 | | g | SDVC21-XLP |
| Ambient Temperature | 0 | 25 | 40 | ℃ | |

---


## Appendix F: Trouble Shooting Tips and Error Explanations

The following tips can help to solve the problems you may encounter

| | | | Symbol Image |
|---|---|---|---|
| 1 | No display after power on | ➔Make sure the power outlet is live<br>➔Make sure the Input Power Cable is reliably connected to the power outlet | |
| 2 | Displays normally, but no output | ➔Make sure the Input Power Cable and Output Power Cable are firmly connected<br>➔Make sure the Output Voltage parameter value is not too small<br>➔Make sure the controller is not stopped by the control signal<br>➔Make sure the controller is not stopped by the parameters that are set as normal off | |
| 3 | Control signal loses effectiveness | ➔Make sure the control signal is correctly inputted<br>➔Make sure the ground wire of the control signal is correctly connected to the controller<br>➔Make sure the Logical Relation of the control signal is set correctly as you expectation | |
| 4 | Displays normally, no output, but sound can be heard | ➔Adjust all parameters as this book instructed | |
| 5 | Err2 | ➔Output Over Current. Make sure the specifications of the vibrator don't exceed the limits of controller.<br>➔Output in short-circuit. Make sure the Output Power Cable and Output Power Aviation Connector are not shorted.<br>➔Make sure the Output Power Cable is connected reliably between controller and the vibrator.<br>➔Make sure the controller is reliably grounded. | ![Err2 7-segment display](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0042-vcrop-00.png) |
| 6 | Err3 | ➔Overheat, Place the controller in well ventilated environment | ![Err3 7-segment display](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0042-vcrop-01.png) |


## Appendix G: Absolute Parameters

Absolute Parameters:
Above the standard will damage the controller, obey it strictly.

| Item | GB Standard | IEC Standard | Standard Requirement | Reached Level of CUH Product | Note |
|---|---|---|---|---|---|
| Electrostatic Discharge | GB/T 17626.2-2006 | IEC 61000-4-2:2001 | 4 kV | ±8 kV | Contact Discharge |
| | | | 4 kV | ±15 kV | Air Discharge |
| Electrical Fast Transient Test | GB/T 17626.4-2008 | IEC 61000-4-4:2004 | 4 kV | ±4 kV | Direct Couple |
| Electrical Surge | GB/T 17626.5-2008 | IEC 61000-4-5:2005 | 4 kV | ±4 kV | Line-Line Couple |
| | | | 4 kV | ±4 kV | Line-Earth Couple |

---


![CUH QR code](assets/images/cuh.sdvc21-lp.manual.v0.0/page-0044-vcrop-00.png)

Nanjing CUH Science & Technology Co.,Ltd  
https://en.cuhnj.com  
Tel.:+86-25-84730411 / 84730415 / 84730416  
Fax:+86-25-84730426  
E-mail:sales@cuhnj.com  
Add.:Building 2, Xueyan Tech Park, Tuscity,  
No.9 Zhineng Rd, Jiangning, Nanjing, China

Document No.: IDP1000415


