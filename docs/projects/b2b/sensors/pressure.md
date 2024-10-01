---
hide:
  - toc
---


# Plotting data using Pressure sensor

**The sensor used: BMP180 /  BMP280**


<img src="../images/bmp_pressure.png" alt="BMP180-P(Bar)" width="50%">


The KuttyPy+ takes in the sensor data from an I2C pressure sensor and plots it on
a time graph using the visual code. BMP180/280 is a pressure and temperature sensor.

**Activity**: The participants are asked to find the height of the lecture hall by
determining the pressure difference between the lecture hall and the adjacent floor.
Then convert the pressure difference into altitude difference, hence finding out the height of the hall.


<img src="../images/bmp180_visual.png" alt="BMP180-P(Bar) Output" width="50%">


<iframe width="100%" height="500" src="https://www.youtube.com/embed/3vEMoWWagR0?si=-GocmNqgMNXNpad3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


**Calculation:**

```text
Pressure difference = (Bottom Floor Pressure) - (Top Floor Pressure) 

                    = 1.0047 Bar - 1.0042 Bar
                    
                    = 0.5 milliBar

In air, a pressure difference of 1 milliBar accounts for an altitude difference of 8 meters.

ie. The height of the hall is = 0.5 x 8 = 4 meters.

```
 
