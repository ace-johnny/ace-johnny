# [Johnny "Ace" Anderson](http://www.people.vcu.edu/~jranderson/)

I grew up learning to code on a variety of classic 8-bit microcomputers, including the venerable Apple II and Commodore 64. Over the ensuing years, however, my interest in programming sadly waned as my available discretionary time diminished, and the sedimentary layers of abstracted software complexity piled ever and ever higher.

In an effort to rediscover the joys of my early explorations in electronic logic, I have turned my attention lately toward learning the Arduino ecosystem of embedded development. Succesfully overcoming the severe constraints of confined memory and limited CPU cycles seems a far more satisfying mental challenge than studying yet another upstart flavor-of-the-month framework.

## Baby's First µController

Rather than start predictably with the ubiquitous but bulky Arduino Uno and its painfully basic IDE, I've decided to bootstrap my beginner's knowledge base by instead learning the slightly more sophisticated [Sparkfun Pro Micro](https://github.com/sparkfun/Pro_Micro), along with [Visual Studio Code](https://github.com/microsoft/vscode) and [PlatformIO](https://github.com/platformio/platformio-vscode-ide) as my development toolchain.

- Sparkfun's **Pro Micro** hosts an ATmega32U4 µC, which offers several advantages over the Uno's older ATmega328P, most notably a built-in USB transceiver and native HID capabilities. This wide DIP dev board also shares a common form factor with a selection of varying compact µControllers.

- **VS Code** offers exceptional editing features and an extremely flexible configuration, putting it *streets ahead* of Arduino's primitive IDE. It features stellar syntax highlighting, smart code completion, convenient GitHub integration, and powerful extensions providing support for a variety of languages.

- **PlatformIO** expertly manages disparate source code repositories and asundry platform build targets while avoiding proprietary dependencies. This toolchain enables the easy reuse of both local and remote code, library management, and common build configurations across a wide array of embedded ecosystems.

Each of these tools is entirely open source and should be interchangeable with compatible replacements, making it trivial to experiment with alternate µController hardware using various development software on any common operating system.

## Learning Goals

- Interface with buttons, potentiometers, and rotary encoders.
- Illuminate and animate addressable LEDs using the FastLED library.
- Analyze microphone audio using MSGEQ7 IC and FFT/FHT algorithms.
- Emulate HID devices including keyboards, mice, joysticks, and MIDI controllers. Create a new lighting category HID device? 

## Project Ideas

I'm interested in computer Human Interface Design, and creating unique custom hardware control surfaces.

- **Create a compact media control surface**, with a hybrid joystick / jog wheel, MIDI faders, encoder dials, potentiometer knobs, and neopixel / OLED displays. Maybe separate devices?

    - Battery powered and rechargeable via USB C. Use individual cells or lipo pouches? Use USB PD to quick charge when available.

    - Connects wirelessly via NRF24 framework and accommodates multiple devices. Use this [32u4 nrf24 board](https://www.aliexpress.com/item/4000484453013.html) for hardwired base station, which mimics Logitech's Unifying receiver.

    - Should the hybrid jog wheel joystick be digital (4 directions), or analog (2-axis variable)? Are there low-profile analog joysticks to minimize the assembly's height?

    - What size LED ring to use for main jog wheel? For utility encoders? 4 / 8 / 12 / 16? Need to drill out center hole in 4px board to fit encoder shaft?

    - Which protocols to support? MIDI? OCS? Mackie Control? Others?
