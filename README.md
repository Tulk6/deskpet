# deskpet

This is an internet radio and alarm clock that can function as a general internet connected hub. it's made up of two boards - one with a screen, buttons, and rotary encoders for controls, and the other with an ESP32-S3-WROOM, MAX98357A amp, speaker cable connectors, temp sensor, and an LED. Tne two boards are connected via a flat flex cable, and sit inside a 3D printed case. it is powered via a USB-C cable at the back. 

The display used is a monochrome LCD matrix display, so that the device can be left on at night without producing distracting light as an LED screen would. It comes with a backlight as well to allow for nighttime operation.

The amp will drive a small mono speaker fixed within the case.

Given the ESP32-S3 can connect to the internet, in addition to functioning as an internet radio and alarm clock, the device will also be able to fetch RSS streams and check weather information. 

The planned ui will feature tamagotchi elements, with a character that wakes at your alarm, listens to the radio with you, reacts to changes in temperature, and acts differently depending on the time.

The two rotary encoders also contain buttons, which along with two other buttons allow for a range of inputs. One rotary encoder will function as volume/mute, the other to select options. One of the buttons will be a return button, and the other a home button.

![](screenshots/full.png)

The assembled device

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTMwOTMsInB1ciI6ImJsb2JfaWQifX0=--0f190f50af62074da17d28b49e2736ef89ab9bd3/image.png)

The main board

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTAyNTgsInB1ciI6ImJsb2JfaWQifX0=--771b79f1734833de02d010591e5ab0a39bcf8eb1/image.png)

The display board 

![](screenshots/ioboard.png)

![](screenshots/mainboard.png)

![](screenshots//backplate.png)

^ The back of the device, with the backplate visible.

![](screenshots/back.png)

^ The back of the device without the backplate.

![](screenshots/back2.png)

![](screenshots/front.png)
