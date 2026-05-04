# The Claw - pick-and-place head

A relatively cheap way to do manual pick and place by converting a 3D printer.

![image](/assets/pnp-head.png)

## Control/software

This just uses whatever Pi camera streaming software you want, plus Octoprint/serial to control it, like any printer. No special firmware is generally required (depending on your specific wiring). Octopi works great for this, as it provides both a camera view and serial/controls.

## Assembly

Just print all the parts, then assemble it all together - it should be pretty self-explanatory, given the assembly image.

- The stepper motor controls the rotation of the components, and is screwed in from the top
- The solenoid controls vacuum on/off, that's not included on the head as it's extra weight as well as being hard to mount - put it near the air pump.
- There is a spring resting between the lower shaft and the roof, which is used to keep the component pressed down while allowing it to press into the bed without breaking anything..
- The nozzle is mounted using a silicone connector which has the lower shaft tip on one size and the nozzle on the other to ensure proper fit.

The silicone is used to make nozzles fit properly - creating the mold is left as an exercise to the reader, as nozzle dimensions aren't available, hence the components are required to create the silicone mold.

## Wiring

Your wiring can vary significantly, but the only control besides just basic movement is turning the solenoid on/off. If your fan headers can provide enough current, that will be the easiest way to control it.

## Parts

| Item name               | Price | Quantity | Link                                                                                      | Total    |
| ----------------------- | ----- | -------- | ----------------------------------------------------------------------------------------- | -------- |
| NEMA 17 motor (XH)      | 7.06  | 1        | <https://www.aliexpress.us/item/3256808273084374.html>                                    | 7.06     |
| Spring (45x13)          | 3.17  | 1        | <https://www.aliexpress.us/item/3256808172121056.html>                                    | 3.17     |
| 6x8 5m tubing           | 5.46  | 1        | <https://www.aliexpress.us/item/3256809523563550.html>                                    | 5.46     |
| 24V Air pump            | 11.4  | 1        | <https://www.aliexpress.us/item/3256807520990953.html>                                    | 11.4     |
| Silicone                | 25.62 | 1        | <https://www.amazon.com/BBDINO-Elastic-Silicone-Making-Casting/dp/B0DK9GD52Q>             | 25.62    |
| AF-65 camera            | 4.65  | 1        | <https://www.aliexpress.us/item/3256803200476731.html>                                    | 4.65     |
| Solenoid                | 5.88  | 1        | <https://www.aliexpress.us/item/3256807858795768.html>                                    | 5.88     |
| 8x12x3.5mm bearing      | 2.51  | 1        | <https://www.aliexpress.us/item/3256807442294068.html>                                    | 2.51     |
| Blunt needles (nozzles) | 7.99  | 1        | <https://www.amazon.com/Dispensing-Industrial-Dispenser-Stainless-Adhesive/dp/B09CL4RB5X> | 7.99     |
|                         |       |          |                                                                                           |          |
|                         |       |          |                                                                                           |          |
|                         |       |          |                                                                                           |          |
| Total                   |       |          |                                                                                           | 79.82355 |
