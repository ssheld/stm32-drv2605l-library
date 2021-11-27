<h1> STM32 Library for DRV2605L  </h1>

STM32 library for using the DRV2605L haptic motor driver.



***Repository Contents***
---
- **/drv2605l_example** - Example program utilizing DRV2605L library.
- **/DRV2605L** - DRV2605L library.
- **/datasheets** - Datasheets for all hardware utilizes in the example program.
- **drv2605l tutorial.pdf/.docx** - Tutorial on how to setup hardware and library.

***Caveats***
---
This library currently does not implement the PWM functionality of the DRV2605L. It currently uses the TouchSense2200 waveform library in the DRV2605L's ROM.
