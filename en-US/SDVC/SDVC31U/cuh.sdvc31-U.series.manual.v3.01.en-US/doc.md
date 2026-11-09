---
doc_id: cuh.sdvc31-U.series.manual.v3.01.en-US
doc_key: cuh.sdvc31-U.series.manual.v3.01
doc_type: manual
lang: en-US
product: sdvc31-U
source_pdf: /Users/wangle/Documents/Python开发/说明书转换/典型文档/20250905_25_SDVC31U.pdf
source_sha256: 4bca51402905402ddc1ccb9d730942161b7c484f125ef21d44e02884dd0d9789
title: Instruction Book of SDVC31-U Series Variable Frequency Digital Controller for Vibratory Feeder
updated_at: 2026-06-04 11:06:35
version: 0
---



# **Instruction Book of CUH SDVC31 Series**  
**Variable Frequency Digital Controller for Vibratory Feeder**


![SDVC31 Series controllers product photo](assets/images/Pasted%20image%2020260706014420.png)


---
# Preface

Thank you for choosing **CUH** Intelligent Digital Vibratory Feeder Controllers.(The controller for short in the following text)

This instruction book includes notes for installing, debugging, parameter setting, maintaining and trouble shooting of the controller. Please read this instruction book carefully before operating the controller and keep it properly

## This instruction book applies to the following models:

➡Variable Frequency Digital Controller for Vibratory Feeder  
SDVC31-S (1.5A Output Current)

➡Variable Frequency Digital Controller for Vibratory Feeder  
SDVC31-M (3.0A Output Current)

➡Variable Frequency Digital Controller for Vibratory Feeder  
SDVC31-L (4.5A Output Current)

➡Variable Frequency Digital Controller for Vibratory Feeder  
SDVC31-XL (6.0A Output Current)

➡Variable Frequency Digital Controller for Vibratory Feeder  
SDVC31-U (10.0A Output Current)

➡Variable Frequency Digital Controller for Vibratory Feeder  
SDVC31-XU (20.0A Output Current)


---

# Notice

➜ Never hot swap nor touch the contacts in any case to avoid electric shock or other accidents.

➜ Enclosure of the controller is grounded via the input power cable. Please make sure the power outlet is well grounded.

➜ Never connect the controller to 380V AC which may cause unrecoverable damage.  
(Choose products that are designed for 380V AC when needed)

➜ Never switch the input of the controller by way of cutting off power supply through a relay, a PLC or other devices, otherwise service life of the controller may be reduced severely.

➜ The controller is designed to work in a cool and dry environment. Never run outdoors to avoid soaking or sun exposure. Operate the controller within the temperature range that its electrical characteristics demand.

➜ Never operate the controller under the condition that beyond its designed limits.

➜ Operate the controller in accordance with this instruction book strictly. We will not assume any civil or criminal liability if the equipment damage or personal injury is caused by incorrect operation.

> [!CAUTION]
> **Never open the controller shell to avoid electric shock.** Contact CUH if the controller breaks down.
>
> Never try to revamp the controller since the solid state circuit boards inside the controller can not be repaired, and there's no adjustable part.

---

# Operating Environment

## Inspection Before Using

Every controller will go through rigorous quality inspection before delivery and is packed  
with crash-proof packaging.

## Please Check the Following Items After Unpacking:

➜ Whether the controller is damaged in appearance

➜ Whether model of the controller is exactly what you ordered

## Runtime Environment

Please follow the notes below to ensure better performance and longer lifetime of the  
controller

➜ Well-ventilated environment

➜ Keep away from water, steam, dust and especially oily dust

➜ Keep away from corrosive or flammable gas and liquid

➜ Keep away from flying dust and metal particles

➜ Firmly fixed to avoid self vibration

➜ Keep away form electromagnetic interference

➜ Operate within the temperature range of 0 °C to 40 °C

➜ For use at altiude 2000m or lower

---

# Chapter I Features

The controller is specially designed for controlling vibratory feeder in the automation systems. Combined with the latest electronic technology and elaborate design, the controller provides the following convenient and practical features:

**Frequency Adjusting:** Output Frequency ranges from 40.0Hz to 400.0Hz.

**Voltage Adjusting:** Output Voltage ranges from 0V to 250V.

**Automatic Voltage Stabilizing:** The controller can eliminate feeding speed variation caused by mains voltage fluctuation.

**Soft Startup:** In order to avoid sudden shock to the work pieces, the controller can gently increase output voltage from 0 to the pre-set value when startup.

**Intelligent Photoelectric Sensing:** Our adaptive Intelligent Photoelectric Sensor can help to stall the controller when work-pieces are full or work-piece is empty and to fulfill the functions of Soft Startup Time Setting,Startup Delay, Shutdown Delay, and Logical Relation Adjusting.

**Halt when Work-pieces are full:** A NPN switch sensor can help to halt the controller when work-pieces are full and to fulfill the functions of Soft Startup Time Setting, Startup Delay, Shutdown Delay, and Logical Relation Adjusting.

**Acceleration:** Due to this function, maximum output voltage value of the controller can be increased up to 150% of the input voltage value.

**Remote Speed Control:** Output Voltage of the controller can be controlled by an external potentiometer, a PLC, or voltage control signal ranging form 1V to 5V.

**Controlling Output:** The Controlling Output signal outgoing from the transistor can coordinate a solenoid or other external devices with the controller.

**Keypad Locking:** Press the ON/OFF button and hold for 2 seconds to lock all buttons for fear of false operation.

**Maximum Output Restriction:** Maximum Output Voltage value can be preset to protect the equipment from damage caused by misuse.

**Waveform Index Setting:** Operators can weight efficiency and maximum capacity by adjusting this parameter.

**Default Settings Restoration:** This function allows the user to restore all default parameter settings and reset the controller.

**CUH** attaches great importance to the product quality management and safety performance. Apart form the high-quality components we use and rigorous quality control system, **CUH** has taken account of possible accidents users may encounter and provides the following protective functions to maximum the controller's practicability.

**Short-Circuit Protection:** If output of the controller is short-circuited, the controller will halt its output until restarted.

**Current Overload Protection:** The controller will halt its output to ensure equipments' operating safety when operation current exceeds its rated value.

**Overheat Protection:** The controller will halt its output to protect itself when operation temperature is too high.

**CUH** controllers are strictly compliant with CE certification.

---

# Chapter II Installation Guide

## Step One:

Open the packing box and check the controller's outward appearance and make sure the controller model is exactly what you ordered.

## Step Two:

Connect the Output Power Cable in the packing box to the vibrator's electromagnetic coils.

![Step Two wiring diagram showing output power cable connected to vibrator electromagnetic coils, with two output pins and yellow/green ground wire.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0011-vcrop-00.png)

Figure labels:

- Output Pin
- Output Pin
- Ground Wire (Yellow and Green Dual Color)

## ⚠ Notice

Make sure the vibrator's electromagnetic coils is connected to the two output pins of the Output Power Cable and the electromagnetic coils is reliably grounded otherwise series security incident may occur.

---


---

## Step Three:

Connect the Input Power Cable to the controller and lock the power nut.

![Step Three illustration: input power cable connected to the controller first, with outlet, cable, controller, hand, and callout.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0012-vcrop-00.png)

## Step Four:

Connect the plug of the Input Power Cable to the mains jack.

![Step Four illustration: plug of the input power cable being connected to the mains socket.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0012-vcrop-01.png)

---


---

## Step Five:

Adjust the controller's Output Voltage to the value between 30 and 80 (represented by the letter U)

![Step Five controller display and output voltage indicator callout diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0013-vcrop-00.png)

Diagram labels:

- U—represents Output Voltage
- Output Voltage Indicator

## Step Six:

Press the <kbd>FUNC</kbd> button and hold for 2 seconds to enter the Basic Settings Adjusting status.

The Output Frequency Indicator on the panel lights up and the LED displays the current frequency value (E) Press the ▲ or ▼ button to adjust the parameter value from 400Hz to 40Hz to find out harmonic frequency of the vibrator and hold this value.

![Step Six controller display and output frequency indicator callout diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0013-vcrop-01.png)

Diagram labels:

- E—represents Output Frequency
- Output Frequency Indicator

> ● Harmonic frequency of the vibrator means the frequency value that creates the maximum amplitude.
>
> ● Every vibrator has its natural mechanical resonance frequency, adjust the output frequency of the controller to this frequency to guarantee the best working condition.

---


---

## Step Seven:

After setting the Output Frequency of the controller to the natural mechanical resonance frequency of the vibrator, adjust the Output Voltage of the controller by pressing the **Vol+** or **Vol-** button to change feeding speed.

![Output voltage indicator diagram showing controller display, Vol+ and Vol- buttons, and hand pressing the button](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0014-vcrop-00.png)

After the above seven steps, the controller can work properly. Please refer to the other chapters if advanced control functions are needed.

---


# Chapter III Components Description

## 3.1 Descriptions of the Control Panel

![Annotated control panel description and SDVC31 model appearance drawings](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0015-vcrop-00.png)

### Control panel indicators and buttons

| Item | Description |
|---|---|
| Output Voltage Indicator | The indicator lights up as the controller enters Output Voltage Adjusting status. |
| Output Frequency Indicator | The indicator lights up as the controller enters Output Frequency Adjusting status. |
| Startup Delay Indicator | The indicator lights up as the controller enters Startup Delay Time adjusting status. |
| Shutdown Delay Indicator | The indicator lights up as the controller enters Shutdown Delay Time Adjusting status. |
| Soft Startup Indicator | The indicator lights up as the controller enters Soft Startup Time Adjusting status. |
| Output Voltage Increasing Button & Output Voltage Decreasing Button | Output Voltage can be changed by these two buttons. When the Keypad Locking function is on, these two buttons lose efficacy. |
| Advanced Parameter Increasing Button &Advanced Parameter Decreasing Button | Advanced parameters can be adjusted by these two buttons. |
| FUNC Button | Shift advanced parameters by pressing this button. |
| Soft Power Switch Button | Startup or shutdown output of the controller by pressing this button. |

### Models shown

| Model | Current |
|---|---:|
| SDVC31-S | 1.5A |
| SDVC31-M | 3A |
| SDVC31-L | 4.5A |
| SDVC31-XL | 6.0A |
| SDVC31-U | 10A |
| SDVC31-XU | 20A |

---


---

## 3.2 Descriptions of the Status Indicators

![Descriptions of the Status Indicators diagram showing the SDVC31 controller front panel and callouts for Saturation, Acceleration, Remote Speed Control, Stop, Lock, and LED display indicators.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0016-vcrop-00.png)

- **Acceleration Indicator:** The indicator lights up as the Acceleration function takes effect when the Output Voltage value exceeds Input Voltage value.
- **Remote Speed Control Indicator:** The indicator lights up when Remote Speed Control signal is available as the Vol+and Vol- buttons loses efficacy.
- **Stop Indicator:** The indicator lights up as the controller halts its output.
- **Saturation Indicator:** The indicator lights up when the preset Output Voltage value exceeds Input Voltage value so much that the controller can't sustain.
- **Lock Indicator:** The indicator lights up as the controller being locked.
- **LED displayer:** The LED displayer indicates current adjustable parameter.

## 3.3 I/O Interface Descriptions

![I/O Interface Descriptions diagram showing rear or side interfaces for SDVC31-S/M, SDVC31-L/XL, and SDVC31-U/XU models with power switch and socket callouts.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0016-vcrop-01.png)

- **SDVC31-S（1.5A） / SDVC31-M（3.0A）**
  - Power Switch
  - Output Power Socket
  - Input Power Socket
- **SDVC31-L（4.5A） / SDVC31-XL（6.0A）**
  - Power Switch
  - Output Power Socket
  - Input Power Socket
- **SDVC31-U（10A） / SDVC31-XU（20A）**
  - Input Power Socket
  - Output Power Supple Core
  - Power Switch

---


# Chapter IV Function Descriptions

## 4.1 Output Voltage Setting

The Output Voltage can be set directly and digitally through the control panel. Benefit from the unique Voltage Stabilizing Function, Output Voltage of the controller won't fluctuate as the Input Voltage does,and a vibrator can work stably in unstable input voltage environment.

- Turn on the power switch

- The Output Voltage Indicator lights up as the controller enters Output Voltage Adjusting status when the LED displays the voltage symbol U and the previously set voltage value.

- Adjust the Output Voltage value by pressing the <kbd>Vol+</kbd> or <kbd>Vol-</kbd> button.

![Output Voltage Setting control panel diagram with labels](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0017-vcrop-00.png)

- U — represents Output Voltage
- Output Voltage Indicator
- Output Voltage value is set as 180V at present
- The adjustable Output Voltage of the controller series ranges from 0V to 250V

> Output Voltage can be adjusted in any Basic Parameter Adjusting status or Advanced Parameter Adjusting status by pressing the <kbd>Vol+</kbd> or <kbd>Vol-</kbd> button. The controller returns to the previous parameter adjusting status after adjusting the Output Voltage.

## ☺ Acceleration

When desired Output Voltage value exceeds Input Voltage value, the Acceleration function of the controller works as the Acceleration Indicator lights up.

When desired Output Voltage value exceeds too much of the Input Voltage value, the controller fails to output such voltage value as the Saturation Indicator lights up.

![Acceleration and Saturation indicator control panel diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0017-vcrop-01.png)

- Acceleration Indicator
- Saturation Indicator

---


---

## 4.2 Output Frequency Adjusting

The controller is produced with the DDS technology and its output has got high frequency accuracy and stability which doesn't change as the time or temperature does.

- Press the <kbd>FUNC</kbd> button and hold for 2 seconds to enter the Basic Parameters Adjusting status.

- The Frequency Indicator on the panel lights up and the LED displays the Output Frequency symbol **E** and the current Output Frequency value.

- Press the ▲ or ▼ button to adjust the parameter value.

Output Frequency of the controller ranges from 40Hz to 400Hz.

![Output Frequency Adjusting controller display diagrams with annotation callouts](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0018-vcrop-00.png)

**Figure callouts:**

- **E** — represents Output Frequency
- Frequency Setting Indicator
- Output Frequency is set as 50Hz at present

> ☺
>
> ● Output Frequency (E), Startup Delay Time, Shutdown Delay Time and Soft Startup Time can be set after entering the Basic Parameters Adjusting status by pressing the <kbd>FUNC</kbd> button and holding for 2 seconds.
>
> ● The controller will return to the Output Voltage Adjusting status automatically in 1 minute after adjusting operation.
>
> ● Press the <kbd>FUNC</kbd> button and hold for 2 seconds again to exit the Basic Parameters Adjusting status.

---


## 4.3 Soft Startup

In order to avoid sudden shock to the work pieces, the controller can gently increase Output Voltage from 0 to the pre-set value when startup.

Soft Startup Time ( t ): The period of time it takes for the controller to gently increase Output Voltage from 0 to the pre-set value when startup.

» Press the **FUNC** button and hold for 2 seconds to enter the Basic Parameters Adjusting status.

» Press the **FUNC** button repeatedly until shifting to the Soft Startup Time adjusting status (t) as the Soft Startup Indicator lights up.

» Press the ▲ or ▼ button to adjust the parameter value. The parameter unit is second, and the numerical precision is 0.1.

![Soft Startup setting diagram showing the controller display and indicator callouts](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0019-vcrop-00.png)

- **t** - represents Soft Startup Time
- Soft Startup Indicator
- Soft Startup Time is set as 1.5 seconds at present

Adjustable Soft Startup Time ranges from 0.1 seconds to 9.9 seconds.

## 4.4 Output Switch Button

The soft-touch switch button on the panel can turn on/off the controller's output quickly and easily.

» Press the **ON/OFF** button to turn on/off the controller's output. The Stop Indicator lights up as output of the controller is turned off.

![Output switch button diagram showing the controller and stop indicator callout](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0019-vcrop-01.png)

The Stop Indicator lights up as the controller is shutdown by the **ON/OFF** button.

😊

Due to the soft-touch switch and digital signal control technology, no spark will generate to spoil the contact. As a result, life-span of the controller and the vibrator will be extended greatly.

---


## 4.5 Maximum Output Voltage Restriction

Maximum Output Voltage of the controller can be set to prevent damage to the vibrator. Remote Speed Controller function is affected by this parameter.

- Press the <kbd>FUNC</kbd> and ▲ buttons simultaneously and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the <kbd>FUNC</kbd> button repeatedly until shifting to the Maximum Output Voltage Restriction status (h).
- Press the ▲ or ▼ button to adjust the parameter value.

![Maximum Output Voltage Restriction adjustment illustrations showing FUNC/up/down buttons and display example h 50.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0020-vcrop-00.png)

> ● Output Voltage value can not exceeds this parameter value in any case.  
> ● Default value of this parameter is set as the maximum adjustable Output Voltage value.

## Exit method of the Advanced Parameters Adjusting status

● The controller will quit to the Output Voltage Adjusting status automatically in one minute after Advanced Parameters adjusting.  
● Press the <kbd>FUNC</kbd> and ▲ buttons and hold for 2 seconds to quit to the Output Voltage Adjusting status.  
● Press the <kbd>FUNC</kbd> button and hold for 2 seconds to quit to the Basic Parameters Adjusting status.

---


## 4.6 Acceleration Parameter Adjusting

Acceleration Parameter (y): This parameter means the maximum Output Voltage as percentage of the Input Voltage. The Acceleration function is affected by this parameter.

- Press the `FUNC` and ▲ buttons simultaneously and hold for 2 seconds to enter the Advanced Parameters Adjusting status
- Press the `FUNC` button repeatedly until shifting to the Acceleration Parameter Adjusting status (y).
- Press the ▲ or ▼ button to adjust the parameter value.

![Acceleration Parameter Adjusting operation diagram with controller buttons, digital display y 120, and output voltage percentage description](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0021-vcrop-00.png)

> ● Adjustable Acceleration value (y) ranges from 100 to 150, and the default value is 120.  
> ● The Saturation Indicator lights up when Output Voltage of the controller exceeds the limit.

---


---

## 4.7 Waveform Index Adjusting

Operators can weight peak efficiency and maximum power (minimal noise) by adjusting this parameter.

- Press the **FUNC** and **▲** buttons simultaneously and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Waveform Index Adjusting status (**r**).
- Press the **▲** or **▼** button to adjust the parameter value.

![Controller button operation illustration and display showing waveform index parameter r and value 60](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0022-vcrop-00.png)

Diagram labels:

- **r** represents Waveform Index
- Waveform Index is set as **60** at present

> ☺
>
> ●Adjustable Waveform Index ranges form 0 to 100.  
> ●The value 0 represents the peak efficiency when the spring plates bear the minimal stress.  
> ●The value 100 represents the maximum power (minimal noise) when the spring plates bear the maximal stress.

---


## 4.8 Keypad Locking

The Keypad Locking Function can lock all buttons on the panel to avoid misoperation.

- Press the <kbd>ON/OFF</kbd> button and hold for 2 seconds to lock all buttons on the panel as the Keypad Locking Indicator lights up.
- Press the <kbd>ON/OFF</kbd> button and hold for 2 seconds in the locking mode to unlock the keypad.

![Keypad locking indicator lights up: controller panel illustration with ON/OFF button being pressed and indicator callout.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0023-vcrop-00.png)

---


## 4.9 Default Settings Restoration

This function allows the operator to restore all default parameter settings.

Due to the abundant functions of the controller, many parameters can be adjusted. In order to avoid the circumstance that after too many times modification by a beginner, the controller can not work properly, this function allows the operator to restore default settings to the controller in an easy way.

- Press the **FUNC** and **▲** buttons simultaneously and hold for 2 seconds to enter the Advanced Parameters Adjusting status.

  ![Press FUNC and up arrow buttons simultaneously on controller](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0024-vcrop-00.png)

- Press the **FUNC** button repeatedly until `8888` is flashing on the LED display, and then press the **▲** button and hold until `-----` is displayed which means default settings have been restored successfully.

  ![Controller display shows 8888 and ready to restore indication](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0024-vcrop-01.png)

- After releasing the **▲** button, the controller enters Output Voltage Adjusting status (U). By this time, all parameters have been restored to default values.

  ![Controller display shows restored successfully indication](assets/images/page-0024-vcrop-02.png)


# Chapter V Sensors and Signal Control

The controller can be controlled by many kinds of external signals and sensors. This chapter mainly elaborates using method of the Intelligent Photoelectric Sensor, the Proximity Switch Sensors and the PLC.

## 5.1 Intelligent Photoelectric Sensing

Combined with the SDVC-S1 Photoelectric Sensor the function of Intelligent Photoelectric Sensing can be achieved. The SDVC-S1 sensor can filter the interference of background light impacting on the sensitivity of the controller. As a result, the controller can work reliably without manual sensitivity adjustment.

### 5.1.1 Connection Method of the SDVC-S1 Intelligent Photoelectric Sensor

![Connection diagram for the SDVC-S1 Intelligent Photoelectric Sensor showing controller terminals B1-B4, RX/TX wires, ground/input/output, red/white/copper wires, and installation steps.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0025-vcrop-00.png)

**Step 1:**  
Open the upper cover plate of the controller.

**Step 2:**  
Connect the SDVC-S1 sensor to the terminals of the controller according to the diagram.

**Step 3:**  
Close the cover plate after connecting the sensor.

**Notice:**  
Default logical relation of the sensor is set as work pieces are empty.


---

## 5.1.2 Startup Delay Time and Shutdown Delay Time Settings of the Intelligent Photoelectric Sensor

In most actual applications, the output of the controller should be delayed for a period of time when Startup or Shutdown of the controller is controlled by external signals. Startup Delay Time and Shutdown Delay Time Adjusting functions made this kind of application possible. Furthermore, shocks to the work pieces as the controller starts up can be eliminated by setting Soft Startup Time.

### Startup Delay( J )

The period of time the controller goes through from receiving a startup control signal to outputting.

- Press the **FUNC** button and hold for 2 seconds to enter the Basic Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Startup Delay Time Adjusting status ( J ) as the Startup Delay Time Indicator on the panel lights up.
- Adjust the parameter by pressing the ▲ or ▼ button. The parameter unit is second, and the numerical precision is 0.1.

*Adjustable range of the parameter is from 0.0 to 9.9 seconds*  
*Default value of the parameter is 0.2 seconds*

![Startup Delay Time setting diagram showing digital controller panel, display value 2.0, J represents Startup Delay Time, Startup Delay Time is set as 2.0 seconds, and Startup Delay Indicator.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0026-vcrop-00.png)

### Shutdown Delay (L)

The period of time the controller goes through from receiving a shutdown control signal to cutting off output

- Press the **FUNC** button and hold for 2 seconds to enter the Basic Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Shutdown Delay Time Adjusting status (L) as the Shutdown Delay Time Indicator on the panel lights up.
- Adjust the parameter by pressing the ▲ or ▼ button. The parameter unit is second, and the numerical precision is 0.1.

*Adjustable range of the parameter is from 0.0 to 9.9 seconds*  
*Default value of the parameter is 0.2 seconds*

![Shutdown Delay setting diagram showing digital controller panel, display value 1.5, L represents Shutdown Delay Time, delay time is set as 1.5 seconds, and Shutdown Delay Indicator.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0026-vcrop-01.png)

---


## 5.1.3 Logical Relation Setting of the Intelligent Photoelectric Sensor

Under normal circumstances, the receiving end receives no optical signal, and the controller runs by default. But in some special applications the controller needs to be stopped when the receiving end receives no optical signal. Adjusting this parameter can fulfill this kind of application.

- Press the **FUNC** and ▲ button simultaneously and hold for 2 seconds to enter the Advanced Parameters Adjusting status.

![Press FUNC and up button simultaneously for 2 seconds diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0027-vcrop-00.png)

- Press the **FUNC** button repeatedly until shifting to the Logical Relation Adjusting status of the Intelligent Photoelectric Sensor.

  **08** — represents Logical Relation of the Intelligent Photoelectric Sensor  
  **Normal Open**

![Logical Relation parameter 08 Normal Open controller display diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0027-vcrop-01.png)

- Adjust the parameter by pressing the ▲ or ▼ button.

  **08** — represents Logical Relation of the Intelligent Photoelectric Sensor  
  **Normal Close**

![Logical Relation parameter 08 Normal Close controller display diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0027-vcrop-02.png)

- When Logical Relation is set as Normal Open, namely no optical signal received, the controller runs.
- When Logical Relation is set as Normal Close, namely no optical signal received, the controller stops.

---

## 5.2 Using Method of the NPN Switch Sensor

The controller can operate with all kinds of sensors such as switch sensors, optical switch sensors and fiber optic sensors.

### 5.2.1 Connection method of the NPN Proximity Switch Sensor

**Step 1:**  
Open the upper cover plate of the controller.

**Step 2:**  
Connect the NPN Proximity Switch Sensor to the terminals of the controller according to the diagram.

**Step 3:**  
Close the cover plate after connecting the sensor.

![Connection method diagram for NPN proximity switch sensor, including controller cover opening, terminal wiring C1/C2/C3, wire color convention, and proximity switch connection.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0028-vcrop-00.png)

| Terminal | Wire |
|---|---|
| C1 | Ground Wire |
| C2 | Signal Wire |
| C3 | +24V Output |

**Convention**

The blue wire represents ground wire  
The black wire represents signal wire  
The brown wire represents power wire

Proximity Switch

---


---

### 5.2.2 Connection method of the NPN Counter-radiation Switch Sensor

![Connection method of the NPN Counter-radiation Switch Sensor wiring diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0029-vcrop-00.png)

### 5.2.3 Connection method of the Photoelectric Counter-radiation Sensor

![Connection method of the Photoelectric Counter-radiation Sensor wiring diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0029-vcrop-01.png)

---


## 5.2.4 Connection method of the Optical Fiber Counter-radiation Sensor

![Connection diagram for optical fiber counter-radiation sensor, showing RX/TX fiber heads, fiber optic sensor module wiring, and terminal block connections.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0030-vcrop-00.png)

Diagram labels shown include: **RX**, **TX**, **Fiber optic sensor**, **White or Black**, **Blue**, **Brown**.

Terminal annotations shown:

| Terminal | Annotation |
|---|---|
| C1 | Ground Wire |
| C2 | Signal Wire |
| C3 | +24V Output |


---

## 5.2.5 Connection method of the Photoelectric Reflection Sensor

![Connection method diagram of the photoelectric reflection sensor to terminals A1-D2](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0031-vcrop-00.png)

---


---

## 5.3 Startup Delay Time and Shutdown Delay Time Settings of the NPN Switch Sensor

By default, Intelligent Photoelectric Sensor and Switch Sensor share the same Startup Delay Time and Shutdown Delay Time. Operators can also set Startup Delay Time and Shutdown Delay Time independently for the Switch Sensor.

### Startup Delay (J-)

The period of time the controller goes through from receiving a startup control signal to outputting.

- Press the **FUNC** and ▲ buttons simultaneously and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Startup Delay Time Adjusting status (`J---`) as the Startup Delay Time Indicator on the panel lights up.
- Adjust the parameter by pressing the ▲ or ▼ button. The parameter unit is second, and the numerical precision is 0.1.

![Startup Delay setting illustration with controller buttons, display, and callout showing startup delay time set as 3 seconds.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0032-vcrop-00.png)

Startup Delay is set as `J---` by default

### Shutdown Delay (L-)

The period of time the controller goes through from receiving a shutdown control signal to cutting off output.

- Press the **FUNC** and ▲ buttons simultaneously and hold for 2 seconds to enter the Advanced Parameters Adjusting status.
- Press the **FUNC** button repeatedly until shifting to the Shutdown Delay Time Adjusting status (`L-`) as the Shutdown Delay Time Indicator on the panel lights up.
- Adjust the parameter by pressing the ▲ or ▼ button. The parameter unit is second, and the numerical precision is 0.1.

![Shutdown Delay setting illustration with controller buttons, display, and callout showing delay time set as 2 seconds.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0032-vcrop-01.png)

Shutdown Delay is set as `L----` by default

> ➜ When `J-` and `L-` values are adjusted to 0, Startup Delay Time and Shutdown Delay Time of the Switch Sensor will be the same with Startup Delay Time and Shutdown Delay Time of the Intelligent Photoelectric Sensor.  
> ➜ Startup Delay Time and Shutdown Delay Time of the Intelligent Photoelectric Sensor will not affected by the parameter of `J-` or `L-`.

---


---

## 5.4 Logical Relation Setting of the NPN Switch Sensor (Halt when work-pieces are full)

Under normal circumstances, the controller receives no signal from the NPN Switch Sensor and runs by default. But in some special applications the controller needs to be stopped when receives no signal from the NPN Switch Sensor. Adjusting this parameter can fulfill this kind of application.

▶▶ Press the <kbd>FUNC</kbd> and ▲ buttons simultaneously and hold for 2 seconds to enter the Advanced Parameters Adjusting status.

▶▶ Press the <kbd>FUNC</kbd> button repeatedly until shifting to the Logical Relation Adjusting status of the NPN Switch Sensor (`F2`).

▶▶ Adjust the parameter by pressing the ▲ or ▼ button.

![Controller button and display illustrations for NPN switch sensor logical relation setting, showing FUNC plus up button operation, F2 display, Normal Open and Normal Close examples.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0033-vcrop-00.png)

`F2`—represents Logical Relation of the NPN Switch Sensor.

- Normal Open
- Normal Close

> ●When Logical Relation is set as Normal Open, namely no signal received, the controller runs.  
> ●When Logical Relation is set as Normal Close, namely no signal received, the controller stops.

---


## 5.5 Logical Relation Setting of the Control Signal

The controller can set the Logical Relation of the Intelligent Photoelectric Sensor and the Switch Sensor when they work simultaneously.

▶ Press the **FUNC** and ▲ buttons simultaneously and hold for 2 seconds to enter the Advanced Parameters Adjusting status.

▶ Press the **FUNC** button repeatedly until shifting to the Logical Relation Adjusting status of the Control Signal

▶ Adjust the parameter by pressing the ▲ or ▼ button.

![Right-side controller buttons and digital display operation diagram with OR, AND, XOR logic relation annotations](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0034-vcrop-00.png)

Ⅰ

●Logical relation AND: The controller runs only when both the Intelligent Photoelectric Sensor and the NPN Switch Sensor ask the controller to.

●Logical relation OR: The controller runs when the Intelligent Photoelectric Sensor or the NPN Switch Sensor asks the controller to.

●Logical relation NOR: The controller runs only when the Intelligent Photoelectric Sensor and the NPN Switch Sensor output the opposite control signal.

---


## 5.6 Connection Method of the Upper PLC which Controls the Vibratory Feeder Controller

### 5.6.1 Connection method of the controlling PLC

**Step One:**  
Open the upper cover plate of the controller.

**Step Two:**  
Connect the PLC to the terminals of the controller according to the diagram.

**Step Three:**  
Close the cover plate after connecting the sensor.

![Connection diagram showing PLC wiring to SDVC31 controller terminals, including C1/C2/C3 ground and signal wire labels and controller cover illustration.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0035-vcrop-00.png)

Relay output or NPN output of the PLC is compatible with the controller.

---


---

## 5.7 Controlling Output

The controller can output low-voltage controlling signal to cooperate with other devices such as a solenoid valve, a PLC or an electrical relay.

### 5.7.1 Connection method of the Controlling Output

**Connection method of the solenoid valve**

![Connection method of the solenoid valve wiring diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0036-vcrop-00.png)

●The controller can directly drive a solenoid valve whose rated voltage is 24V and rated power lower than 4W.  
●Use external power supply for high power solenoid valve.

**Connection method of the electrical relay**

![Connection method of the electrical relay wiring diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0036-vcrop-01.png)

●The controller can directly drive an electrical relay whose rated voltage is 24V and rated power lower than 4W.

---


## 5.7.2 Logical Relation Setting of the Controlling Output

- Press the **FUNC** and **▲** buttons simultaneously and hold for 2 seconds to enter the Advanced Parameters Adjusting status.

- Press the **FUNC** button repeatedly until shifting to the Logical Relation Adjusting status of the Controlling Output (F3).

- Adjust the parameter by pressing the **▲** or **▼** button.

![Logical Relation setting diagrams showing FUNC and arrow buttons, display 0.8, and Normal Open / Normal Close output states.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0037-vcrop-00.png)

> ● When Logical Relation is set as Normal Open, the Controlling Output works as the controller runs.  
> ● When Logical Relation is set as Normal Close, the Controlling Output doesn't work as the controller runs.

---


---

## 5.8 Remote Speed Control

The function of Remote Speed Control allows the operator to control the Output Voltage by an external potentiometer or a control signal ranging from 1V to 5V. Thus, external remote speed control can be easily achieved by a PLC, a DCS or some other means.

Remote Speed Control function becomes effective to the controller when the controlling signal exceeds 0.5V. Meanwhile, Remote Speed Control indicator on the panel lights up and the `Vol+` and `Vol-` buttons lose effectiveness. The LED displayer shows current Output Voltage if the controller is running in the Output Voltage Adjusting status.

### Connection method of the external potentiometer

- A1: Ground Wire of the Remote Speed Control
- A2: Remote Speed Control Input
- A3: Remote Speed Control Power Supply

**Note:** Please select linearity potentiometer with the resistance of 1k.

![Connection method of the external potentiometer wiring diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0038-vcrop-00.png)

### Connection method of the PLC

- A1: Ground Wire of the Remote Speed Control
- A2: Remote Speed Control Input
- A3

![Connection method of the PLC wiring diagram](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0038-vcrop-01.png)

---


---

# Chapter VI Security Functions

## 6.1 Automatic Voltage Stabilizing

The built-in Digital Voltage Stabilizing function can eliminate feeding speed variation caused by mains voltage fluctuation.

## 6.2 Short-Circuit Protection

If output of the controller is short-circuited, the controller will halt its output until restarted.

## 6.3 Current Overload Protection

The controller will halt its output to ensure equipments' operating safety when operation current exceeds its rated value.

## 6.4 Overheat Protection

The controller will halt its output to protect itself when operation temperature is too high.

---


---

# Appendix

## Appendix A: Dimensions

Outline Dimensions of the controller model: SDVC31-S and SDVC31-M (unit: mm)

![Outline dimension drawing for SDVC31-S and SDVC31-M controller, showing front and side views with dimensions in millimeters.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0040-vcrop-00.png)

---


Outline Dimensions of the controller model: SDVC31-L and SDVC31-XL (unit: mm)

![Outline dimensions front view of SDVC31-L and SDVC31-XL controller, with measurement annotations including 64, 10, 54, 147.8, 162.7, 174, and 190 mm.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0041-vcrop-00.png)

![Outline dimensions side/bottom view of SDVC31-L and SDVC31-XL controller, with heat sink fins, controls/connectors, and measurement 94.5 mm.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0041-vcrop-01.png)


---

Outline Dimensions of the controller model: SDVC31-U and SDVC31-XU (unit:mm)

![SDVC31-U and SDVC31-XU controller outline dimensions, front view with dimension annotations.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0042-vcrop-00.png)

![SDVC31-U and SDVC31-XU controller outline dimensions, side/bottom view with dimension annotations.](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0042-vcrop-01.png)

---


---

## Appendix B: Output Interface Definition

![Output Interface Definition circular socket diagram showing two Output pins and Shell Ground](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0043-vcrop-00.png)

### ☺ Notice:

**A:** Make sure the electromagnetic coils of the vibrator is connected to the two output pins of the Output Power Cable socket and the shell of the vibrator is reliably earthed, otherwise series security incident may occur.

**B:** After welding, make sure the blank area is enswathe by insulating tape or heat-shrinkable tube before insert it into the Output Power Cable socket to avoid electrical leakage or short-circuit.

## Appendix C: Signal Interface Definition

| Terminal | Definition |
|---|---|
| A1 | Ground Wire of the Remote Speed Control |
| A2 | Remote Speed Control Input |
| A3 | Remote Speed Control Power Supply |
| B1 | Ground |
| B2 | Intelligent Photoelectric Sensor Signal In |
| B3 | Ground |
| B4 | Intelligent Photoelectric Sensor Signal Out |
| C1 | +24V GND |
| C2 | NPN Switch Sensor Signal In |
| C3 | +24V |
| D1 | Controlling Output |
| D2 | +24V |

![Signal Interface Definition terminal wiring diagram with terminals A1 to D2 and signal labels](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0043-vcrop-01.png)

---


## **Appendix D:** LED Displayed Characters Definition

| Controller | Displayed Character | Symbol Image |
|---|---|---|
| `U` | Output Voltage | ![Seven-segment Symbol: U](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-00.png) |
| `F` | Output Frequency | ![Seven-segment Symbol: F](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-01.png) |
| `d` | Startup Delay Time of the Intelligent Photoelectric Sensor | ![Seven-segment Symbol: d](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-02.png) |
| `C` | Shutdown Delay Time of the Intelligent Photoelectric Sensor | ![Seven-segment Symbol: C](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-03.png) |
| `E` | Soft Startup | ![Seven-segment Symbol: E](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-04.png) |
| `U-` | Shutdown D | ![Seven-segment Symbol: U-](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-05.png) |
| `d-` | Startup Delay Time of the NPN Switch Sensor | ![Seven-segment Symbol: d-](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-06.png) |
| `r1` | Logical Relation of the Intelligent Photoelectric Sensor | ![Seven-segment Symbol: r1](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-07.png) |
| `r2` | Logical Relation of the NPN Switch Sensor | ![Seven-segment Symbol: r2](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-08.png) |
| `r3` | Logical Relation of the Controlling Output | ![Seven-segment Symbol: r3](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-09.png) |
| `n` | Logical relation of the Control Signal | ![Seven-segment Symbol: n](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-10.png) |
| `H` | Maximum Output Voltage | ![Seven-segment Symbol: H](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-11.png) |
| `A` | Acceleration Index | ![Seven-segment Symbol: A](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-12.png) |
| `P` | Waveform Index | ![Seven-segment Symbol: P](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-13.png) |
| `88888` | Default Settings Restore | ![Seven-segment Symbol: 88888](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0044-vcrop-14.png) |

---


## Appendix E: Electrical Specification

| Item | Range Min | Range Typical | Range Max | Unit | Description |
|---|---:|---:|---:|:---:|---|
| Input Voltage | 85 | 220 | 250 | V | AC RMS |
| Adjustable Output<br>Voltage Range | 0 | —— | 250 | V | Lower than 150% of<br>Input Voltage |
| Voltage Adjustment<br>Accuracy |  | 1 |  | V |  |
| Voltage Regulation<br>Accuracy | 0 | —— | 10 | % | ΔVout/ΔVin |
| Response Time of<br>Voltage Regulation | 0.0025 | —— | 0.025 | s | 1/10 of the period of<br>output voltage |
| Adjustable Output<br>Current Range | 0 | —— | 1.5 | A | SDVC31-S |
|  | 0 | —— | 3 | A | SDVC31-M |
|  | 0 | —— | 4.5 | A | SDVC31-L |
|  | 0 | —— | 6 | A | SDVC31-XL |
|  | 0 | —— | 10 | A | SDVC31-U |
|  | 0 | —— | 20 | A | SDVC31-XU |
| Output Power | 0 | —— | 330 | VA | SDVC31-S |
|  | 0 | —— | 660 | VA | SDVC31-M |
|  | 0 | —— | 990 | VA | SDVC31-L |
|  | 0 | —— | 1320 | VA | SDVC31-XL |
|  | 0 | —— | 2200 | VA | SDVC31-U |
|  | 0 | —— | 4400 | VA | SDVC31-XU |
| Output Frequency | 40 | —— | 400 | Hz |  |
| Frequency Adjustment<br>Accuracy |  | 0.1 |  | Hz |  |
| Output Waveform |  | sine |  |  |  |
| Soft Start Time | 0 | —— | 10 | s | Factory Default<br>Value:0.5 |
| On/Off Delay Time<br>Range | 0 | —— | 20 | s | Factory Default<br>Value:0.2 |
| On/Off Delay Time<br>Accuracy |  | 0.1 |  | s |  |
| Overheat Protection<br>Trigger Temperature | 58 | 60 | 66 | ℃ | SDVC31-S\M |
|  | 60 | 65 | 65 | ℃ | SDVC31-L\XL\U\XU |
| DC Control Output<br>Voltage | 22 | 24 | 26 | V |  |
| DC Control Output<br>Current | 0 | —— | 200 | mA |  |
| Analog Control Signal |  | 1-5 |  | V | Remote speed<br>Control Voltage |
| Digital Control Signal |  | 24 |  | V | Switching Signal |
| Adjustment Method |  | 6 |  | Button |  |
| Standby Power<br>Consumption | —— | 3 | —— | W |  |
| Display Method |  | 5 |  | Digit | LED Digital Tubes |
| Ambient Temperature | 0 | 25 | 40 | ℃ | No Condensation |
| Ambient Humidity | 10 | 60 | 85 | % |  |


## Appendix F: Trouble Shooting Tips and Error Explanations

The following tips can help to solve the problems you may encounter

| No. | Problem / display | Symbol Image | Trouble Shooting Tips and Error Explanations |
|---:|---|---|---|
| 1 | No display after<br>power on |  | ◆ Make sure the power outlet is live<br>◆ Make sure the Input Power Cable is reliably connected to the power outlet |
| 2 | Displays normally<br>but no output |  | ◆ Make sure the Input Power Cable and Output Power Cable are firmly connected<br>◆ Make sure the Output Voltage parameter value is not too small<br>◆ Make sure the controller is not stopped by the control signal<br>◆ Make sure the controller is not stopped by the parameters that are set as normal off |
| 3 | Control signal<br>loses effectiveness |  | ◆ Make sure the control signal is correctly inputted<br>◆ Make sure the ground wire of the control signal is correctly connected to the controller<br>◆ Make sure the Logical Relation of the control signal is set correctly as you expectation |
| 4 | Beat phenomena |  | ◆ Avoid vibration coupling among the vibrators<br>◆ Heighten the resonant frequency of the vibrators |
| 5 | Displays normally,<br>no output, but sound<br>can be heard |  | ◆ Adjust all parameters as this book instructed |
| 6 | Err01 | ![Seven-segment display symbol Err01](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0046-vcrop-00.png) | ◆ Output in short-circuit, Make sure the Output Power Cable and the coil are not shorted out |
| 7 | Err02 | ![Seven-segment display symbol Err02](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0046-vcrop-01.png) | ◆ Output Over current, Reduce the Output Voltage value and make sure the armature gap is not too big |
| 8 | Err03 | ![Seven-segment display symbol Err03](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0046-vcrop-02.png) | ◆ Overheat, Place the controller in well ventilated environment |
| 9 | Err04 | ![Seven-segment display symbol Err04](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0046-vcrop-03.png) | ◆ Reserved, please contact us |
| 10 | Err05 | ![Seven-segment display symbol Err05](assets/images/cuh.sdvc31-U.series.manual.v3.01/page-0046-vcrop-04.png) | ◆ Reserved, please contact us |


**Nanjing CUH Science & Technology Co., Ltd**

![CUH QR code](assets/images/page-0048-vcrop-00.png)



No. 1 Xiaodong Road, Chenguang Village, Qilin, Nanjing, Jiangsu, China  
Tel: +86-25-84730415  
Fax: +86-25-84730426  
Email: sales@cuhnj.com  
Website: en.cuhnj.com


