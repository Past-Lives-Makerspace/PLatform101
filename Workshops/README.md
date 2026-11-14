# Workshops

The workshops are still a work-in-progress. These are my initial notes.

## Goals

The initial workshops have the following goals.

- Getting Arduino IDE installed and configured. This includes any necessary serial USB drivers.
- Focus on C/C++ code, not Circuit Python.
    - The C/C++ code compiles tighter and runs on smaller processors.
    - Compile-time checking of type and libraries.
    - Debugging infrastructure with Circuit Python (such as missing library dependencies or bad/mismatched function arguments) isn’t fun for beginners.
- Loading code Into the microprocessor.
- Accepting button presses.
- Using the built-in LED blinkey.
- Addressing LEDs on strip.
- Initial code templates shared with group. Don’t have to write from scratch. But we’ll tweak and edit.

## LED Strip Workshop (Milestones)

- USB Power
    - Microprocessors are initially loaded with 1sec on / 1sec off blinkey code. (Either from the factory or by the workshop instructor if not.)
    - Attach to breadboard and USB. Attach USB to laptop.
    - Should see the blinkey.
- IDE install.
    - Install IDE.
    - Load whatever dependencies required for the specific board and libraries we’ll be using.
    - Get familiar with where the examples live.
- IDE connectivity, software load.
    - Load Morse Code blinkey code.
    - Can inspect the code, but no need to understand it right now.
    - This will blink in a different way from the pre-loaded blinkey.
    - It will prove that each person is set up to load code into the microprocessor.
- Explain how solderless breadboards work.
- Wire the light strip and button into the breadboard.
    - Library install
    - ...


