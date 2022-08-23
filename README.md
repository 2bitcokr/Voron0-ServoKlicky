# Voron0-ServoKlicky
Voron0-ServoKlicky


https://user-images.githubusercontent.com/110684743/186092694-69971830-356e-452b-9cc5-ffa57690e5ff.mp4

Vzero Servo Klicky

Klicky BASE is https://github.com/jlas1/Klicky-Probe/tree/main/Klipper_macros

You must use ServoKlicky to use all Printing Range.

NEED PARTS 

MG90S servo motor 

M3-12 Bolt * 2ea

M3 Hex Nuts * 2ea


+ KlickyProbe Magnetic 6*3 9ea
+ 
+ Micro Switch ( D2f or KW10 )




# Menual
https://github.com/jlas1/Klicky-Probe/tree/main/Klipper_macros
This is Klicky Menual.

First! Config Klicky setting... 

servosetting is

Printer.CFG file

[servo klicky_servo]

pin: PA1 #Servo PIN!

maximum_servo_angle: 180 #dont change

minimum_pulse_width: 0.00025

maximum_pulse_width: 0.0024


before assembly

insert a magnet in probe,dock.

connect the servo Cable (real)

SET_SERVO SERVO=klicky_servo ANGLE=160

disconnect the servo Cable

Do not touch the servo gear!!

![Klicky_ass](https://user-images.githubusercontent.com/110684743/186160759-9de3d2d4-dca1-446b-bacb-059d83c08979.gif)
![ezgif com-gif-maker](https://user-images.githubusercontent.com/110684743/186160766-66a9ba80-ced1-4bd6-910d-0ca505e60034.gif)

![cc](https://user-images.githubusercontent.com/110684743/186163077-cba91136-bfc4-4bc8-b050-27971508fa8c.png)

![hori](https://user-images.githubusercontent.com/110684743/186164428-f883e439-6ace-49fd-8ebd-16d82098518e.png)

Horizontal adjusts the servo angle.

(SET_SERVO SERVO=klicky_servo ANGLE=160)

Also check the folding angle (maybe -90 degree)

The height and angle are  little changed by the magnet.

Need test docking, undocking

