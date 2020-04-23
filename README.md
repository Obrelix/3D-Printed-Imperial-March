# 3D-Printed-Imperial-March 


 [![Watch the video](https://i.imgur.com/KWxv6zv.png)](https://youtu.be/fOcZKwsDDqY)
 

The files of this project mainly work on 3d printers or any other computerized machine tool use the MARLIN frimware and :
1. Use 85 - 90 E-Steps for the X and the Y axis. (E3_Imperial_March.gcode)
2. Have a speaker or a buzzer instaled. (E3_Imperial_March_Buzzer.gcode)

The  [E3_Imperial_March.gcode](https://github.com/Obrelix/Ender-3-Imperial-March-/blob/master/GCODE%20Files/E3_Imperial_March.gcode)
 file uses the  **G1** command that adds a linear move , with a specific rate,  to the queue to be performed after all previous moves are completed. By changing the rate and the position of the stepper motors produce frequencies for a certain period of time at specific times. [MARLIN Documentation G0-G1 Commands](https://marlinfw.org/docs/gcode/G000-G001.html)

The  [E3_Imperial_March_Buzzer.gcode](https://github.com/Obrelix/Ender-3-Imperial-March-/blob/master/GCODE%20Files/E3_Imperial_March_Buzzer.gcode) file uses the  **M300** command that add a tone to the tone queue and its requires **SPEAKER** to play tones (not just beeps). [MARLIN Documentation M300 Command](https://marlinfw.org/docs/gcode/M300.html)

