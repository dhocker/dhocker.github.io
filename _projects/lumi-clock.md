---
layout: project
title: lumi-clock - Digital clock inspired by various Lumitime clocks
---

Repo: [https://github.com/dhocker/lumi-clock](https://github.com/dhocker/lumi-clock)

This project is a relatively simple digital clock app that was inspired
by the Lumitime clocks of the '70s and '80s. It uses Python3 and
Tkinter for
the GUI and the Pillow package for implementing an animated GIF.
It was originally conceived as a Raspberry Pi based project.

The clock display takes over the enitre screen. It displays the current time,
an AM/PM indicator and a spinner (an animated GIF). The time display
is sized so that it looks good on a tablet sized display (say 7"-8").

![Screen Shot](https://github.com/dhocker/lumi-clock/raw/master/screenshot.png "Screen Shot")

The app also supports a PIR motion sensor. This allows the app to turn
the clock display on or off based on the motion sensor. This allows
the clock to run 7/24 with reasonable wear on the display.

# Caveat
There are known issues with the PIR sensor and RPi's that have WiFi. The PIR sensor will
report false positives due to WiFi activity. At this time, no good alternative 
or workaround has been identified.
