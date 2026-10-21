# bamb-boo's mechanical keyboard!

This is a custom mechanical keyboard using a raspberry pi pico and really nice switches!!

##### Features!

- Has 83 keys (~75% keyboard)

- Non-hotswappable Akko V3 Creamy Purple Pro Switches (hotswappable will increase cost and design time, so kept it simple ;] )

- Runs on a Raspberry Pi Pico due to its powerful chip and the number of IO pins (26 pins)

- Has a 16x6 matrix, which is all I need for my needs (_not_ an aspiring accountant, though it'll be cool to have a larger keyboard)

- 1N4148 through-hole diodes to prevent ghosting (The matrix is a useful way of succinctly employing a limited number of IO pins for a large number of keys)

##### Why I made it

To be honest, I had a faulty laptop keyboard, and wanted to get a mechanical keyboard. Creating my own keyboard >>> buying a pre-made one, so I just decided to make one on a whim! ✨

##### Future scope-

I would REALLY love to make a-

- A keyboard using a touchscreen to for more efficiency (and fun, who doesn't like repeating GIFs)
- Wireless version using Pi Pico W (because you can't always stay connected to your laptop!)
- Make a larger keyboard (because larger is always equal to better!)


##### Photos-

<img width="839" height="346" alt="image" src="https://github.com/user-attachments/assets/c96cda9d-6473-421f-9c8e-dd984b5420d2" />

(looks kinda wonky because my laptop became incredibly slow, and it was trouble to get anything done let alone model in fusion 360.)

<img width="690" height="263" alt="image" src="https://github.com/user-attachments/assets/42d33c03-15f2-44a1-9353-8f0c402bd36f" />

(just case)

<img width="772" height="266" alt="image" src="https://github.com/user-attachments/assets/9562e222-a7a4-4aeb-ac46-baf9fb8c4f35" />

(case+pcb)

<img width="1074" height="402" alt="image" src="https://github.com/user-attachments/assets/63e0763a-c8b1-49e8-9323-9a572e5acece" />

(pcb)

<img width="1861" height="515" alt="image" src="https://github.com/user-attachments/assets/20344622-14e4-4cd2-9a9f-9516e02955ce" />

(schematic)

##### Build instructions-

1. Solder the diodes to the designated holes in the pcb, with the diodes pointing down.

2. Solder the pi pico using headers onto the pcb

3. Flash the firmware-
    plug in the usb and connect it to a laptop.
    Drop the .uf2 file 

4. Use [https://www.keyboardtester.com/tester.html](https://www.keyboardtester.com/tester.html) to test if all connections are correct- this mitigates the need to annoyingly verify if all connections are right later on

5. Solder the switches to the holes beside the diodes.

6. Clip the stabilizers onto the pcb.

7. Attach the keycaps to the switches.

8. Attach the pcb to the plate, ensuring the fit snugly.

9. Bolt the plate to the case using the screws.

10. Viola, you're done!

Finally, I heartfully thank PCBWay for their sponsorship, which allowed me to experiment and become a creator. Their quality is very high and they offer a wide range of helpful services such as PCB manufacturing, 3D-printing and CNC machining. Visit PCBWay at [PCBWay](https://www.pcbway.com)
![PCBWay logo](https://images.squarespace-cdn.com/content/v1/59b037304c0dbfb092fbe894/1574266723216-3GI9YH3SC37PUJ0DMA9C/image-asset.png)

[Bill of Materials](https://github.com/bamb-boo/keyboard/blob/main/cart/README.md)-
| Component name    | Details                          | Qty        | Bought from                                                                                                                                                                                                                                                          | Cost (usd) |
|-------------------|----------------------------------|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| Case              | ABS                            | 1          | pcbway| free       |
| Plate             | PLA                            | 1          | pcbway| free       |
| Switches          | Click Inc HP Switch (Pack of 10) | 9 packs    | https://stackskb.com/store/click-inc-hp-switch-pack-of-10-pre-order/ | 17         |
| Keycaps           | Color PBT                        | 83 keycaps | https://meckeys.com/shop/accessories/keyboard-accessories/keycaps/colour-pbt-keycaps/| about 11   |
| M2 nuts and bolts | 15 mm height                     | 8          | Local vendor| 1          |
| Microcontroller   | Raspberry Pi Pico                | 1          | https://quartzcomponents.com/products/raspberry-pi-pico?variant=37945289801912&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AfmBOooph4yAOKlaXOlzuqV4wVWYXD59shyxalMg0NoKKp0ef7S1frVsyPs | 3.5        |
| Stabilizers       | 4 x 2u + 1 x 6u                  | 5          | https://www.genesispc.in/products/durock-plate-mount-stabilizers-6-25u-4x2u-black?variant=43129560924213| 4          |
| Diodes            | 1n4148                           | 83         | https://www.ktron.in/product/diode-1n4148-th/?srsltid=AfmBOoqAQ2ie58oqGB9lnuLERS_E0bK5uivKzd28IHgtJRiMNgbBmKTvdes| 0.6        |
|Total              |                |114           |                 |  |

