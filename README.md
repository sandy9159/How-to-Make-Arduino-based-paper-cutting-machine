# How-to-Make-Arduino-based-paper-cutting-machine-

![image](https://user-images.githubusercontent.com/19898602/129760038-186abd8b-ff03-4f1e-aa4d-e358c5df0f6a.png)

Hello friends in this video I have made a paper cutting machine using arduino and some stepper motors and custom PCB.
I have used Two stepper motors one feeds the paper to the cutter and one stepper motor slides the blade to cut the paper.
User will enter data like how many strips need to cut and how long each strip would be, from the the 2.8" nextion HMI 

Sometimes, art projects can require the creation of many different pieces of material to be used in the construction of an item. Imagine wanting to build a mosaic out of construction paper but then realizing you’ll need hundreds of tiny strips that are each cut to the exact same length. 

I come up with a solution in the form of an Arduino-based paper cutter. This project follows from a recent one where he assembled an automatic wire cutting machine that can handle up to four different colors simultaneously. 

design consists of a large block of wood for the base with a pair of opposing, parallel rails on either side. 

Just beside one of these is a NEMA 17 stepper motor with a gear that meshes with and rotates a set of rubber rollers that span the entire width of the machine to feed paper through. At the end of the base is another rail 

that supports the cutting head (a razor blade) which is slid back and forth with another stepper motor. 



Both motors are driven by a custom control board that houses a pair of A4988 motor drivers and an Arduino Nano. 

An I2C-enabled screen sits at the front, and it displays a simple GUI with which the user can select both the length of each paper strip and how many should be cut.


# COMPONENT USED

> Some 3D printed parts

> Aluminium Rails T shape

> 12mm Wooden sheet

> 2 NEMA 17 Stepper motor

> 6MM SS smooth rod

> 9mm Raor blade

> Rubber roller from old printer

> Timming belt

> Idler pulley 

> 2.8" Nextion HMI

![image](https://user-images.githubusercontent.com/19898602/129761510-775b9946-3255-407e-ab40-01c3c8918d09.png)


First I prepare based for this machine from 12mm wooden sheet

I cut it in 200 x 350 size.

![image](https://user-images.githubusercontent.com/19898602/129761685-20c7de55-30d0-4c49-8cd9-e424487187e6.png)

I ued this type of 10mm U shape aluminium this is used as guuid for paper



![image](https://user-images.githubusercontent.com/19898602/129763213-555422e6-bebd-4974-9c64-b181a3281e27.png)

This are the Nema17 stepper motor I have used 2 of this type

One to feed paper to the blade, and one is to cut the paper.

Basically stepper motors are brushless DC motors, normally a permanent magnet rotor placed in between of stator winding.

Stator winding then energize step by step in a sequential way so it get magnetize and force rotor to align with the magnetic field of stator coil.

in this way rotor begin rotate in small steps, due to this behavior the motor gets its name “stepper motor”

As we can see now by controlling the stator winding generations sequence we can precisely control the position of rotor without any position feedback system.

this quality of stepper motor makes is best suitable to be used were high precision motion is required like CNC machines.




![image](https://user-images.githubusercontent.com/19898602/129763706-4aff0364-6079-411e-b36c-512594c6d832.png)


This is the rubber roller you can find this type off roller in any OLD printers.

Rubber mounted on the shaft is provide great grip with paper, this will make very easy to feed paper

at the on end of the roller's shaft I have attached a 3D printed gear, this gear get engage with the other

gear which is mounted on the shaft of nema 17 stepper motor.

This stepper motor runs the roller against the paper and paper feed to the cutting blade


![image](https://user-images.githubusercontent.com/19898602/129764325-111a154c-5734-42b0-88c0-475a255dc875.png)

This is the sliding mechanism for the blade


















