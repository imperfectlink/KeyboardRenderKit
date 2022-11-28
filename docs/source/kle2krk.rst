KLE To KRK
====

While Keyboard Layout Editor doesn't name its objects, naming is a required attribute for both Blender and Keyboard Render Kit to function properly. Blender names both its objects and the object data that they contain. Keyboard Render Kit largely ignores object names but it relies heavily on object data names to operate. Once this is understood, the path between KLE and KRK is quite reliable.

|

What can you expect to translate into KRK? The translator takes into consideration size, legend, row, color (cap and legend), position and rotation. You may modify the last three without repercussion but know that a keycap may not import if you modify the first three and there is no destination object data.

|

`Keyboard Layout Editor Example <http://www.keyboard-layout-editor.com/#/gists/f7528ebe1348daab7abc45bc2f662c8a>`_

|

This layout is the testing ground for KLE to KRK translation and loads into KRK and serves as good reference. If you haven't started your layout yet, this is a good place to begin. It may look familiar and that is because it is the layout that is used for keycap UV and textures in KRK.

|

Take note of the legend and row designations since these are what is used for translation into KRK. If you make modifications, they may not translate at all. Remember, the legends themselves are not translated and they only serve as a keycap name. Once you are in Blender the keycap can have any legend on it through legend masks.
