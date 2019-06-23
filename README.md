# grbl-0.8c-modified-inverse-dir-step

https://github.com/Protoneer/GRBL-Arduino-Library

     config.h change dir port with step port because in cnc shield is inversed

     #define X_STEP_BIT         2->5  // Uno Digital Pin 2
     #define Y_STEP_BIT         3->6  // Uno Digital Pin 3
     #define Z_STEP_BIT         4->7  // Uno Digital Pin 4
     #define X_DIRECTION_BIT    5->2  // Uno Digital Pin 5
     #define Y_DIRECTION_BIT    6->3  // Uno Digital Pin 6
     #define Z_DIRECTION_BIT    7->4  // Uno Digital Pin 7
