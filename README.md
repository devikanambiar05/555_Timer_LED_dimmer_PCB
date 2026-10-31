# 555 Timer LED Dimmer Circuit

This project contains the KiCad project files for a custom-designed PCB of a 555 Timer-based LED dimmer circuit. The circuit uses the NE555 timer IC to generate a PWM (Pulse Width Modulation) signal, allowing the brightness of an LED to be controlled by adjusting the duty cycle.

## Circuit Design

The circuit is based on the NE555 timer IC configured in astable mode to generate a PWM signal. The duty cycle of the output signal can be varied using a potentiometer, which controls the brightness of the connected LED.

The 555 timer continuously generates pulses at a fixed frequency, while adjusting the potentiometer changes the ON and OFF time of the output signal. This allows smooth LED brightness control without significantly changing the LED's operating voltage.

The circuit is powered using a DC supply, and the output stage controls the LED according to the generated PWM signal.

Below is the schematic of the LED dimmer circuit.

<img width="515" height="326" alt="image" src="https://github.com/user-attachments/assets/d5ca788e-0f36-49cc-b21f-b58aa4ecb129" />


## PCB Design

The PCB layout for the circuit is designed using KiCad. The components are arranged to keep the circuit compact and ensure proper routing between the 555 timer, timing components, potentiometer, and LED output stage.

The PCB includes footprints for all the required components, along with input power and output connections. The potentiometer is accessible for convenient adjustment of LED brightness.

Below is the final PCB layout after routing.

<img width="377" height="263" alt="image" src="https://github.com/user-attachments/assets/59399b73-2e35-4f9b-b792-daef8fb003bc" />


## 3D View

The 3D view of the finalized PCB provides a representation of the assembled board, showing the component placement and overall PCB dimensions.

<img width="587" height="361" alt="image" src="https://github.com/user-attachments/assets/30dc2349-b4da-4c59-ba4f-836288f11211" />
<img width="671" height="326" alt="image" src="https://github.com/user-attachments/assets/dd4fc428-7e38-422e-8cfe-dfb03ab54621" />


## Technologies Used

- KiCad
- NE555 Timer IC
- PWM (Pulse Width Modulation)
- PCB Design and Routing
