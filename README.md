# parametric_defeaturing
FreeCAD macro providing parametric defeaturing inside and outside of Part Design.  Select one or more faces of an object and run the macro.  It will attempt to defeature the object, removing those faces.  Similar in functionality to the Defeaturing tool in Part workbench except this one is parametric and works inside Part Design bodies as well as outside of Part Design.

## Installation
Not available yet in the Addon Manager.  Copy the parametric_defeaturing.FCMacro file to your macro folder.  On first run it will ask to create an additional file, parametric_defeaturing.py, from which it imports the class definitions needed to make the objects created with the macro parametric after restarting FreeCAD and loading a file with one of the objects in it.

## Toolbar Icon
<img src="parametric_defeaturing.svg" alt="toolbar icon"> <a href="parametric_defeaturing.svg">Download</a> the toolbar icon.


### Changelog
* 0.2010.10.05 initial upload
