MPL115A2-Library
================

MPL115A2 I2C DIGITAL BAROMETER
 - This is a sample code for MPL115A2 Barometer 
   utilizing MPL115A2.h library.
 - The output of this IC are Pressure(in kPa)
   and Temperature(in Celsius).
  

MPL115A2 Functions:
   - readBoth(&P, &T)   - Simultaneously read pressure(P)
                       and temperature(T) from the chip.
   - readPressure()     - returns the pressure reading from the chip.
   - readTemperature()  - returns the temperature reading from the chip.
   - *Both returned values are floating points.
    

Wiring Connection:

   MPL115A2 BREAKOUT BOARD	GIZDUINO          
        - VCC      <------------> VCC                  
        - GND      <------------> GND                  
        - CS/RESET <------------> A2                   
        - SHDN     <------------> A3                   
        - DIN/SDA  <------------> A4 <--- 4.7Kohms ---> VCC
        
        - SCLK/SCL <------------> A5 <--- 4.7Kohms ---> VCC  
 
 -Created On: 23 Apr 2014
        - By: e-Gizmo Mechatronix Central
        - http://www.e-gizmo.com

Note: Rename the folder to "MPL115A2", then place it on the Arduino>libraries.
