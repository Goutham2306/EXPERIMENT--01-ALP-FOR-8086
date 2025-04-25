## EXPERIMENT--01-ALP-FOR-8086
## Name :Goutham.K
## Roll no :212223110019
## Date of experiment :10/03/2025





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)
9.	Click on emulate to start emulation 
![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)
10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 
![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)
## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AL, 80H
MOV BL, 90H
ADD AL,BL
HLT

```
## Output  
 ![Screenshot 2025-03-07 132746](https://github.com/user-attachments/assets/23a30cd2-7dec-4f27-8657-2bf063e77e87)

## Subtraction   of 8 bit numbers  ALP 
```
MOV AL,90H    
MOV BL,80H
SUB AL,BL
HLT
```
## Output  
![Screenshot 2025-03-07 132907](https://github.com/user-attachments/assets/95f77819-1fb1-47de-896b-d06e4d137d2a)

## Multiplication alp 
```
MOV AL,90H    
MOV BL,80H
MUL BL
HLT
```
 ## Output  
![Screenshot 2025-03-07 133134](https://github.com/user-attachments/assets/8950671b-bb02-45b8-971a-004fe430e2c3)


## Division alp 
```
MOV AL,90H    
MOV BL,80H
DIV BL
HLT
```

## Output  
![Screenshot 2025-03-07 133656](https://github.com/user-attachments/assets/0d719a15-29f3-4a05-9a17-3f2db30cb33b)

## Programs For Logical Operation
## AND operation
```
MOV AL, 5Ah  
MOV BL, 3Ch  
AND AL, BL   
MOV CL, AL 
```
## OR operation 
```
MOV AL, 5Ah  
OR AL, BL    
MOV DL, AL
```
## XOR operation 
```
MOV AL, 5Ah  
XOR AL, BL   
MOV DH, AL
```
## NOT operation 
```
MOV AL, 5Ah  
NOT AL       
MOV BH, AL
```
## Output
![Screenshot 2025-03-11 110729](https://github.com/user-attachments/assets/36ca76d7-87e2-4441-8be4-9eaa58a2c13f)

## Output:
![image](https://github.com/user-attachments/assets/46525010-b313-403f-8e50-56f15aa70052)

## NOT Operation of 8 bit ALP
```
org 100h
MOV BX,4444h
NOT BX
MOV [6020h],AX
```
## Output:
![image](https://github.com/user-attachments/assets/e4ba9493-303d-4a14-978f-b7f126ecff79)

## XOR Operation of 8 bit ALP
```
org 100h          
MOV AX,702H
MOV BL,10H
XOR [6030h],AL
HLT
```
## Output
![image](https://github.com/user-attachments/assets/f3cd500a-f023-4988-a94d-339763a6f15d)

## Result :
The program has been executed successfully.








