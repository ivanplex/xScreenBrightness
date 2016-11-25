# xScreenBrightness

An alternative for xbacklight. It uses xrandr to adjust your main screen's backlight level.

Usage
-----

brightness [brightness or percentage adjustment]

~~~bash
#Increase brightness by 5%
brightness 5%
brightness 0.05

#Decrease brightness by 5%
brightness -5%
brightness -0.05

#Return current brightness
brightness
~~~

Dependency
----------
- xrandr
- bc
