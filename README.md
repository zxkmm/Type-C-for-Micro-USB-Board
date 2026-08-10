# Type-C-for-Micro-USB-Board
Hardware design file that allow you replace Micro USB slot with a Type-C slot without modify the board

# Soldering
1. Remove the original Micro USB connector
2. Put the adapt board onto the original Micro-USB's position, align the 5 pins and solder them. Provide as much as possible solder so it can flow under the adapt board to make connection, just consider this as soldering a QFN chip.
<img width="1286" height="703" alt="image" src="https://github.com/user-attachments/assets/0845ca72-a785-45ac-b502-c8e035d9dfb9" />
3. Use multi-meter to test connection, because it is the easiest chance to fix connection before doing next step.
4. Put the MC-314C-4P16 on, solder the pins, and **GENITALLY** plug USB cable in to test connection. **Note that you should be very gentile, don't apply any force from the cable, because the connection isn't fixed and you can rip pads off from adapter OR EVEN YOUR ORIGINAL BOARD AND DAMAGE IT!** Test both sides.
<img width="1286" height="794" alt="image" src="https://github.com/user-attachments/assets/e42bf4f7-3f96-450c-b7f8-217ca88c5e5b" />
6. If connection tested good, add as much as possible solder in the side pads, to **secure the connector to the adapter board**.
7. Also add as much as possible solder from the adapter board's exposed copper pads, let the solder connect it into your board's original connector's mounting hole, to **secure the adapter board onto your original board that you are modifying**. The adapter board's pad were designed to compatible with most Micro-USB's old mounting hole's position.
<img width="1034" height="801" alt="image" src="https://github.com/user-attachments/assets/7a5c608f-4182-4745-8dbf-a7cc5fa0e68f" />
8. If you ever plan to use a Type-C to Type-C cable, solder the two resistor per the BOM. If you only use USB-A to Type-C cable, this step is not needed.
