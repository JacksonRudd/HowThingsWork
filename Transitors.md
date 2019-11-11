# Differential Amplifier With Transistors

![image](https://sub.allaboutcircuits.com/images/quiz/03925x01.png)


A differential amplifier takes two small inputs, and finds the delta between them. This is a set up where $latex Vin(-)$ will move against the output and $latex Vin(+)$ will move with the output.  How does this work? 

Note that the voltage drop across $latex Re$ will never change by a significant amount. The voltage at the emitters of the transistors are roughly a voltage drop from the small inputs. Therefore the voltage before the resistors hovers within a few mV of 0.


Since the voltage drop does not change, there is a fixed amount of current that goes through the $latex Re$ resistor. Which must be a sum of the current that exits the emitters. Therefore the currents through the collectors must be inverse to each other. 



Now say that the current through $latex Vin(+)$ increases. The current through $latex Q2$ must fall. Therefore $latex Vout$ must fall, as the resistor above $latex Vout$ causes change in current to change with voltage. If $latex Vin(-)$ increases, then again, the resistor will cause $latex Vout$ to change as well. 
