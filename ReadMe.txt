The following set of files contains the documentation of the prototype presented in the article "Quadcopter platform for control systems experimentation in teaching".


The documentation described below is intended to serve as a user guide for the replication and use of the platform. The following is a brief description of the contents of each folder:


-Folder "CAD Prototype": this folder contains the .cad files of design for each component of the prototype and its assembly. 

-Folder "3D Printing Parts": This folder contains the .cad and .stl files of the parts that are manufactured under 3D printing. 

-Folder "Numerical simulations": This folder contains the .slx files of simulations for the prototype model. In these simulations the state feedback controller and the PID controller shown in the article are implemented. 

-Folder "Experimental implementations": This folder contains the .slx files to carry out implementation of the control system in the prototype under approach of state feedback control and PID control shown in the article.


Additionally, below is a brief user manual for the use of the platform.

-Step 1. Configuration of simulink environment.
The configuration of settings in Matlab/Simulink is established to link the software with the PX4 microcontroller through external mode.

-Step 2. Simulink model creation. 
A block diagram is built in the Simulink software using Pixhawk block library. The adjustable variables to be used during application are defined in the software. 

-Step 3. Source code creation
The source code of the application just created by the block diagram is integrated into the PX4 firmware modules.

-Step 4. Firmware compilation
The updated firmware is compiled with the created Simulink application and loaded into the PX4 microcontroller.

-Step 5. Starting the application on the microcontroller
Run the compiled application on the PX4 microcontroller.

-Step 6. Power up the drone
The power supply is turned on and the quadcopter motors are energized.

-Step 7. Arm drone motors manually 
The quadcopter motors are manually armed by a physical switch. 

-Step 8. Starting the application in Simulink software
The application is started in Matlab/Simulink software and linked to the application running on the microcontroller.

-Step 9. Using the platform
At this point, the platform is ready to be used by means of the adjustable variables established in the block diagram design.


Finally, in the following URL it is possible to find a video of the prototype in operating.

https://www.youtube.com/watch?v=P1qK8tDe-CM&t=4s
