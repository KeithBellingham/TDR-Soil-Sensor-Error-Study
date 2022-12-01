# TDR-Soil-Sensor-Error-Study
A validation of accuracy claims made in sales literature
## Prepared by B. Keith Bellingham, <br />
Soil Scientist, <br />
September 20, 2022<br/>
https://www.linkedin.com/in/bkbellingham/

**Introduction**

Time domain reflectometry (TDR) is commonly used for the determination of the volumetric soil water 
content. Monitoring soil moisture is increasingly becoming more important for irrigation, 
flood and drought risk, water resources, and climate change assessments. TDR is based on the principle
that the velocity of an electrical pulse will slow down in the soil as the soil gets wetter. The 
travel time of the electrical pulse, T, is directly corelated to the parameter called the apparent dielectric permittivity, $K_a$ (sometimes called the relative dielectric permittivity). Knowing the time of travel of the pulse, the $K_a$ of the soil can be determined by;


$$K_a = (cT/2L)^2$$

Where c is the speed of light, and L is the path length of the waveguide. The waveguide is metal part of the sensor that is in the soil through which the electrical pulse travels before reflecting back to the sensor head. 

The Topp Equation, is commonly used as the soil moisture calibration for TDRs by using  the $K_a$ value to estimate soil water content; 

$$\theta = a + bK_a + cK_a^2 + dK_a^3$$

Where a, b, c, and d, are empirical coefficients and $\theta$, is soil moisture. 

Soil salinity is often represented by the bulk electrical conductivity (EC) and is important for assessing seawater intrusion and poor drainage in soils. EC is measured by TDR using the impedance or shrinkage of the reflected electrical pulse. The unit for EC is micro-Siemens per cm ($\mu S/cm$)

Many soil moisture sensors on the market make claims about accuracy and repeatability and it is difficult for most end users to validate such claims. In this study, ten True TDR sensors were tested in controlled conditions against NIST traceable standards in an attempt to reproduce the accuracy claims in the sales literature for the parameters of EC, $K_a$ and $\theta$. 
