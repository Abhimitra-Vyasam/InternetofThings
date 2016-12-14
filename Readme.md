Hardware:

Particle,
Arduino,
Servo Motors,
Line Follower,
Photo Resistor.

Explanation:

I have used line follower as a replacement for actual car and used whit sheet as a parking lot. 
When the line follower reaches its destination, a sinal is sent to stepper motor, and particle that the spot is filled up. 
stepper motor blocks the path and particle published information to IFTTT and an update is received.

Once the car leaves parking lot, a signal is sent to particle and IFTTT. AN update that parking lot is empty is received.
