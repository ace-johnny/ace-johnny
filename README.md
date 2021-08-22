# [Johnny "Ace" Anderson](https://www.people.vcu.edu/~jranderson/)

I grew up learning to code on a variety of classic 8-bit microcomputers, including the venerable Apple II and Commodore 64. Over the ensuing years, however, my interest in programming sadly waned as my available discretionary time diminished, and the sedimentary layers of abstracted software complexity piled ever and ever higher.

In an effort to rediscover the joys of my adolescent explorations in electronic logic, I turned my attention toward learning the [Arduino](https://github.com/arduino/Arduino) ecosystem of embedded development. Successfully overcoming the severe constraints of confined memory and limited CPU cycles seemed a far more satisfying mental challenge than studying yet another upstart flavor-of-the-month framework.

## Baby's First µController

![Apple II to Arduino](/assets/pro_micro-banner.png)

Rather than begin predictably with the ubiquitous but bulky Arduino Uno and its painfully basic IDE, I decided instead to start with the slightly more sophisticated [Sparkfun Pro Micro](https://github.com/sparkfun/Pro_Micro) as my introductory µC of study, along with [Visual Studio Code](https://github.com/microsoft/vscode) and [PlatformIO](https://github.com/platformio/platformio-core) as my development environment and build toolchain.

- Sparkfun's **Pro Micro** hosts an `ATmega32U4` µC, which offers several advantages over the **Uno**'s `ATmega328P`, most notably a built-in USB transceiver and native HID capabilities. This diminutive dev board also shares its wide pitch DIP form factor with a large selection of other various µCs.

- **VS Code**'s flexible configuration and editing features put it *streets ahead* of Arduino's primitive IDE, with syntax highlighting, smart code completion, convenient GitHub integration, advanced debugging, and endless extensions providing support for seemingly every language available.

- **PlatformIO** expertly manages disparate source code repositories and sundry platform build targets while avoiding any proprietary dependencies. This toolchain provides powerful library management, integration with several different IDEs, and builds targeting a wide array of µC ecosystems.

All of the above tools are open source and are interchangeable with compatible workalikes, simplifying experimentation with different µC architectures using a variety of development environments on myriad modern operating systems.

## Learning Goals

Since my extant programming skills are still somewhat passable, I'm able to forgo the intermediate "for-next" student studies and focus on sharpening my c++ syntax.

- Interface with buttons, potentiometers, and rotary encoders.
- Use the [FastLED](https://github.com/FastLED/FastLED) library to illuminate addressable RGB pixels.
- Display UI using web browser and [p5.js](https://github.com/processing/p5.js) library to draw canvas.
- Display UI using OLED via I2C and SPI.
- Analyze live audio using a mic, FHT algorithm, and `MSGEQ7` IC.
- Emulate HID devices: keyboards, mice, gamepads, and MIDI.
- Script with [Bitlash](https://github.com/billroy/bitlash) serial command shell.

## Projects

Individual projects are housed in their respective repositories:

- **ace-johnny**: this profile readme, along with other documents and resources.

- **rotary_button-dev**: library development for a rotary encoder button, displays HSV color on 8b neopixel with `p5.js` web UI via serial.
