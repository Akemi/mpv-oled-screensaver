## mpv-oled-screensaver

Due to  burn-in problems on OLED TVs i decided to script a screensaver for mpv.
After 15 seconds when paused it just fades-in a black screen.


## Options

#### startAfter
Time after screensaver is shown in seconds (Default: 10s).

#### screensaverColor
Colour of the screensaver in ASS hex BBGGRR (Default: "000000").

#### rainbow
Instead of using one colour, use a rainbow colour transition (Default: false).

#### rainbowStep
How many colour steps per period (Default: 1).

#### rainbowRedrawPrediod
Time between redraws of the rainbow in seconds (Default: 0.03).

#### alphaStep
How many steps for the fade-in of the screensaver (Default: 12).

#### luminance
The Luminace of the rainbow colours (Default: 255).
