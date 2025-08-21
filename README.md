# EXPERIMENT--01-ALP-FOR-8086
## Name : HEMNATH R
## Roll no : 212224240057 
## Date of experiment : 21.08.2025





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
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 16 bit ALP 
~~~
org 100h
mov ax,7ab3h
mov bx,54bah
add ax,bx
ret
~~~

## Output 

<img width="1920" height="1200" alt="Screenshot (114)" src="https://github.com/user-attachments/assets/bbd42637-d6e6-4297-a2a9-2229f6103207" />

 
## Subtraction   of 16 bit numbers  ALP 
~~~
org 100h
mov ax,7ab3h
mov bx,[3cbdh]
mov cx,ax
sub ax,cx
ret
~~~
## Output 
<img width="1920" height="1200" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/3f003acd-9c9f-4deb-94eb-fbd1a5aec035" />

## Multiplication of 16 bit numbers ALP
~~~
org 100h
mov ax,7ab3h
mov bx,3cbdh
mul bx
ret
~~~
## Output  
<img width="1920" height="1200" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/ff6ad8fe-8f36-4bbd-942e-bacf1b66bdf7" />


## Division of 16 bit numbers ALP 
```
org 100h
mov ax,7ab3h
mov bx,[3cbdh]
div bx
ret
```
## Output  
<img width="1920" height="1200" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/a3277823-0195-4e35-a40f-2e0aeedb6ce9" />

## AND Operation of 16 bit ALP
```
org 100h
mov ax,5aa3h 
mov bx,8090h
mov ax,[bx]
and ax,bx
ret
```
## Output

<img width="1920" height="1200" alt="Screenshot (113)" src="https://github.com/user-attachments/assets/aac25aa3-eb94-4e54-b822-50c43663c095" />


## OR Operation of 16 bit ALP
```
org 100h
mov ax,5aa3h 
mov bx,8090h
or ax,bx
ret
```

## Output


<img width="1920" height="1200" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/d074f972-b50d-4719-b9dc-23ce4b30274b" />



## NOT Operation of 16 bit ALP
```
org 100h
mov ax,5aa3h 
mov bx,[8090h]
not bx
ret
```
## Output

<img width="1920" height="1200" alt="Screenshot (112)" src="https://github.com/user-attachments/assets/f54b5922-e63f-41a6-a534-42619f7c2f4d" />

## XOR Operation of 16 bit ALP
```
org 100h
mov ax,5aa3h  
mov bx,[8090h]  
mov ax,[bx]
xor ax,bx
ret
```
## Output

<img width="1920" height="1200" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/e8da19d2-94e1-4554-bf49-cfbeda2d0f76" />

## Result :
Thus, to write and execute ALP on fundamental arithmetic and logical operations is successfully executed
