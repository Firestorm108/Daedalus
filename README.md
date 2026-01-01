# Daedalus
An STM32F405RGT6 based flight computer! It has integrated battery management, meaning you can connect up a 3.7V Li-Po directly to the board without worries!
It's also got an altimeter, 6-axis IMU, and a microSD card slot so you can track all your flight data and review post-launch.
The 5V boost line means you can power your components from the board! There are 4 MOSFET-controlled outputs to support this, including one ignition switch.

<img width="414" height="1020" alt="image" src="https://github.com/user-attachments/assets/b164f08e-c863-4789-8950-ea06fd7557b1" />
<img width="1296" height="931" alt="image" src="https://github.com/user-attachments/assets/1b5d5fe4-ddab-4489-94fa-d231c5073285" />
<img width="364" height="961" alt="image" src="https://github.com/user-attachments/assets/b5ab7e66-2f06-4087-baa1-5ea40e96101f" />

## Bill of Materials (BOM)

| Id | Designator | Footprint | Quantity | Comment | Supplier and Ref |
|----|------------|-----------|----------|---------|------------------|
| 1 | C17,C4,C9,C6,C2,C5,C1,C18,C13,C16,C23,C8,C22,C3,C12 | C_0402_1005Metric | 15 | 0.1uF | |
| 2 | U7 | Texas_DRC0010J_ThermalVias | 1 | TPS63000 | |
| 3 | R22,R13,R5,R8,R12,R11,R23,R9,R6,R10,R7,R21,R14,R15,R3,R24,R18 | R_0402_1005Metric | 17 | 10K | |
| 4 | U1 | LQFP-64_10x10mm_P0.5mm | 1 | STM32F405RGTx | |
| 5 | U2 | SOT-23 | 1 | MCP1700x-330xxTT | |
| 6 | Q1,Q3,Q2,Q4 | SOT-23 | 4 | AO3400A | |
| 7 | TP2,TP1 | TestPoint_Plated_Hole_D2.0mm | 2 | TestPoint | |
| 8 | R16,R19,R20 | R_0402_1005Metric | 3 | 1.5K | |
| 9 | SW1,SW2 | SW_Push_SPST_NO_Alps_SKRK | 2 | SW_Push | |
|10 | D3,D2 | LED_0603_1608Metric | 2 | LED | |
|11 | C26,C25,C24,C7,C19 | C_0402_1005Metric | 5 | 1uF | |
|12 | J5,J4 | PinHeader_1x03_P2.54mm_Vertical | 2 | Servo | |
|13 | C21,C14,C15,C20 | C_0402_1005Metric | 4 | 4.7uF | |
|14 | D1 | LED_0603_1608Metric | 1 | Power LED | |
|15 | R4 | R_0402_1005Metric | 1 | 1K | |
|16 | C27,C28 | C_0603_1608Metric | 2 | 10uF | |
|17 | U4 | LGA-16_3x3mm_P0.5mm_LayoutBorder3x5y | 1 | ICM-20602 | |
|18 | U5 | VQFN-16-1EP_3x3mm_P0.5mm_EP1.6x1.6mm | 1 | BQ24072RGT | |
|19 | R25 | R_0402_1005Metric | 1 | 27 | |
|20 | U3 | Texas_DRT-3 | 1 | TPD2EUSB30 | |
|21 | C11,C10 | C_0402_1005Metric | 2 | 33pF | |
|22 | U6 | QFN_BMP388_BOS | 1 | BMP388 | |
|23 | J1 | USB_C_Receptacle_HRO_TYPE-C-31-M-12 | 1 | USB_C_Receptacle_USB2.0_14P | |
|24 | J2 | MOLEX_503398-1892 | 1 | MicroSD 503398-1892 | |
|25 | R2,R1 | R_0402_1005Metric | 2 | 5.1K | |
|26 | J9 | PinHeader_1x02_P2.54mm_Vertical | 1 | Ignition | |
|27 | J6,J3,J7 | PinHeader_1x02_P2.54mm_Vertical | 3 | Switched | |
|28 | R17 | R_0402_1005Metric | 1 | 2.2K | |
|29 | L1 | L_0805_2012Metric | 1 | 2.2uH | |
|30 | Y1 | Crystal_SMD_3225-4Pin_3.2x2.5mm | 1 | 8MHz | |
