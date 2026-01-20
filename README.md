# PIC16F877A
 Familiarization of PIC16F877A

## What is PIC16F877A?
PIC16F877A is an 8-bit microcontroller developed by Microchip Technology. It is widely used in embedded systems for learning and small-to-medium control applications.

## Key Features
- 8-bit RISC architecture
- Up to 20 MHz operating frequency
- 8K words of Flash program memory
- 368 bytes of RAM
- 256 bytes of EEPROM
- 33 I/O pins
- 10-bit ADC (8 channels)
- Timers (Timer0, Timer1, Timer2)
- USART, SPI, I2C communication
- Watchdog Timer

## Architecture Overview
PIC16F877A uses Harvard architecture, meaning program memory and data memory are separate. This improves execution speed.

## Pin Diagram
<img width="565" height="475" alt="image" src="https://github.com/user-attachments/assets/04d4e022-7aab-48e3-b166-f207c9b6f27f" />


## Applications
- LED control systems
- Temperature monitoring
- Motor control
- Home automation
- Embedded system learning projects

## Tools Used
- MPLAB X IDE
- XC8 Compiler
- PIC16F877A Microcontroller

## Author
Jeffin Paul

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Communication Protocols

## What is a Communication Protocol?
A communication protocol is a set of rules that defines how data is transmitted and received between devices.  
It specifies data format, timing, synchronization, and direction of data flow.

---

## Modes of Communication

### 1. Simplex Communication
- One-way communication only
- Data flows in a single direction
- No feedback from receiver

**Examples:**
- Keyboard → Computer  
- Television broadcast  
- Radio transmission  

---

### 2. Half Duplex Communication
- Two-way communication
- Data flows in both directions, but not simultaneously

**Examples:**
- Walkie-talkie  
- RS-485  
- CAN bus  

---

### 3. Full Duplex Communication
- Two-way communication
- Data flows in both directions simultaneously

**Examples:**
- Telephone communication  
- Ethernet  
- UART communication  

---

## Types of Communication Protocols

### 1. UART / USART
- Asynchronous serial communication
- Uses TX and RX lines

**Communication Mode:** Full Duplex  

**Applications:**
- Microcontroller to PC communication  
- Bluetooth modules  
- GPS modules

![UART - Copy](https://github.com/user-attachments/assets/21605214-b849-4708-b24b-a36161c3a554)


---

### 2. SPI (Serial Peripheral Interface)
- High-speed serial communication
- Master-slave architecture
- Uses MOSI, MISO, SCLK, SS

**Communication Mode:** Full Duplex  

**Applications:**
- Sensors  
- Displays  
- Memory devices

<img width="440" height="215" alt="peri_api_spi_diagram" src="https://github.com/user-attachments/assets/b485bca1-d2db-4051-81f1-5b643b205660" />

---

### 3. I²C (Inter-Integrated Circuit)
- Two-wire communication
- Uses SDA (data) and SCL (clock)
- Address-based communication

**Communication Mode:** Half Duplex  

**Applications:**
- EEPROM  
- RTC modules  
- Sensors

<img width="551" height="194" alt="peri_api_i2c_diagram" src="https://github.com/user-attachments/assets/4575e91e-6011-4409-b773-9e49f0d82730" />

---

### 4. CAN (Controller Area Network)
- Multi-master communication
- High reliability and error detection

**Communication Mode:** Half Duplex  

**Applications:**
- Automotive systems  
- Industrial automation  

---

### 5. MODBUS
- Industrial communication protocol
- Master–slave (client–server) architecture
- Data exchanged using registers and coils
- Common variants: **Modbus RTU**, **Modbus ASCII**, **Modbus TCP**

**Communication Mode:**  
- Half Duplex (Modbus RTU / ASCII over RS-485)  
- Full Duplex (Modbus TCP over Ethernet)

**Applications:**
- PLC communication  
- SCADA systems  
- Industrial automation  
- Power and energy monitoring


# UART : SERIAL COMMUNICATION WITH PIC MICROCONTROLLER

### Circuit Diagram: Transmission Rreception
<img width="1198" height="708" alt="image" src="https://github.com/user-attachments/assets/6d181c35-c669-425d-b0fd-88feb8d787fc" />

# SPI : SERIAL COMMUNICATION WITH PIC MICROCONTROLLER

### Circuit Diagram: Transmission Reception
<img width="1078" height="617" alt="image" src="https://github.com/user-attachments/assets/37b3fd6f-f057-487c-89a6-cef6a6ac00fd" />

# I2C : SERIAL COMMUNICATION WITH PIC MICROCONTROLLER

### Circuit Diagram: Transmission Reception
<img width="1237" height="856" alt="image" src="https://github.com/user-attachments/assets/0c6ff60d-6206-4e30-a5c9-c64d2b27d15d" />


# PROJECTS

### 1. LED with switch:

<img width="675" height="494" alt="image" src="https://github.com/user-attachments/assets/081a211b-ec41-4b38-9425-26915ff8ac2d" />

## 2. DC Motor

<img width="1183" height="760" alt="image" src="https://github.com/user-attachments/assets/8fe47265-b00d-4bdc-95f3-d8f6a2c2efb3" />

## 3. 7 Segment

<img width="1198" height="751" alt="image" src="https://github.com/user-attachments/assets/4dcd463c-093d-4ec2-97ba-eea51715a74d" />

## 4. Double 7 Segment

<img width="944" height="686" alt="image" src="https://github.com/user-attachments/assets/648ecc36-be31-468b-87b3-caa60329c848" />

## 5. LCD Display

<img width="985" height="730" alt="image" src="https://github.com/user-attachments/assets/01ddc320-8224-41a7-a976-5a16ecb33915" />

## 6. Interrupt

<img width="955" height="522" alt="image" src="https://github.com/user-attachments/assets/a2ce48bc-5470-4895-b124-5b71a526cb05" />

## 7. Timer 2

<img width="796" height="518" alt="image" src="https://github.com/user-attachments/assets/1d4c1105-3f8d-491f-9b27-c73779aa21fd" />

## 8. Timer 1

capture:<img width="1247" height="827" alt="image" src="https://github.com/user-attachments/assets/33eb0fa8-af1e-4de3-83e8-cd190e7d132c" />

compare:<img width="941" height="514" alt="image" src="https://github.com/user-attachments/assets/7a1e9079-c199-499f-b1ae-e814e66c64c9" />

## 9. Timer 0


## 10. ADC

<img width="1028" height="560" alt="image" src="https://github.com/user-attachments/assets/0472f756-3c14-4838-b618-f1222ba4d38c" />


## 11. UART Communication
Displaying message on LCD screen with respect to each switch pressed.

<img width="1324" height="598" alt="Screenshot 2026-01-13 124729" src="https://github.com/user-attachments/assets/2bc104ad-04e4-4c12-9ff7-ea20f46f9580" />

## 12. Basic Calculator

<img width="901" height="694" alt="Screenshot 2026-01-15 120901" src="https://github.com/user-attachments/assets/ddc0b5e4-db66-457d-b6eb-1e9b14707ddb" />

