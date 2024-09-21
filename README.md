# rack_piHAT
Raspberry Pi HAT (Hardware Attached on Top) featuring a few components for use in my home lab/Pi rack

# Features
- Hardware RNG
  - uses an avalanche noise generator circuit
  - STM32F103x for random number generation using the avalanche circuit's noise
- Sensor bus with the following devices:
  - TMP36 temperature sensor (analog on board/chip)
  - MQ6 gas sensor
  - BME280 (I2C)
  - Some light sensor
- Fan control (analog)
- Something else?

## Hardware RNG using an avalanche noise generator.
The avalanche noise generator circuit consists of:
- 2x 4.7k resistors
- 1x 10k resistor
- 1x 1m resistor
- 3x 3904 NPN transistors
- 10uf capacitor
- 0.1uf capacitor

# Schematic

# Protoboard
*TODO:* **Attach picture**
