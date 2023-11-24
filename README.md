# PUTM_Kicad_Library

## Use impartGUI

## Adding new parts
This branch bases its folder / lib structure on a structure created by the impartGUI (kicad plugin) so use it to it's op :>. However this plugin creates all symbol libs in the legacy version, we can used the but not edit them if necessary, so we need to take a extra few steps to import them to newest version, for that there is a SamacsysNew.kicad_sym file. The footpint lib and 3dlib is good as it is.
<p align="center">
  <img src=https://github.com/PUT-Motorsport/PUTM_Kicad_Library/assets/26027009/4f5cbd89-4321-449a-a492-ac6d437e50f5/>
</p>
Haveing added both the legacy version and newest version now we can copy/paste symbols between those libraries. It's better to copy/paste them rather than using the import/export feature since it creates a new kicad symbol library every time u export a symbol. It's possible to export symbols to other libraries but the kicad symbol manager breakes and it would need a restart to properly show newly exported symbols. Summing up just copy needed symbols.
<p align="center">
  <img src=https://github.com/PUT-Motorsport/PUTM_Kicad_Library/assets/26027009/9bbf6fc3-321c-49ae-b761-ff49862cde91>
</p>
And paste them in the SamacsysNew symbol library.
<p align="center">
  <img src=https://github.com/PUT-Motorsport/PUTM_Kicad_Library/assets/26027009/bd42795d-e8b0-4089-ad6c-f36fdf55cbf1>
</p>

