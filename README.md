RotaryEncoder
=============

Forked in 2015 and modified for personal project

## Changes:

* Added acceleration support with `setAccel(boolean value)`
Meaning that the faster the encoder is rotated the greater the step of increment/decrement will be and keeping in mind that the encoder must be able to step by 1 if rotated slowly enough. Threshold time between steps is 150ms


## Credits

Original library by [**mathertel**](https://github.com/mathertel)


## Original readme

>A Library for the Arduino environment for using a rotary encoder as an input.
>
>Here you can find an Arduino compatible library for using rotary encoders.
>
>I was searching a library for using a rotary encoder in my latest project and found a lot of information on this topic but none of the existing libraries did immediately match my expectations so I finally built my own. 
>
>The article on my web site explains the software mechanisms used in detail so you can understand
>the coding and might be able to adjust it to your needs if you like:
>
>http://www.mathertel.de/Arduino/RotaryEncoderLibrary.aspx
>
>
>There are various aspects when writing a library for rotary encoders and you can also find a lot of the sources I analyzed at the bottom of this article. 
