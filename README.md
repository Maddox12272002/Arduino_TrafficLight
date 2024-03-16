# Arduino_TrafficLight
This is an Arduino activity where:

Exercise 2.1: Use Potentiometer to Control timing of Traffic Light

•	For the traffic light system, add a potentiometer to control the timing of the signals.
•	You need to set the timing for the green and red signals to be proportional to the analog input value. For example, if the analog input is 100, set the duration of each of the red and green signals to 1 second. If the analog input is 500, set the red and green signal durations to 5 second, and so on. The yellow signal will always have a constant duration of 1 second.
•	You will still need to provide the override feature as using the pushbutton for control which can control which signal will turn ON.

Exercise 2.2: Modify Traffic Light Operation at Night

•	For the traffic light circuit, you built in Exercise 1.1, add a light sensor (LDR) that will be used for controlling the operating mode of the traffic light signals.
•	First “calibrate” the light sensor by taking several sensor measurements under varying lighting intensities.
•	Find a “threshold” value that splits the light intensity measurements into two, “dark” readings and “light” readings.
•	Implement an Arduino program that controls the operation of the traffic signal as follows:
–	During the daytime, the traffic signal operates in the “normal” operation mode; i.e., “green” (for 4 seconds), “yellow” (for 1 seconds), then “red” (for 4 seconds).
–	During the nighttime, the traffic signal only flashes the “red” light every one second; i.e., one second on and one second off.

Exercise 2.3: Smart Street Light

•	Use a bright “white” LED to emulate a street light.
•	Make the streetlight ‘smart’ by using a light sensor as feedback.
•	Control the ‘smart’ streetlight in such a way that the brightness of the streetlight is adjusted based on the measurements from the sensor readings.
Therefore, during the day the smart streetlight is completely off.
As the sun goes down, the smart streetlight gradually turns itself on at intensity levels that are appropriate to give sufficient lighting to the environment. When it is completely dark, the ‘smart’ street light gives off its brightest light.

