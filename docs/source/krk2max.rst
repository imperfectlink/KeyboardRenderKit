KRK to 3ds Max
====
Exporting to 3d Studio Max is pretty simple. However, there are a couple things we need to do beforehand. 3ds Max doesn't handle ngons as well as well as Blender does but it loves triangles and quads. So let's give it what it wants.

.. image:: img/krk2maxstart.jpg

|

Once your board or kit is ready, hide all of the other objects that you don't want to be a part of the export. It's likely that this would include the scene collection so turn that off.

.. image:: img/TurnOffSceneCollection.gif

|

Once it is the only thing that is visible, select all by pressing A on your keyboard. Then hit tab to enter edit mode on all of the selected objects.

.. image:: img/KeyboardVertices.jpg

|

You need to be in face select mode. The shortcut is 3 on your number row.

.. image:: img/FaceMode.jpg

|

Deselect all by pressing A twice in succession or Alt+A.

.. image:: img/KeyboardFaces.jpg

|

Now go to Select > Select By Trait > Faces By Sides.

.. image:: img/FaceBySides.gif

|

Use the popup in the bottom left to set the type to Greater Than.

.. image:: img/SelectGreaterThan.jpg

|

Now all of the Ngons and only the Ngons are selected.

.. image:: img/KeyboardNgons.jpg

|

Then click on Face > Triangulate Faces or Ctrl+T then press Tab to exit edit mode.

.. image:: img/KeyboardTriangulate.gif

|

Your keyboard is now ready for export. Click on File > Export > FBX. Give your file a name, set the Path Mode to Copy and don't forget to make sure that Limit to Selected Objects is checked.

.. image:: img/krk2maxexportsettings.png

|

Now in Max, import your fbx.

.. image:: img/krk2maximported.png

|
