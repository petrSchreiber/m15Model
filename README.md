# m15Model
thinBasic solution for m15 3D model management

## About the project
This effort seeks for new ways to further simplify the use of m15 3D models in thinBasic scripts.

There are three main goals:
-   simplify the model handling and instancing
-   optimize the rendering via TBGL GBuffer backend
-   enable load from memory

## About m15
M15 is a model format specification, which targets to shield the thinBasic users from struggle with various formats and variations of OBJ.
This is achieved by providing middle layer, TBGL OBJ2M15, to perform the conversion to strict format, which can be loaded safely without further complex checks.

Useful links:
[Model format specification](http://psch.thinbasic.com/data/thinEdgeM15_fileformat.pdf)
[OBJ 2 M15 conversion tool](http://www.thinbasic.com/community/showthread.php?8585-TBGL-OBJ-to-M15-converter-UPDATED-to-v-1.4)
