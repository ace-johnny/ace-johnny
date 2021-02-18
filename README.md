# Title Goes Here

I grew up learning to code on a variety of classic 8-bit microcomputers, such as the venerable Apple II and Commodore 64. Over the ensuing years, however, my interest in programming waned considerably as my available discretionary time diminished, and the sedimentary layers of abstracted software complexity piled ever and ever higher.

In an effort to rediscover the joyous roots of my early explorations in electronic artistry, I have turned my attention lately toward learning the Arduino ecosystem of bare-metal embedded development. Succesfully overcoming the severe constraints of confined memory and limited CPU cycles seems a far more satisfying mental challenge than studying yet another flavor-of-the-month framework's syntax.

## Baby's First µController

Rather than start predictably with the ubiquitous Arduino Uno and its basic IDE, I decided to bootstrap my beginning knowledge base using the slightly more sophisticated [Sparkfun Pro Micro](https://github.com/sparkfun/Pro_Micro), along with [Visual Studio Code](https://github.com/microsoft/vscode) and [PlatformIO](https://github.com/platformio/platformio-vscode-ide) as my development toolchain.

- The **Pro Micro**'s ATMega32U4 offers several advantages over the Uno's ATMega328P, most notably its built-in USB transceiver and HID capabilities. Its compact DIP form factor is also ideal for prototyping, and inexpensive clones are widely available thanks to its open-source design.

- **VS Code**'s excellent editing features and flexible configuration are *streets ahead* of Arduino's primitive IDE, offering stellar code completion and syntax highlighting, convenient Git and GitHub integration, and powerful extensibility supporting a wide array of languages.

- **PlatformIO** competently manages disparate source code repositories and various platform build targets while avoiding any system software dependencies or vendor lock-in.
