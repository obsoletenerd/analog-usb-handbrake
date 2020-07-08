# Analog USB Handbrake for Racing Sims

A conversion kit to turn any real car handbrake (eg cheap drift/race handbrakes from eBay/Amazon) into an analog USB handbrake for racing sims.

## Required

- Cheap drift/race handbrake such as [this one](https://www.amazon.com.au/Kyostar-Universal-Hydraulic-Handbrake-Parking/dp/B07WPS87Y3/) (similar are available from all major online marketplaces)
- Generic gate spring (experiment with the size/strength you like)
- Arduino Pro Micro / Leonardo
- 10k sliding potentiometer
- Zip ties
- 3D printer



## Instructions

Attach [Potentiometer Bracket](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Potentiometer-Bracket.stl) to the front of the potentiometer.

![Potentiometer Bracket](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Meta/Analog-USB-Handbrake-Pot-Bracket-1.jpg)

Strip the handbrake of all non-required parts. You just need the handbrake lever itself and the supporting frame.

Zip-tie the spring to the rear-end of the handbrake frame/chassis, then to any available point on the handbrake lever itself. In my case, this spring is temporary, and I have a better idea I'm working on and will update this page to suit later.

Screw the sliding pot bracket to the inside edge of the handbrake frame/chassis, using some of the leftover bolts from stripping the handbrake (I found I had more than enough).

![Potentiometer Bracket](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Meta/Analog-USB-Handbrake-Pot-Bracket-2.jpg)

Clip the [Connecting Arm](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Connecting-Arm.stl) to the potentiometer slider and then put a bolt through the other end to attach it to the handbrake lever itself.

![Handbrake Lever Attached](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Meta/Analog-USB-Handbrake-Lever.jpg)

Flash [the Arduino code](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Arduino-Analog-USB-Handbrake/Arduino-Analog-USB-Handbrake.ino) onto the Arduino Leonardo/Pro Micro, and connect the wiring (Pot pin 1 to VCC, pot pin 2 to A0, and pot pin 3 to GND).

![Wiring Diagram](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Meta/Wiring-Diagram.png)

![Wiring Photo](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Meta/Analog-USB-Handbrake-Wiring.jpg)

Place the Arduino into the [Arduino Case](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Arduino-Case.stl) to insulate the back of the Arduino from touching the metal handbrake parts, and hot glue it into place, and optionally cover it with the 3D printed [Arduino Lid](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Arduino-Case.stl) (I did clear, so I can see the LEDs still).

![Finished Analog USB Handbrake](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Meta/Analog-USB-Handbrake-Finished.jpg)

Go get sideways!

![Analog USB Handbrake on the Sim](https://github.com/obsoletenerd/analog-usb-handbrake/blob/master/Meta/Analog-USB-Handbrake-On-Sim.jpg)