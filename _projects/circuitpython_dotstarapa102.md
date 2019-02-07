---
layout: project
title: CircuitPython_DotStarAPA102 - CircuitPython based driver for Adafruit DotStar LED strings using APA102 controller chips
---

Repo: [https://github.com/dhocker/CircuitPython_DotStarAPA102](https://github.com/dhocker/CircuitPython_DotStarAPA102)

CircuitPython_DotStarAPA102 is a CircuitPython based driver for Adafruit DotStar strings 
that use the APA102/APA102C chip. It was inspired by the
[Adafruit_DotStar_Pi](https://github.com/adafruit/Adafruit_DotStar_Pi)
package. By basing the driver on CircuitPython we avoid the need for C/C++ code like
that found in the Adafruit_DotStar_Pi package.

**DotStarAPA102 is specifically designed for the Raspberry Pi.**

This driver provides a set of methods and properties that facilitate
manipulating the addressable pixels of a DotStar LED string. The driver
treats the DotStar string as a linear array of pixels where each pixel
is defined by brightness, red, green and blue (BRGB). The first pixel
of the string is pixel 0 while the last pixel of the string is pixel n - 1
(e.g. n = 30 for a 30 pixel string).

The methods facilitate setting individual pixels (set_pixel) or slices of
pixels (fill).
