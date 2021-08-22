# Project Ideas

I'm interested in human/computer user interface design, and creating custom hardware control surfaces. I'm also interested in designing and creating custom RGB art lamps that are controlled via mobile app, and the design and coding of those user interfaces too.

- **Create shadow box art lamps:** desktop and wall-mounted LED-illuminated shadow boxes.

    - Kirigami: NeoGeo Zero. Back and front lit geometric kirigami in a dimensional frame, with backside illumination, motion and brightness detection, and mobile control.

    - Calvin & Hobbes: Universe. Nightstand design with backside illumination, motion and brightness detection, and mobile control. Monitoring options?

- **Create media control surfaces:** with hybrid jogstick, MIDI faders, encoder dials, potentiometer knobs, macropad keys, neopixels, and OLED displays. Separate modular devices.

    - Hybrid Jogstick: combines rotary encoder button with joystick

        - Should the joystick be digital (4 directional switches), or analog (2 variable potentiometers)?

        - How to handle two stacked button switches (joystick button and rotary button)?

        - Knob size? LED ring 8/12/16?

    - Battery powered and rechargeable via USB C, use PD to negotiate quick charge when available. Use individual cells or lipo pouches?

    - Separate devices connect via NRF24 framework. This [32U4 NRF24](https://www.aliexpress.com/item/4000484453013.html) board or equivalent could mimic Logitech's Unifying receiver.

    - Which protocols to support? MIDI? OCS? Mackie Control? HID Lighting?

- **Use ATtiny85 as I2C interface** for individual UI controls, up to 4ch. how many analog? available features on remaining pins? IO expansion? Better µC than ATtiny85 for controller?

- **Use ATtiny85 double buffered** with 128x32 I2C OLED.
