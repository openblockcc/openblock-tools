# Changelog

## v2.3.3

1. Add arduino k210 servo library.
2. Update the version of openblock-obmpy.

**Tool list**

- Arduino CLI v0.21.1

    Supported boards:

    | ID              | Version | Name                |
    | --------------- | ------- | ------------------- |
    | arduino:avr     | 1.8.5   | Arduino AVR Boards  |
    | esp32:esp32     | 1.0.6   | esp32               |
    | esp8266:esp8266 | 3.0.2   | esp8266             |
    | Maixduino:k210  | 0.3.11  | Maixduino(k210)     |
    | SparkFun:avr    | 1.1.13  | SparkFun AVR Boards |

    Preinstalled Libraries:

    | Name       | Version |
    | ---------- | ------- |
    | Servo      | 1.1.6   |
    | ServoESP32 | 1.0.3   |
    | ServoK210  | 1.0.0   |

- Python

    Packages:

    | Name            | Version |
    | --------------- | ------- |
    | uflash          | 2.0.0   |
    | microfs         | 1.4.5   |
    | esptool         | 3.3     |
    | kflash          | 1.0.2   |
    | openblock-obmpy | 1.1.6   |

## v2.3.2

1. Update the version of openblock-obmpy to support set rts and dtr flow control.

**Tool list**

- Arduino CLI v0.21.1

    Supported boards:

    | ID              | Version | Name                |
    | --------------- | ------- | ------------------- |
    | arduino:avr     | 1.8.5   | Arduino AVR Boards  |
    | esp32:esp32     | 1.0.6   | esp32               |
    | esp8266:esp8266 | 3.0.2   | esp8266             |
    | Maixduino:k210  | 0.3.11  | Maixduino(k210)     |
    | SparkFun:avr    | 1.1.13  | SparkFun AVR Boards |

- Python

    Packages:

    | Name            | Version |
    | --------------- | ------- |
    | uflash          | 2.0.0   |
    | microfs         | 1.4.5   |
    | esptool         | 3.3     |
    | kflash          | 1.0.2   |
    | openblock-obmpy | 1.1.4   |

**Support system**

- Windows x86/x64
- macOS x64

## v2.3.1

1. Update the version of arduino-cli
2. Update the version of arduino:avr
3. Update the version of esp8266:esp8266, to fix the error log: `Error initializing instance: loading platform release esp8266:esp8266@3.0.0: loading boards: skipping loading of boards esp8266:esp8266:espduino: malformed custom board options`

**Tool list**

- Arduino CLI v0.21.1

    Supported boards:

    | ID              | Version | Name                |
    | --------------- | ------- | ------------------- |
    | arduino:avr     | 1.8.5   | Arduino AVR Boards  |
    | esp32:esp32     | 1.0.6   | esp32               |
    | esp8266:esp8266 | 3.0.2   | esp8266             |
    | Maixduino:k210  | 0.3.11  | Maixduino(k210)     |
    | SparkFun:avr    | 1.1.13  | SparkFun AVR Boards |

- Python

    Packages:

    | Name            | Version |
    | --------------- | ------- |
    | uflash          | 2.0.0   |
    | microfs         | 1.4.5   |
    | esptool         | 3.3     |
    | kflash          | 1.0.2   |
    | openblock-obmpy | 1.1.3   |

**Support system**

- Windows x86/x64
- macOS x64

## v2.3.0

1. Add openblock-obmpy to support standard micro python.
2. Add esptool to support micro python esp32.
3. Add kflash to support micro python k210.
4. Update uflash to support microbit v2.

**Tool list**

- Arduino CLI v0.21.1

    Supported boards:

    1. arduino:avr
    2. esp32:esp32
    3. esp8266:esp8266
    4. SparkFun:avr
    5. Maixduino:k210

- Python

    Packages:

    1. uflash v2.0.0
    2. microfs v1.4.5
    3. esptool v3.3
    4. kflash v1.0.2
    5. openblock-obmpy v1.1.3

**Support system**

- Windows x86/x64
- macOS x64

## v2.2.0

Add arduino esp8266 support.

**Tool list**

- Arduino

    arduino:avr

    esp32:esp32

    esp8266:esp8266

    SparkFun:avr

- Python

    With uflash and microfs inside, for microbit.

**Support system**

- Windows x86/x64
- macOS x64

## v2.1.0

Add arduino esp32 support.

**Tool list**

- Arduino

    Support all basic avr arduino board.

    Support esp32.

- Python

    With uflash and microfs inside, for microbit.

**Support system**

- Windows x86/x64
- macOS x64

## v2.0.0

change arduino-builder to arduino-cli.

**Tool list**

- Arduino

    Support all basic avr arduino board.

- Python

    With uflash and microfs inside, for microbit.

**Support system**

- Windows x86/x64
- macOS x64

## v1.2.0

Add arch parameter.

- **Tool list**

    - Arduino

        Support all basic avr arduino board.

    - Python

        With uflash and microfs inside, for microbit.
    
- **Support system**

    - Windows x86/x64
    - macOS x64

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
