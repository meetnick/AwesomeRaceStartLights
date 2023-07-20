# Awesome Race start lights

This is a Race start lights, which means it not only have red, yellow and green lights, but also includes an integrated buzzer.


## Goals

- Implement the communication protocol.
- Create a program to test the device, according to its protocol, and make sure the hardware is working. Use the provided virtual devices to test it (both working and faulty).


## Bonus Goals

A standard race start lights first light up the RED, then the YELLOW, finally the GREEN light and the Buzzer. In its final state, all lights + buzzer should be ON. The time it stays in the last state should be longer than previous states.

- Create the race start lights controller, so it goes from RED to RED+YELLOW then RED+YELLOW+GREEN+BUZZER.
- Create a test for hardware device controller