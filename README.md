# Solar-cell-characteristics-tracer
Circuit for tracing of the full I-V characteristic, measuring open circuit voltage and short circuit current of a low power solar cell.
Used to test the circuit architecture that will be implemented on the [6S CubeSat](https://polispace.it/6s-cubesat-project/).
- The circuit uses a voltage controlled current generator to trace the full I-V characteristic.
- Open circuit voltage is measure with a simple buffer.
- Short circuit current with a transimpedance amplifier.
- I2C controlled DAC is used to generate the voltage ramp needed to have a linearly increasing current from the solar cell

<img src="https://github.com/Luca452/Solar-cell-characteristics-tracer/assets/36864265/931d0478-209a-4c75-ab21-4d0cd4c60547" width="390" />

<img src="https://github.com/Luca452/Solar-cell-characteristics-tracer/assets/36864265/46387e22-8247-492c-8300-9cf237076fd4" width="1000" />

