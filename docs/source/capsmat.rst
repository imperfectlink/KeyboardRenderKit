Capsmat
====

.. image:: img/Capsmat.jpg

Settings
~~~~
Cap
^^^^
This is the base color of the keycap which can be controlled by the color field of by using the socket with a palette.

Legend
^^^^
This is the legend color. You can choose a color, plug in a palette to control the color or even plug an image into the socket for full color legends.

Legend Mask
^^^^
A white on black image is plugged into this socket to mix between the cap color and the legend color.

Sharpen Legend
^^^^

.. image:: img/SharpenLegend.gif

This is used to sharpen the edge of the legend to appear as a doubleshot legend would. This is set to full by default but you can slide it to zero to simulate more of a dye sublimated look.

Legend Weight
^^^^

.. image:: img/LegendWeight.gif

Due to the way the legend sharpening works, you may also wish to offset the weight to bolden the legend. A smaller number means a bolder legend.

Sub
^^^^
This is the color of the sublegends.

SubMask
^^^^
This is the socket that you can plug in your sublegend files.

Sharpen Sub
^^^^
Like Sharpen Legend, this does the same for sublegends.

Sub Weight
^^^^
Same as Legend Weight but for sublegends.

Front
^^^^
This is the color for the front legends.

Front Mask
^^^^
This is the socket for the front legend mask.

Shapen Front
^^^^
Same as Sharpen Legend but for front legends.

Front Weight
^^^^
This is the same as Legend Weight but for front legends.

Roughness
^^^^

.. image:: img/Roughness.jpg

This is the overall roughness or glossiness for the keycap material. This will vary depending on what type of plastic or finish you are aiming for. For example, PBT will generally have a higher roughness than ABS.

Bump Scale
^^^^

.. image:: img/BumpScale.jpg

This is the scale or grain of the bump noise. Think of it the same as grit for sandpaper in that a larger number represents a higher density.

Top Bump
^^^^

.. image:: img/KeycapBump.JPG

This is the intensity of the bump at the top of the keycap.

Side Bump
^^^^
This is the intensity of the bump at the back, front and sides of the keycap.

Legend Seam
^^^^

.. image:: img/LegendSeam.jpg

Some doubleshot processes result in a more pronounced seam between the legend and the keycap.

|

Masks
~~~~

.. image:: img/LegendsDemo.jpg

A mask is a white on black image that defines how to mix two colors or elements together. Consider white to be ON and black to be OFF.

|

.. image:: img/LegendMask.JPG

In the capsmat, masks are used to mix the cap with the legend, the cap with the sublegend and the cap with the front legend. If any of these are not present, it will assume black or off for that portion. 

|

.. image:: img/LegendsTemplate.png

KRK comes with templates to make generating these masks simpler. 

|

The Palette Workflow
~~~~

KRK2 introduces a new workflow to help with color exploration and design. As you've seen by now, the KRK panel lets you you control the color of the keycaps on an individual basis. You can start off with a custom color per keycap and then drag those colors into a palette to define your colorway.
The palette node groups are the other component to this workflow.

.. image:: img/Palettes.jpg

The palettes range from A-E as well as a standalone palette for driving the from the material editor. They have eight slots for colors while Palette E has four for color and four more for alphas.

|
