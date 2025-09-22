# EXPERIMENT--01-ALP-FOR-8086
# Name : HEMNATH R
# Roll no 212224240057
# Date of experiment : 21/08/2025
## Aim: To Write and execute ALP on fundamental arithmetic and logical operations:
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
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 16 bit ALP :
~~~
org 100h

mov ax,2424h
mov bx,8383h
add ax,bx

ret
~~~
## Output  
 <img width="970" height="898" alt="Screenshot 2025-08-21 134418" src="https://github.com/user-attachments/assets/483081a9-fe74-49e6-8a40-94bb4637b03f" />
 
## Subtraction   of 16 bit numbers  ALP :
 ~~~
org 100h

mov ax,1234h
mov bx,5678h
mov cx,bx
sub cx,ax

ret
 ~~~
## Output 
<img width="960" height="893" alt="Screenshot 2025-08-21 141031" src="https://github.com/user-attachments/assets/311a1e54-de39-484f-9e46-02c83a97678e" />

## Multiplication of 16 bit alp :
~~~
org 100h

mov ax,1111h
mov bx,2222h
mul bx

ret
~~~
 ## Output  
<img width="963" height="906" alt="image" src="https://github.com/user-attachments/assets/7baf8212-a6fd-4371-b150-46a263efffae" />


## Division of 16 bit alp :
~~~
org 100h

mov ax,3323h
mov bx,[4434h]
div bx

ret
~~~

## Output  
<img width="1191" height="900" alt="image" src="https://github.com/user-attachments/assets/1cf90915-9a60-4a08-b3ab-418f34a19a2f" />

## And of 16 bit numbers ALP :
~~~
org 100h

mov ax,1234h
mov bx,5678h
and ax,bx

ret
~~~
## output:
<img width="1187" height="918" alt="image" src="https://github.com/user-attachments/assets/76119790-8ca1-41a9-8e9c-cdd76f59eb94" />

## OR of 16 bit numbers ALP :
~~~
org 100h

mov ax,2468h
mov bx,1357h
or ax,bx

ret
~~~
## output :
<img width="1202" height="919" alt="image" src="https://github.com/user-attachments/assets/92aaa887-9e92-4d4c-aee8-3c847667717e" />

## NOT of 16 bit number ALP :
~~~
org 100h

mov ax,8765h
not ax

ret
~~~
## output:
<img width="1198" height="922" alt="image" src="https://github.com/user-attachments/assets/aefa1f1d-773d-4760-92ea-8b8f587014ae" />

## XOR of 16 bit number ALP :
~~~
org 100h

MOV AX,12ABH
MOV BX,34CDH
XOR AX,BX

ret
~~~
## output:
<img width="1200" height="909" alt="image" src="https://github.com/user-attachments/assets/b68d5ad1-b943-4d41-9ed7-f4a204ca2dfc" />


## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








