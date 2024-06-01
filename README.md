# 8085 exercise no.1

Every 30ms an isolated port with address 0Ah is read
data. If bits 2 and 5 are 1 and 0 respectively in memory
mapped port at address F00Ah is sent read
data divided by 2, otherwise the read data is sent
multiplied by 7. The frequency of the oscillator crystal is
5MHz.

 If bit 2,5==1,0 If bit 2,5==1,0 If bit 2,5==1,0
 F00Ah Data/2
 Else
 F00Ah Data*7 

![Screenshot (1)](https://github.com/tamaraatanasova/8085-Zadaca1/blob/main/image1.png)

Exercise of Low Level Programming with 8085 Assembly Lecture



[Tamara Atanasova ](https://github.com/tamaraatanasova)


**Subject**

Microcomputer's systems

**Built With**

This project is built using the following tools:

- [Emu8085](https://8085-emulator.soft112.com/download.html): Assembler and emulator for the Intel 8085 microprocessor.

- [Online_emulator](https://www.sim8085.com/): You can use online emulator as well

**Prerequisites**

In order to run this project you need:

A working computer
Connection to internet
Setup







