# Type-C-for-Micro-USB-Board
Hardware design file that allow you replace Micro USB slot with a Type-C slot without modify the board

# Soldering
1. Remove the original Micro USB connector
2. Put the adapt board onto the original Micro-USB's position, align the 5 pins and solder them. Provide as much as possible solder so it can flow under the adapt board to make connection, just consider this as soldering a QFN chip.
<img width="1002" height="627" alt="image" src="https://github.com/user-attachments/assets/cf5ef974-0a77-4faa-8414-0cd36bbec114" />
3. Use multi-meter to test connection, because it is the easiest chance to fix connection before doing next step.
4. Put the MC-314C-4P16 on, solder the pins, and **GENITALLY** plug USB cable in to test connection. **Note that you should be very gentile, don't apply any force from the cable, because the connection isn't fixed and you can rip pads off from adapter OR EVEN YOUR ORIGINAL BOARD AND DAMAGE IT!** Test both sides.
<img width="986" height="698" alt="image" src="https://github.com/user-attachments/assets/43a1475b-d892-4044-8361-2fa84583425d" />
5. If connection tested good, add as much as possible solder in the side pads, to **secure the connector to the adapter board**.
6. Also add as much as possible solder from the adapter board's exposed copper pads, let the solder connect it into your board's original connector's mounting hole, to **secure the adapter board onto your original board that you are modifying**. The adapter board's pad were designed to compatible with most Micro-USB's old mounting hole's position.
<img width="1364" height="770" alt="image" src="https://github.com/user-attachments/assets/f00906ce-d92f-4f69-a685-582f1616f1b5" />
7. If you ever plan to use a Type-C to Type-C cable, solder the two resistor per the BOM. If you only use USB-A to Type-C cable, this step is not needed.
