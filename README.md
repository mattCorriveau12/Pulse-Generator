# Pulse-Generator
The purpose of this project was to create a fast-edge pulse generator with a sub-nano-second rise time. This pulse generator can be used for applications including testing Oscilloscope or Oscilloscope Probe Bandwidth, and TDR (Time Domain Reflectometry) Testing of signal reflections for determining cable lengths.

This project is a work in progress.

Schmitt Inverter Pulse Generator - Breadboard Circuit Complete / Tested

    I have parts on order to try swapping in a couple of different part numbers to see if I can improve the edge transition times. TI CD74AC14E & Nexperia 74LVC14APW.

Transistor Avalanche Pulse Generator - Breadboard Circuit Complete / Tested

    I may build this circuit up on Solderable Protoboard to try to further improve the rise time by decreasing circuit capacitance.

    I have parts on order to try swapping in a couple of different part numbers to see if I can improve the edge transition times. Microchip 2N2369A & Central Semi 2N2369A

Analog Devices LTC6905 Oscillator Pulse Generator

    Datasheet specifies Rise Times of 500ps. I will build this part up on protoboard to see what I can produce for edge transition times.




At some point, I plan to hack my Siglent SDS1104X-E Oscilloscope to unlock the software limited maximum bandwidth and see if that improves my edge transitions for each of the above circuits.
