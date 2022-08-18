# Lab04
## Microcomputers-Group_11-Lab_04
SRI LANKA INSTITUE OF INFORMATION TECHNOLOGY  
B.Sc. Eng. Department of Electronic & Computer Engineering  
EC 2131 – Micro Computers  
Laboratory 04   - group 11
 

Module Details 	
Module Code 	EC 2131	
Module Title 	Micro Computers  
Program: SLIIT 		Course: BSc/ BEng/ 
Stream: Electronics	
Assessment details 			
Title 	GROUP PROJECT	Group assignment - YES
Group No. 	11
Lecturer/ Instructor  -Mr.Lasantha Seneviratne	 	
Date of Performance 	-20/07/2022 
Due date            	-19/08/2022	
Date submitted      	-19/08/2022 
Details of the student/s  
ID Number 	Name (As per the institute records ) 	
- Amarakoon A.M.D.P -EN21468292
- W.D.K. Ruvishan. -EN21493942
- Peiris A.B.S. -EN21484032

## Content

- Objective
- Apparatus
- Introduction
- Task
- Operation Table
- Breadboard Implementation
- The PCB Design
- An Image of the Real Implementation
- Code
- Results
- Discussion
- References

## Objective

The main objective of this lab is for you to develop a small water level controlling system of a water tank using the knowledge of interrupts and other programming techniques of PIC16f877a from all the labs we did throughout the course.

## Apparatus

- PCB board
- Breadboard power supply module
- two DC motors
- ultrasonic distance sensors
- 20 cm Wires
- Capacitors 
 - 470µF
 - 47µF
 - 22pF
- Crystal oscillator
- Pic adaptor
- PIC16F877A
- IN4007GL Diode
- Soldering iron
- L293D ic
 ![Picture 7](RackMultipart20220814-1-xydplv_html_95bf67d4ae04b375.gif)

![Shape2](RackMultipart20220814-1-xydplv_html_58e784f1c113c381.gif) ![Picture 2](RackMultipart20220814-1-xydplv_html_e9a6663106c90e76.gif)

 ![Picture 4](RackMultipart20220814-1-xydplv_html_ebbde0f9a9520579.gif) ![Picture 2](RackMultipart20220814-1-xydplv_html_17175841329071ce.gif) ![Picture 8](RackMultipart20220814-1-xydplv_html_75d8aeddebe45796.gif)

**ultrasonic distance sensors Breadboard power supply module DC motors**

**IN4007GL Diode**  **Soldering iron**

**Crystal oscillator**

**L293D ic**

**Pic adaptor**

**PIC16F877A**

## Introduction

The project's goal is to build a mechanism that automatically regulates the water level. The suggested system is implemented using a PIC microcontroller and ULTRA SONIC sensors to detect the water level inside a tank and automatically turn on or off two DC motors depending on that information.

The results of the experiments indicate that the suggested system is successful in determining the water level and turning the water pump ON or OFF in accordance with the water level.

PIC microcontrollers (Programmable Interface Controllers) are electronic circuits that may be programmed to carry out a range of tasks. They can be configured to do a variety of tasks, including managing a production line and serving as timers. You can program a PIC microcontroller with a variety of software. Some individuals still program PIC Microcontrollers in assembly language.

An ultrasonic sensor is an electronic device that measures the distance of a target object by emitting ultrasonic sound waves, and converts the reflected sound into an electrical signal. Ultrasonic waves travel faster than the speed of audible sound (i.e. the sound that humans can hear). Ultrasonic sensors have two main components: the transmitter (which emits the sound using piezoelectric crystals) and the receiver (which encounters the sound after it has travelled to and from the target).

In order to calculate the distance between the sensor and the object, the sensor measures the time it takes between the emission of the sound by the transmitter to its contact with the receiver. The formula for this calculation is D = ½ T x C (where D is the distance, T is the time, and C is the speed of sound ~ 343 meters/second). For example, if a scientist set up an ultrasonic sensor aimed at a box and it took 0.025 seconds for the sound to bounce back, the distance between the ultrasonic sensor and the box would be:

D = 0.5 x 0.025 x 343

A direct current (DC) motor is a type of electric device that converts electrical energy into mechanical energy. Electric power is converted into mechanical rotation by direct current (DC) motors. DC motors rotate a rotor within the output shaft with the aid of magnetic fields created by electrical currents. The output torque and speed are influenced by both the electrical input and the motor's design.

## Task

Below is a water tank that has two DC motors where the motor one is used to pump the water into the tank the motor two is used to suck the water out from the water tank and there are three sensors that are used to measure the water level of the tank. The operations of the two DC motors according to the switch state is given in a table right after the diagram.

## Operation Table
![Capture](https://user-images.githubusercontent.com/111219871/185356673-943aef1f-9775-41d0-b384-61db702a1efb.PNG)

## Breadboard Implementation
![01](https://user-images.githubusercontent.com/111219871/185334762-2fb08e60-d8ee-4bcd-a9d3-85a43d0aba9c.jpg)
![02](https://user-images.githubusercontent.com/111219871/185334767-5117ad83-274a-489f-862d-53bd5d0eaf78.jpg)
![03](https://user-images.githubusercontent.com/111219871/185334769-bfba5dab-acf0-485b-b91a-6444e325e8a8.jpg)
![04](https://user-images.githubusercontent.com/111219871/185334772-055d599b-9307-4387-a9e2-d940a328ab6b.jpg)

## The PCB design
![Screenshot (232)](https://user-images.githubusercontent.com/111219871/185356111-97bdfc35-097c-4d0d-8707-88224288a22a.png)
![Screenshot (233)](https://user-images.githubusercontent.com/111219871/185356123-1c5053da-e1ce-497e-aef9-9eabf09943e4.png)
![Screenshot (234)](https://user-images.githubusercontent.com/111219871/185356125-59298d4f-910d-4921-8f90-af7740fb6e77.png)
![21](https://user-images.githubusercontent.com/111219871/185335136-ab46e476-7b1f-43eb-b671-267df63eb36e.jpg)
![22](https://user-images.githubusercontent.com/111219871/185335149-5a2ce07a-ceff-42fe-a1d1-109b5cf7b150.jpg)
![23](https://user-images.githubusercontent.com/111219871/185335153-bc4b9b47-6f2a-4c85-8504-4ba2b999c027.jpg)
![20220720_190551](https://user-images.githubusercontent.com/111219871/185336069-d2c9f940-5771-4b92-859b-b936fd3ace09.jpg)

## An Images of the real implementation
![Screenshot (192)](https://user-images.githubusercontent.com/111219871/185343895-b89c7250-3784-4378-8e7f-17fc18916a26.png)
![41](https://user-images.githubusercontent.com/111219871/185343954-e5dbf605-1742-4069-b57c-8a934c4e805d.png)
Case 1- Motor1 is turned on
![42](https://user-images.githubusercontent.com/111219871/185343965-3175a393-9792-4bb7-b5a5-2c7618bfac54.png)
Case 2- Motor1 is turned on
![Screenshot (231)](https://user-images.githubusercontent.com/111219871/185345220-73de7905-bf20-4dfa-a2f8-d8105275125d.png)
Case 3- Motor2 is turned on

## Code

    //PIC16F877A Configuration Bit Settings
    //'C' source line config statements
    //CONFIG 
    #pragma config FOSC = HS // Oscillator Selection bits (HS oscillator) 
    #pragma config WDTE = OFF // Watchdog Timer Enable bit (WDTdisabled) 
    #pragma config PWRTE = ON // Power-up Timer Enable bit (PWRT enabled) 
    #pragma config BOREN = ON // Brown-out Reset Enable bit (BOR enabled) 
    #pragma config LVP = OFF // Low-Voltage (Single-Supply) In-Circuit Serial Programming Enable bit (RB3 is digital I/O, HV on MCLR must be used for programming) 
    #pragma config CPD = OFF // Data EEPROM Memory Code Protection bit (Data EEPROM code protection off) 
    #pragma config WRT = OFF // Flash Program Memory Write Enable bits (Write protection off; all program memory may be written to by EECON control)
    #pragma config CP = OFF // Flash Program Memory Code Protection bit (Code protection off)
    // #pragma config statements should precede project file includes. 
    //Use project enums instead of \#define for ON and OFF.

    #include <xc.h> 
    #define _XTAL_FREQ 20000000 
    #define ECHO RB0
    #define TRIG RB1 
    #define MOTOR1 RC3 
    #define MOTOR2 RC5

    //TIMER INTERRUPT
    void __interrupt() timer_isr(void){ 
    if(TMR1IF==1){
    MOTOR1 = 0; 
    MOTOR2 = 1; 
    __delay_ms(500); 
    MOTOR2= 0; 
    TMR1IF = 0;
    } 
    }

    void main(void){

    //initializing input output pins 
    TRISB0= 1; //ECO PIN
    TRISB1= 0; //TRIGGER PIN 
    //TRISB2= 1; //ECO PIN 
    TRISC3= 0; //BLUE LED-MOTOR1 
    TRISC5= 0; //RED LED- MOTOR 2 

    //T1C0N REGISTER 
    T1CON = 0X20; //1:4 PRESCALAR WITH INTERNAL CLOCK 

    //INTCON REGISTER 
    GIE = 1; //GLOBAL INTERRUPTS ENABLED 
    PEIE= 1; //PHERIPHERAL INTERRUPT ENABLED 

    //PIR1 REGISTER 
    TMR1IF = 0; //NO OVERFLOW 

    //PIE REGISTER 
    TMR1IE = 1; //TIMER1 INTERRUPT ENABLED

    MOTOR1 = 0;
    MOTOR2 = 0;

    int distance;
    int time_taken;

    while(1){
        
        TMR1H= 0;
        TMR1L= 0;
        
        //INITIALIZING US SENSOR
        TRIG = 1;
        __delay_ms(10);
        TRIG = 0;
        
        while(ECHO==0);
        TMR1ON= 1;
        while(ECHO==1);
        TMR1ON= 0;
        
        time_taken= (TMR1L | (TMR1H<<8));
        distance= (0.0272*time_taken)/2;
        
        //time_taken= time_taken*0.8;
        //INITIALIZING FUNCTION OF SENSOR1
        if(distance<10){
            MOTOR1= 1;
            MOTOR2= 0;
        }else{
            MOTOR1= 0;
            MOTOR2= 0;
        }
        //INITIALIZING FUNCTION OF SENSOR2
        if(10<=distance && distance<20){
            MOTOR1= 1;
            MOTOR2= 0;
        }else{
            MOTOR1= 0;
            MOTOR2= 0;
        }
        //INITIALIZING FUNCTION OF SENSOR3
        if(20<=distance && distance<30){
            TMR1IF=1;
        }
        
    }

    return;

}

## Results

According to the above code, distance between the untrasonic sensor and a object will be calculated. MOTOR1 will turn on if the calculated distance is less than 10 centimeters. MOTOR1 will also turn on if the calculated distance is between 10 and 20 centimeters. If the calculated distance is between 20 and 30 centimeters, timer1 interrupt flag will be logic high. Then, Moto1 will ther off and Motor2 will turn on for 500 miliseconds and then turn off. Since within 20 to 30cm range timer1flag is hogic high, between that range motor2 can be observed as constently turned on. 

## Discussion

During this project We faced a lot of difficulties while doing this project. Especially the PCB design did not work at the end. The PCB we used here was made by ourselves spending only three days. We did not make it by giving it to a separate company, even though we tried several times. Through this activity, it was possible to find a solution to a problem in the practical world using a pic microcontroller, and since this project is a group project, it was also possible to develop unity and harmony among each other.
In this project, we have learnt lots to program and simulate and this was a good platform to obtain the knowledge on how too attend into a proper project and how to make a documentary with this report. In future studies, it will help to do more complicated projects.

## References

- Ajer.org. 2022. [online] Available at: \<http://www.ajer.org/papers/v4(07)/L047088092.pdf\> [Accessed 20 July 2022].
- LiveTechIndia. 2022. _Water Level Indicator using Micro-Controller PIC16F877A | Livewire_. [online] Available at: \<https://livetechindia.com/water-level-indicator-   using-micro-controller-pic16f877a/\> [Accessed 20 July 2022].
- Myint1, K. and Tun2, M., 2022. _PIC MICROCONTROLLER BASED AUTOMATED WATER LEVEL CONTROL SYSTEM_. [online] Zenodo. Available at: \<https://zenodo.org/record/3352817\>   [Accessed 20 July 2022].

- 2022. [online] Available at <https://www.researchgate.net/publication/335210568\_PIC\_Microcontroller\_
  Based\_Water\_level\_Monitoring\_and\_Controlling\_System\_using\_Sharp\_Infra-   red\_range\_sensor\> [Accessed 20 July 2022].
- George, L. and George, L., 2022. _Water Level Indicator Controller Using PIC Microcontroller_. 
  [online] electroSome. Available at: \<https://electrosome.com/water-level-indicator-controller-pic/\> [Accessed 20 July 2022].
