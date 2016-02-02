# drone-build

Build Documents for a Drone

## Phases

1) Sensors - Everything here should be testable with just RPi GPIO
  * Gyroscope
  * Accelerometer
  * Radio
  * camera (maybe v2)
  
2) Motors - require an additional power source
  * Propellers
  * Servo

3) Controller - Should signal to radio on RPi. doesn't need a real case at first
  * TODO: what controls do we need?
  * NOTE: stop gap - MAcbook
  * Use an old dual-shock?
  
4) Flight control board - Arduino?

5) Drone Body - Need tools/Maching/3d Printer
