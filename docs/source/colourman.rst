Colour Management
====


Colour management in Blender is in linear colour space with the View Transform set to AGX (or Filmic before 4.0). While these view transforms include a wide dynamic range, it will cause your chosen colours to appear "washed out" or low contrast when no prost processing is applied.

|

This workflow assumes you'll be doing some post processing to grade the colour into a more faithful result. Since not a lot of people (especially newer users) are doing this, KRK (as of KRK211) is set to Filmic with Medium High Contrast and then in post (the compositor), is undergoing a conversion from Filmic to sRGB to produce a more expected result.

|

The viewports are set so that what you see passes through the compositor process. If you create a new 3d viewport, remember to turn on the compositing to "Always" so that the colour is properly reproduced.

|

Remember, your eyes have the final say. Always compare to a physical reference.
