.. _doc_ui-overview_build-report-assets:
 
Used and Unused Assets
======================

These two panels give you a detailed list of the assets included or not in your build. 

.. image:: images/build-report-assets/assets.png

Assets Information
------------------

The **Total Size** on top of the list is the sum of all the assets *Imported Size*.

Imported Size 
   This is the size of the asset after it was imported in the player. For example, if the asset is a .psd file and is imported under
   the format ETC 4 bits in the player, then Imported Size will display the size of the later. 

Raw Size 
   This is the original size of the asset imported in Unity. This is the size that directly impacts your VCS repository size.

Percentage 
   This is the percentage that represents the *Imported Size* over the total size of the build you can read on the *Overview* panel.

.. note:: Note that you can re-order the assets by clicking on the columns header.

Filtering
---------

Simple search
:::::::::::::

You can filter which assets should be listed by entering a value in the search field. .Peek will list all the
assets which path contains all of the word you input. For example, if you enter ``.png car``, all the asset with a path
containing *.png* and *car* will be displayed. **The search field is case unsensitive.**

Typed search
:::::::::::::

You can also filter the assets by type. You simply need to input ``t:[asset type]``. This can be used on top of the
simple search, like for example : ``car t:texture renault``. The values accepted are:

t:texture
   Displays files with extention : *.png*, *.tga*, *.psd*, *.tif*, *.jpg*, *.jpeg*, *.gif*, *.bmp*, *.iff*, *.pict*

t:audio
   Displays files with extention : *.mp3*, *.ogg*, *.wav*, *.aiff*, *.aif*, *.mod*, *.it*, *.s3m*, *.xm*

t:model
   Displays files with extention : *.fbx*, *.dae*, *.3ds*, *.dxf*, *.obj*, *.skp*, *.ma*, *.mb*, *.max*, *.c4d*, *.blend*

t:plugin
   Displays files with extention : *.dll*, *.jar*, *.so*, *.aar*, *.a*

t:shader
   Displays files with extention : *.shader*, *.cginc*

These extensions are based on what is supported in Unity. Don't hesitate to create a pull request or open an issue on 
Github if you find out relevant to add an extension here.
