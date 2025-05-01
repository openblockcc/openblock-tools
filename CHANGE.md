# Changelog

## v2.9.0

1. Add ArduinoGraphics library.

## v2.8.0

1. Upgrade arduino:avr v1.8.5 -> v1.8.6
2. Upgrade rp2040:rp2040 v2.6.0 -> v4.4.4
3. Upgrade esp32:esp32 v1.0.6 -> v3.1.3
4. Add arduino:renesas_uno
5. Modify the configuration to prevent arduino-cli from checking for updates on startup

## v2.7.0

1. Update arduino-cli v0.27.1 -> v0.35.3

## v2.6.0

1. Add support for linux x86/x32.
2. Update arduino libraries Servo 1.1.6 -> 1.1.8
3. Update arduino rp2040:rp2040 2.5.4 -> 2.6.0

## v2.5.0

1. Add new arduino board: Raspberry Pi Pico
2. Add new arduino libraries: SimpleList, avr-stl
3. Update arduino-cli v0.21.1 -> v0.27.1.

## v2.4.0

1. Fix the python call problem under mac.
1. Update the version of openblock-obmpy.

## v2.3.3

1. Add arduino k210 servo library.
2. Update the version of openblock-obmpy.

## v2.3.2

1. Update the version of openblock-obmpy to support set rts and dtr flow control.

## v2.3.1

1. Update the version of arduino-cli
2. Update the version of arduino:avr
3. Update the version of esp8266:esp8266, to fix the error log: `Error initializing instance: loading platform release esp8266:esp8266@3.0.0: loading boards: skipping loading of boards esp8266:esp8266:espduino: malformed custom board options`

## v2.3.0

1. Add openblock-obmpy to support standard micro python.
2. Add esptool to support micro python esp32.
3. Add kflash to support micro python k210.
4. Update uflash to support microbit v2.

## v2.2.0

Add arduino esp8266 support.

## v2.1.0

Add arduino esp32 support.

## v2.0.0

change arduino-builder to arduino-cli.

## v1.2.0

Add arch parameter.

## v1.1.0

**Tool list**

- Arduino

	Support all basic avr arduino board.

- Python3.9.2 (32-bit)

	With uflash and microfs inside, for microbit.

**Support system**

- Windows x86/x64

## v1.0.0

**Tool list**

- Arduino

	Support all basic avr arduino board.

- python-uflash

	For microbit.

**Support system**

- windows
