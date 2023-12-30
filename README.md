# EurorackPower

A submodule PCB for prototyping Eurorack modules. This PCB encapsulates the circuit often used in Eurorack modules for reverse polarity protection and ripple filtering. This PCB can be mounted onto another PCB or onto a breadboard. 

To mount the EurorackPower submodule on a breadboard, you can do one of two things:

1. Only use the pairs of pins on the left side of the board to connect to the power rails of the breadboard. This is a flimsy solution, but it can work.
2. Only solder two of the three pins in the top right and bottom right corners, making them match the pins on the left side. This allows you to connect the EurorackPower submodule to the power rails of the breadboard with all four sets of pins making it much more stable.

```
Q. Why are there three pins on the right corners at all? 
A. Providing +12v, ground and -12v at both corners
   makes it easier to develop PCBs
   to which this submodule would provide power.
```

The PCB conforms to an as-yet-unnamed system of submodules I am developing to make prototyping a little bit easier and more modular. Yeah, modular in your modular.

When soldering, please see the [interactive BOM](https://octovolt.github.io/EurorackPower/).

![3DView-1](https://github.com/octovolt/EurorackPower/assets/78008936/263a8b32-d329-48c6-ae07-ec33e4f2e552)

![3DView-2](https://github.com/octovolt/EurorackPower/assets/78008936/c26b12cf-3423-4331-9c7e-328290b34d80)
