Custom Board
====

This tutorial isn't going to cover export settings from your CAD software. Export your design as an OBJ or FBX and import it into Blender. Alternately, you can use the Stepper Blender addon to import the STEP/STP file directly.

|

As an example, let's use Alchemist Keyboards Aella render file converted to OBJ. `Right Click > Save <https://github.com/imperfectlink/KeyboardRenderKit/raw/main/docs/source/files/AKB_Aella.obj>`_

|

In a new Blender file, delete the contents (cube, camera, light) and set your Units to millimeters in the Scene Properties tab of the Properties Panel.

|

Now you can import the Aella OBJ by clicking File > Import > Wavefront Obj

|

The first thing you'll notice is that the scale is incorrect. In this case the millimeter units were plugged into meters. Scale the board to a thousandth by pressing S 0.001 .

|

Now apply the scale and rotation by pressing ctrl+A then A again to apply All Transforms.

|

Now let's create a move handle. Press Add > Mesh > Plane.

|

Hold Shift and click on the board's case to add it to the selection.
