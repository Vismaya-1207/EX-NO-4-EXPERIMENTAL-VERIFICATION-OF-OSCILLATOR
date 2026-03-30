# EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR

4. ## **EX.NO:* ## EXPERIMENTAL VERIFICATION OF RC Phase Shift and Wien Bridge oscillators 
	
 ## AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
 ## THEORY:
 
 ## RC PHASE SHIFT OSCILLATOR
 
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 



---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR
<img width="952" height="976" alt="image" src="https://github.com/user-attachments/assets/dd2b5792-8183-4214-9245-8373279357f6" />



---

## MODEL GRAPH
<img width="414" height="324" alt="image" src="https://github.com/user-attachments/assets/3389b740-b70e-4148-9bf9-e5319627260f" />

## DESIGN

## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/4e8dc3b2-4794-4266-bae3-59d210d80515" />



---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION

<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/8e233b96-7fa4-4983-aa59-637e71b9d7d7" />

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1600" height="1477" alt="image" src="https://github.com/user-attachments/assets/db5e2476-43ed-47d6-80a8-50aea690dd1c" />


---
## THEORY
 ##WIEN BRIDGE
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR
<img width="570" height="480" alt="image" src="https://github.com/user-attachments/assets/be71f26e-36ad-4677-8117-51362146cbbd" />


---
## MODEL GRAPH
<img width="414" height="325" alt="image" src="https://github.com/user-attachments/assets/1cc285f7-05c7-4b65-af59-b28cf039fcd3" />

---

## DESIGN

## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ

<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/78ac11ab-eca5-41ae-ba2a-1d67ee6e54c9" />

---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION

<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/50a8762d-1506-4950-adb4-fb2d7206d6ce" />

---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1600" height="1121" alt="image" src="https://github.com/user-attachments/assets/bb1a44c5-968a-4bd4-8e8c-f88a3417931f" />


---
## RESULT:

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
<img width="2160" height="2054" alt="image" src="https://github.com/user-attachments/assets/033dbbea-7c65-48e6-b993-09a448cad536" />

