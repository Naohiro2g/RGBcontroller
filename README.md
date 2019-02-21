# RGB Controller
Forked from https://github.com/ebbesmoeller/RGBcontroller
(Simple program using Python and module gpiozero to host a webinterface with a color wheel, controlling the color of a RGB led connected to GPIO on a RaspPi.)

# As a new tool to do:  (not yet)

 - Add the Color Correction mode on top of the exist Color Presentation mode.
   You can get correction factor for each LED of R, G, and B to produce real white light.
 - Add three sliders to adjust brightness of the real LED each by R, G, and B.
 - Add [Brightness] slider to change the total brightness of the real LED.

# Color Correction mode  (not yet)

1. Press the [Correction] button to get into the Color Correction mode.
2. Pick a 'white' color by color picker with seeing the real LED connected to RPi looks as white.
3. Press the [Set] button to create correction factor values for R, G, and B, like 1.00, 0.63, 0.89.
4. Color Correction done and now you came back to the Color Presentation mode.
5. You can reproduce real white and well-balanced colors by your full-color LED with the correction factor values.

