# EXPERIMENT NO. 4 – HALF WAVE AND FULL WAVE BRIDGE RECTIFIERS

| **Name:** |Dharshini B | **Reg. No.:** |26013000 |
|---|---|---|---|
| **Date:** |21-11-2026 | **Batch / Section:** |26ODJ102 |

---

## AIM

To study the half wave and full wave bridge rectifiers with and without filter and to observe their input and output waveforms using Proteus.

## COMPONENTS AND EQUIPMENT REQUIRED

| S. No. | Components / Equipment |
|:---:|:---|
| 1 | Diodes |
| 2 | Resistor (load) |
| 3 | Capacitors (filter) |
| 4 | Step-down transformer |
| 5 | Voltmeter |
| 6 | Ammeter |
| 7 | Breadboard |
| 8 | CRO |
| 9 | Connecting wires |
| 10 | Simulation software – Proteus Design Suite |

## THEORY

A rectifier changes AC to DC and is an essential part of a power supply. The unique property of a diode, permitting current to flow in only one direction, is utilised in rectifiers.

### Half wave rectifier

Mains supply is applied to the primary of the step-down transformer. All the positive half cycles of the stepped-down AC supply pass through the diode and all the negative half cycles are eliminated. The peak value of the output voltage is less than the peak value of the input voltage by about 0.6 V because of the voltage drop across the diode. For a half wave rectifier, **Vrms = Vm/2** and **Vdc = Vm/π**, where Vrms is the RMS value of the output, Vdc is the average value of the output and Vm is the peak value of the output.

### Full wave bridge rectifier

During the positive half cycle of the secondary voltage, diodes D1 and D3 are forward biased and D2 and D4 are reverse biased, so current flows through the secondary winding, D1, the load resistor and D3. During the negative half cycle, D2 and D4 are forward biased and D1 and D3 are reverse biased, so current flows through the secondary winding, D2, the load resistor and D4. In both half cycles the current through the load resistor is in the same direction. The peak output voltage is less than the peak input voltage by about 1.2 V due to the drop across two diodes. For a full wave bridge rectifier, **Vrms = Vm/√2** and **Vdc = 2Vm/π**.

### Filters

All rectifier outputs contain a considerable amount of ripple in addition to the DC component. To remove the AC components, a filter is connected at the output of the rectifier. Capacitor input, choke input, RC, CRC, LC and CLC filters are commonly used; the capacitor input filter is the simplest and cheapest. A high-value capacitor C is connected in shunt with the load resistor RL. The capacitor charges to the peak voltage when a half cycle appears at the output. After the peak, the capacitor discharges slowly through RL, since the diode is reverse biased by the capacitor voltage. Before the capacitor voltage drops substantially, the next output cycle arrives and the capacitor recharges to the peak.

## PROCEDURE

1. Wire up the half wave rectifier circuit without capacitor after testing all the components.
2. Switch on the mains supply. Observe the transformer secondary voltage waveform and the output voltage waveform across the load resistor simultaneously on the CRO.
3. Connect the capacitor filter across the load and observe the waveforms. Repeat for different capacitor values.
4. Repeat the above steps for the full wave bridge rectifier.
5. Simulate both rectifiers, with and without filter, in Proteus and capture the input and output waveforms on the virtual oscilloscope.

## CIRCUIT DIAGRAMS

### Half wave rectifier without filter
<img width="515" height="235" alt="Screenshot 2026-11-21 212912 5" src="https://github.com/user-attachments/assets/bc4778ea-347c-4575-84fe-d4e80fec835a" />


**Figure 1:** Half wave rectifier without filter

### Half wave rectifier with filter

<img width="640" height="300" alt="image" src="https://github.com/user-attachments/assets/63b7343b-c6ac-4d6d-b2cd-9fc4e1a66c03" />


**Figure 2:** Half wave rectifier with filter

### Full wave bridge rectifier without filter

<img width="673" height="252" alt="image" src="https://github.com/user-attachments/assets/08340066-566e-411e-b2fa-68701d58305d" />


**Figure 3:** Full wave bridge rectifier without filter

### Full wave bridge rectifier with filter

*<img width="589" height="290" alt="image" src="https://github.com/user-attachments/assets/bb748352-0a2f-4068-8deb-f46eb613f5d2" />


**Figure 4:** Full wave bridge rectifier with filter

## SIMULATION AND WAVEFORMS USING PROTEUS

Build each rectifier in Proteus, with and without the capacitor filter. Use the virtual oscilloscope to display the input (secondary) and output waveforms together, and paste the screenshots below.

### Half wave rectifier without filter – waveform

<img width="782" height="457" alt="image" src="https://github.com/user-attachments/assets/23cb446c-8282-4c1e-8285-68f1ddeef3ac" />
<img width="737" height="386" alt="WhatsApp Image 2026-11-22 at 1 28 58 PM" src="https://github.com/user-attachments/assets/fc879068-9d72-40d6-b582-25ef4430e106" />



**Figure 5:** Proteus waveform – half wave rectifier without filter

### Half wave rectifier with filter – waveform

<img width="848" height="628" alt="WhatsApp Image 2026-11-22 at 1 28 56 PM" src="https://github.com/user-attachments/assets/ae3f5c20-5b13-4cd5-862d-7378389fd3eb" />
<img width="738" height="372" alt="WhatsApp Image 2026-11-22 at 1 28 57 PM" src="https://github.com/user-attachments/assets/6d62db3d-fea4-48e9-bdf8-f41687ca2f8a" />



**Figure 6:** Proteus waveform – half wave rectifier with filter

### Full wave bridge rectifier without filter – waveform

<img width="1046" height="402" alt="image" src="https://github.com/user-attachments/assets/a004e13a-b3e8-4992-af03-63bfabf6483e" />
<img width="801" height="422" alt="image" src="https://github.com/user-attachments/assets/24381e48-37d5-4260-b840-291c24630a23" />


**Figure 7:** Proteus waveform – full wave bridge rectifier without filter

### Full wave bridge rectifier with filter – waveform

<img width="1040" height="321" alt="image" src="https://github.com/user-attachments/assets/bec2d1db-f5b7-4335-8ce4-6f5e2c82bbb1" />
<img width="785" height="412" alt="image" src="https://github.com/user-attachments/assets/4e2e32bb-62b4-4155-88fc-31716950ab32" />


**Figure 8:** Proteus waveform – full wave bridge rectifier with filter

## FORMULAE

### A. Half wave rectifier

- Average (DC) voltage: **Vdc = Vm / π**
- Average (DC) current: **Idc = Im / π**
- RMS voltage: **Vrms = Vm / 2**
- RMS current: **Irms = Im / 2**
- Ripple factor: **γ = √[(Vrms / Vdc)² − 1] = 1.21**
- Rectification efficiency: **η = Pdc / Pac × 100 = (Idc² RL) / (Irms² RL) × 100 = 40.6 %**
- Form factor: **FF = Vrms / Vdc = 1.57**
- Peak factor: **PF = Vm / Vrms = 2**
- Peak inverse voltage: **PIV = Vm**

### B. Full wave bridge rectifier

- Average (DC) voltage: **Vdc = 2Vm / π**
- Average (DC) current: **Idc = 2Im / π**
- RMS voltage: **Vrms = Vm / √2**
- RMS current: **Irms = Im / √2**
- Ripple factor: **γ = √[(Vrms / Vdc)² − 1] = 0.482**
- Rectification efficiency: **η = Pdc / Pac × 100 = (Idc² RL) / (Irms² RL) × 100 = 81.2 %**
- Form factor: **FF = Vrms / Vdc = 1.11**
- Peak factor: **PF = Vm / Vrms = √2 = 1.414**
- Peak inverse voltage: **PIV = Vm**

### C. With capacitor filter

- Half wave: **γ = 1 / (2√3 f C RL)**
- Full wave bridge: **γ = 1 / (4√3 f C RL)**

### D. Regulation

- **% Regulation = (VNL − VFL) / VFL × 100**

Vm – peak output voltage; Im – peak load current (Im = Vm / RL); RL – load resistance; f – supply frequency (50 Hz); C – filter capacitance; VNL – no-load voltage; VFL – full-load voltage.

## RESULT

Thus, the input and output waveforms of the half wave and full wave bridge rectifiers with and without filter were observed using Proteus.
