# MCC Melody for PIC16 - UART Print String to Terminal

Send string output from PIC16 to terminal via UART, configured via MCC Melody.

## 📹 Video Tutorial
https://youtu.be/mc2_sT8akK8

## 🛠️ Tools & Hardware
- MPLAB X IDE
- MCC Melody
- PIC16F13145 Curiosity Nano (EV06M52A)

## 📋 What it does
- Sends a custom string via EUSART1 using a custom `uartString()` function
- Also demonstrates `printf()` output through UART
- Output is viewable in any serial terminal (e.g. MPLAB Data Visualizer, Tera Term)
