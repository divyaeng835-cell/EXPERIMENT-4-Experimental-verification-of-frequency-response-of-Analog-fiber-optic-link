
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---


## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502   
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

![WhatsApp Image 2025-11-25 at 11 09 03_fd628f3a](https://github.com/user-attachments/assets/bab022c9-444d-40ea-b9d2-4c20115a2d79)


---

## CONNECTION DIAGRAM  
**Setting up an Analog Link**

*(Insert connection diagram here)*

---

## TABULATION  
**Transmission through Analog Link**

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
|----------------|------------------------------|--------------|------------|
|  50 Hz         |    1380                      |   0.644      |   1.938    |
|  3.33 Hz       |    1500                      |   0.700      |   1.549    |
|  9.86 Hz       |    1480                      |   0.691      |   1.605    |
|  10.2 KHz      |    1480                      |   0.691      |   1.605    |
|  13 KHz        |    1460                      |   0.68       |   1.674    |
|  16 KHz        |    1440                      |   0.672      |   1.726    |
|  33 MHz        |    1400                      |   0.654      |   1.844    |
|  3 MHz         |    1360                      |   0.028      |   1.526    |

---

## MODEL GRAPH

![WhatsApp Image 2025-11-25 at 11 09 14_5c33330a](https://github.com/user-attachments/assets/a2c75a52-c4b9-4006-ae60-a8e7f656d40e)

## OUTPUT FRAPH
![WhatsApp Image 2025-11-25 at 11 19 28_15b11d80](https://github.com/user-attachments/assets/9acc533d-cc3e-42f9-9f47-59f3bd913e74)

---

## RESULT
The relationship between input and received signal of a 660nm fiber optic cable using analog and digital link are analyzed completely.

