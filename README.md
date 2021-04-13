# openinput-hw (to be renamed)

[<img src="assets/logo.svg" alt="" width="20%" align="right">](https://github.com/openinput-fw)

Open source firmware for input devices.

## Specifications
- 8 kHz sampling rate support
- Zero latency switch debounce
- Onboard configuration memory
- 2 main mouse buttons (satellite* configuration for both)
- 2 side buttons (symmetric to allow easy left/right handedness)
- encoder + wheel button (satellite* configuration)

`*meaning, a separate board from the core with the controller and sensor`

## Hardware

- ATSAMS70 MCU (ATSAMS70JxxB-M)
- PMW3360 Optical sensor
- onboard conectors:
    - JST PH (2mm pitch) for USB
    - JST SH (1mm pitch) for stellite boards
- M2 mounting hardware

|USB pinout||
|-----|-----|
|1|VCC|
|2|DM|
|3|DP|
|4|GND|
|5|Shield|

## License

This hardware is licensed under the [CERN-OHL-P v2](LICENSE) license.